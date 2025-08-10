# Playwright Rudderstack Automation

## Setup
1. Clone the repo
2. Run `npm install`
3. Set credentials in `.env` for dev, qa, prod

## Run Tests
```
npx playwright test
```

## Structure
- `pageObjects/` - Page object classes
- `tests/` - Test specs and fixtures
- `.env` - Environment credentials
- `playwright.config.js` - Playwright config
- `package.json` - Project dependencies

## Environment Management
- Use `.env` to switch credentials for different environments

## Example Test
Automates login, navigation, and event validation for Rudderstack.

