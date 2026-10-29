# Release Audit

## Project Description

Small Python program for displaying support-ticket information.

## Requirements

- Python 3.12 or newer
- Git
- project dependencies from `requirements.txt`

## Set-up Instructions

- Clone repository: git clone https://github.com/BenDensmore59/CPS310-ICA08-DevOps.git
- Create .venv: python -m venv .venv
- Activate .venv: .\.venv\Scripts\Activate.ps1
- Install dependencies: python -m pip install -r requirements.txt

## Configuration 

- Project settings are stored in config.json file
- "data_file" controls the file that stores the tickets
- "report_title" controls the title that appears overhead after running the program
- "high_priority_threshold" controls the boundary for determining high priority tickets

## Run Program

```text
python release_audit.py
```

## Run Tests

python -m pytest -v

## Run Verification Script

.\verify.ps1

## Release Statement

The program is now updated with a verification script, functioning test suite, configuration file,
and up-to-date .gitignore to encourage easy reproducibility.
