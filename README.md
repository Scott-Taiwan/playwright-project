# Playwright Test Project

This repository contains automated tests using Playwright for end-to-end testing of web applications.

## Setup

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Install Playwright browsers:
   ```bash
   npx playwright install
   ```

## Running Tests

Run all tests:
```bash
npx playwright test
```

Run a specific test file:
```bash
npx playwright test test_UI.ts
```

Run tests in a specific browser:
```bash
npx playwright test --project=chromium
```

Run tests in UI mode:
```bash
npx playwright test --ui
```

## Test Reports

After running tests, you can view the HTML report:
```bash
npx playwright show-report
```

## Project Structure

- `playwright.config.ts`: Configuration file for Playwright
- `test_UI.ts` and `test_UI1.spec.ts`: Test files containing test cases
- `.github/workflows/playwright.yml`: GitHub Actions workflow for running tests on CI
