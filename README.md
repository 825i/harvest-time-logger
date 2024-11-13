# harvest-time-logger
Logs billed time to two instances of Harvest for 2 weeks in advance

## Description

Uses Harvest v2 API to log time entries to two separate Harvest instances for the same project.

I created this Python script when when a client project required me to log my hours to two separate systems. This script avoids having to separately log every single day twice in two separate systems.

## Requirements

- Python 3
- 2 Harvest API tokens
- Requests pip package
- Relevant Harvest permissions

## Usage

1. Fill in your account ID and harvest tokens
2. Run the script

The script will log by default 7.5 hours Mon-Fri to the same group in both Harvest instances.

Absolutely no warranty is implied whatsoever when using this script.
You are responsible for any damage you do by running this script.
