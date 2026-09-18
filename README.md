# Playwright Python Automation Portfolio

This project contains beginner-level automated tests created with Python, Playwright, and pytest.

## Tools Used

- Python
- Playwright
- pytest
- VS Code
- GitHub Copilot

## Current Test Coverage

### Successful Login Test

The login test:

- Opens SauceDemo
- Enters a valid username
- Enters a valid password
- Clicks the Login button
- Verifies navigation to the inventory page
- Verifies that the Products page is visible

## Installation

Create and activate a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate

## Install Dependencies: ##

pip install -r requirements.txt
playwright install