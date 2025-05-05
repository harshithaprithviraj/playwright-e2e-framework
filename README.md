# Playwright E2E Framework

This repository contains a robust End-to-End (E2E) testing framework built using [Playwright](https://playwright.dev/), with support for Cucumber-style BDD, modular page objects, and cross-browser execution.

## 🛠️ Project Structure

- `features/` – Cucumber feature files
- `tests/` – Test specs in JavaScript and TypeScript
- `pageobjects/`, `pageobjects_ts/` – Page Object Models (JS and TS)
- `utils/`, `utils_ts/` – Reusable utility functions
- `allure-results/`, `allure-report/` – Test reporting with Allure
- `.github/workflows/` – CI setup for GitHub Actions

## 🚀 Getting Started

1.Install dependencies:
   ```bash
   npm install

2.Run tests:
npx playwright test

3.Generate Allure report:
npx allure generate allure-results --clean -o allure-report
