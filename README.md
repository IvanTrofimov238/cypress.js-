# Cypress UI Autotests

A learning project: end-to-end UI tests written with the Cypress framework during a QA training course (2024). The suite covers the login form at `https://login.qa.studio/`.

## What's inside

- `автотесты.cy.js` — a single Cypress spec with 6 test cases:
  - positive login flow
  - password recovery flow
  - negative login (wrong password)
  - negative login (wrong email)
  - email validation check
  - email case-insensitivity check

## Requirements

- Node.js 16+
- Cypress (`npm install cypress`)

## How to run

```bash
npx cypress open    # interactive mode
npx cypress run     # headless mode
```

Place `автотесты.cy.js` under `cypress/e2e/` of a Cypress project, or point Cypress at this file directly.

## Status

Course exercise (2024). Written while learning web UI test automation.
