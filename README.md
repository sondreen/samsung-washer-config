# GitHub-safe washing-machine configuration

This directory is a sanitized copy of the Home Assistant washing-machine files.

## Changes made

- Replaced personal notification targets with example entity IDs:
  - `notify.mobile_app_primary_phone`
  - `notify.mobile_app_secondary_phone`
- Replaced the personal presence entity with `person.secondary_user`.
- Replaced aliases containing personal names with `primary user` / `secondary user`.
- Replaced the live helper-state dump with `Helpers_and_sensors.yml`, containing
  YAML examples only. Exact state values and timestamps were intentionally omitted.
- No passwords, API keys, tokens, webhook URLs, private IP addresses, or other
  credentials were found in the supplied files.

## Before using

Change the example notification/person entities to match your own Home Assistant
installation. If your helpers are created through the Home Assistant UI, do not
also define the same helpers in YAML.
