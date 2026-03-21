1. Install Dependencies

npm install

2. Install Playwright Browsers

npx playwright install

3. Run All Tests (Headless Mode - Default)

npx playwright test

4. Run Tests in Headed Mode (Visible Browser)

npx playwright test --headed

5. Run Tests in UI Mode (Interactive Dashboard)

npx playwright test --ui

6. Run Tests in Specific Browser

npx playwright test --project=chromium
npx playwright test --project=firefox
npx playwright test --project=webkit

7. Run Specific Test File

npx playwright test tests/todo.spec.js

8. Run Specific Tests Using Grep

npx playwright test --grep "todo"

9. Run Tests Sequentially (Single Worker)

npx playwright test --workers=1

10. Run Only Failed Tests

npx playwright test --last-failed

11. Show Test Report

npx playwright show-report

12. Debug Mode

npx playwright test --debug
