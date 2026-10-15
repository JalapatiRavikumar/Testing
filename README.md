# Testing

Automated QA Testing repository containing end-to-end API and UI automation suites.

## Projects

### 🏨 [restful-booker-qa](./restful-booker-qa)
Comprehensive QA automation suite covering both API and UI layers for the Restful-Booker booking platform:
- **API Automation**: Postman collection executed with Newman & Newman HTML reporter (covers auth, CRUD operations, error handling, status code validations).
- **UI Automation**: Playwright (JavaScript) covering room searches, booking workflows, form validations, and contact forms across Chromium and Firefox.
- **CI/CD**: GitHub Actions workflow.

### Quick Start

Run test suites from the root directory:

```bash
# Run API tests (Postman / Newman)
npm run test:api

# Run UI tests (Playwright)
npm run test:ui

# Run UI tests in headed browser mode
npm run test:ui:headed

# Run both suites
npm test
```
