# Deloitte Technology Job Simulation – Telemetry Data Conversion

## Overview

This project was completed as part of the Deloitte Technology Job Simulation.

The objective is to reconcile telemetry data coming from two different Industrial Internet of Things (IIoT) data formats and convert them into a single unified structure required by the client, Daikibo Industrials.

## Project Structure

```text
.
├── main.py
├── data-1.json
├── data-2.json
└── data-result.json
```

## Task

Two different telemetry message formats are provided:

* Format 1 (`data-1.json`)
* Format 2 (`data-2.json`)

The goal is to transform both formats into the unified target format defined in `data-result.json`.

The implementation includes:

* Parsing telemetry data from two source formats
* Converting location information into a structured format
* Mapping device and operational data fields
* Converting ISO 8601 timestamps into Unix epoch milliseconds
* Validating results using automated unit tests

## Technologies Used

* Python 3
* JSON
* unittest
* datetime

## Running the Project

Clone the repository and run:

```bash
python main.py
```

or

```bash
python3 main.py
```

## Expected Output

Successful execution will produce output similar to:

```text
----------------------------------------------------------------------
Ran 3 tests in 0.0xxs

OK
```

## Learning Outcomes

* Data reconciliation across heterogeneous sources
* JSON transformation and normalization
* Timestamp conversion and standardization
* Automated testing with Python unittest

---
## Certificate
<img width="530" height="408" alt="Screenshot 2026-06-08 211158" src="https://github.com/user-attachments/assets/964b3f7d-d236-404f-b699-2e8e06392327" />
---

## Participant

Completed by **Sattwik** - [GitHub](https://github.com/sattwik-07)
