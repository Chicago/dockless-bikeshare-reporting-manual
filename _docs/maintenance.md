---
title: Maintenance
category: Monthly Submission
order: 3
---

## Scope

All reports, violations, and complaints issued to the company. Should include all customer reports, even if the report cannot be verified or was an invalid complaint.

## File Format

Maintenance data must be reported using the following schema and reported with the following `[company]-maintenance-[date].csv`.

| Field | Element                  | Data Type           | Required | Description                                                                                 |
| M1    | Bike ID                  | String              | Yes      | A unique ID for the bicycle. Should be the same ID used in the Trips file.                  |
| M2    | Maintenance Date         | ISO 8601 date       | Yes      | Timestamp of when the maintenance was conducted. The timestamp (hour/minute) not required.  |
| M3    | Description              | String              | Yes      | Text description of the maintenance completed.                                              |