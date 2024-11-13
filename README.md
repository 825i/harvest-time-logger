# harvest-time-logger
Logs billed time to two instances of Harvest for 2 weeks in advance

## Description

Uses [Harvest v2 API](https://help.getharvest.com/api-v2/) to log time entries to two separate Harvest instances for the same project.

I created this Python script when a client project required me to log my hours to two separate [Harvest](https://www.getharvest.com/) systems. This script avoids having to separately log every single workday twice to two separate systems.

## Requirements

- Python 3
- 2 Harvest API tokens
- [Requests](https://pypi.org/project/requests/) pip package
- Relevant Harvest permissions

## Usage

1. Fill in your account ID and Harvest tokens
2. Fill in the URLs of the 2 Harvest instances
3. Change the relevant project names you want time logged under
4. Run the script

The script will log by default 7.5 hours Mon-Fri to the same group in both Harvest instances.

Absolutely no warranty is implied whatsoever when using this script.
You are responsible for any damage you do by running this script.
