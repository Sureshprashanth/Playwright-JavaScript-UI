# Playwright JavaScript UI Automation

A Playwright JavaScript UI automation framework for cross-browser end-to-end testing.  
Designed with clean structure, page objects, fixtures, and reporting.

---

## 🚀 Tech Stack

- **Playwright** – Cross-browser automation (Chromium, Firefox, WebKit)  
- **JavaScript** – Core language  
- **Node.js / npm** – Runtime & dependencies  
- **Playwright Test Runner** – For test execution

---

## 📁 Project Structure
├── data # Test data & input
├── pageobjects # Page object classes
├── pages # UI page helper modules
├── testFixtures # Shared fixture files
├── playwright-report # Playwright HTML reports
├── config.js # Environment / project config
├── playwright.config.js # Playwright test settings
├── CustomReporter.js # Custom test reporter

yaml
Copy code

---

## 🛠 Installation

1. Clone this repository  
   ```bash
   git clone https://github.com/Sureshprashanth/Playwright-JavaScript-UI.git
Navigate into the project

bash
Copy code
cd Playwright-JavaScript-UI
Install dependencies

bash
Copy code
npm install
⚙️ Configuration
Update or review settings in playwright.config.js (like testDir, retries, browsers, timeouts).

▶️ Running Tests
Run all tests

bash
Copy code
npm test
Run in headed mode

bash
Copy code
npx playwright test --headed
📊 Reporting
After test execution, HTML reports will be generated under:

Copy code
playwright-report/
Use:

bash
Copy code
npx playwright show-report
🤝 Contributing
If you’d like to contribute:


📫 Maintained By
Suresh Prashanth
GitHub: https://github.com/Sureshprashanth
