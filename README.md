Amazon Login Automation Framework

## Tech Stacks

- Playwright
- TypeScript
- Node.js
- Git
- Github

## Framework Design

- Page Object Model (POM)
- Playwright Test Runner
- Reusable Locators
- Data-Driven Test Support

## Test Scenarios

### Functional Scenarios

- Valid Login
- Invalid Email
- Invalid Password
- Empty Email 
- Empty password

### Boundary Scenarios

- Mininum Email
- Minimum Password
- Maximum Email
- Maximum Password
- Long email input 
- Long password input
- Only spaces in email 
- Leading spaces while enter phone number
- Trailing spaces while enter phone number

### Security Scenarios

- Sql injection
- XSS attack 
- HTML injection

### Login Edge Case Scenarios

- Enter Key Press

### Session Management Scenarios

- Refresh after login
- Go back button after logout

### UI Testing Scenarios

- Password masking

## Total: 21 Test Cases 

## Run Tests

npm install

npx playwright test