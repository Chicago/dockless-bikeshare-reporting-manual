---
title: Customer Reports
category: Monthly Submission
order: 2
---

## Scope

All reports, violations, and complaints issued to the company. Should include all customer reports, even if the report cannot be verified or was an invalid complaint.

## File Format

Session data must be reported using the following schema and reported with the following `[company]-reports-[date].csv`.

| Field | Element                  | Data Type           | Required | Description                                                          |
| R1    | Violation ID             | String              | Yes      | A unique ID for the violation.                                       |
| R2    | Date and time reported   | ISO 8601 timestamp  | Yes      | The date and time of when the violation was reported to the vendor.  |
| R3    | Description              | String              | Yes      | A text description of the violation.                                 |
| R4    | Resolution               | String              | Yes      | A test description of the violation.                                 |
| R5    | Latitude                 | Latitude (WGS84)    | Yes      | Latitude of the location of the violation.                           |
| R6    | Longitude                | Longitude (WGS84)   | Yes      | Longitude of the location of the violation.                          |