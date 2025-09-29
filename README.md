# 🎭 Playwright-Automation

This repository contains everything you need to **start practicing Playwright** automation testing.
It covers **fundamental to advanced concepts** with practical examples and real scenarios.

We’ll be using the demo practice site:
👉 [https://qa-practice.netlify.app/](https://qa-practice.netlify.app/)

---

## 📚 Topics Covered

- ✅ Playwright Basics (installation, test runner setup)
- ✅ Page Object Model (POM)
- ✅ Working with Selectors (text, CSS, XPath, role-based, etc.)
- ✅ Handling Test Flakiness & Best Practices
- ✅ Fixtures & Utils for scalable test architecture
- ✅ API Testing with Playwright
- ✅ Running tests in **headed / headless** modes
- ✅ Parallel Execution & Test Configurations
- ✅ CI/CD with **GitHub Actions**
- ✅ Reporting & Trace Viewer

---

## 🗂️ Folder Structure (Recommended)

```

Playwright-Automation/
│── tests/ # Test specs
│ └── example.spec.ts
│
│── pages/ # Page Object Model classes
│ └── LoginPage.ts
│ └── DashboardPage.ts
│
│── fixtures/ # Test fixtures (e.g., logged-in state)
│ └── authFixture.ts
│
│── utils/ # Helper functions (e.g., API calls, random data)
│ └── apiHelper.ts
│
│── playwright.config.ts # Playwright test configuration
│── package.json
│── README.md

```

---

## ⚡ Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/your-username/Playwright-Automation.git
cd Playwright-Automation
```

### 2. Install dependencies

```bash
npm install
```

### 3. Install browsers

```bash
npx playwright install
```

### 4. Run tests

```bash
npx playwright test
```

### 5. Open Playwright Test Report

```bash
npx playwright show-report
```

---

## 🚀 CI/CD with GitHub Actions

This repo also includes a GitHub Actions workflow to run tests in CI.
The pipeline will:

- Install dependencies
- Run Playwright tests
- Upload test results & reports

---

## 🌐 Demo Website

All examples use 👉 [qa-practice.netlify.app](https://qa-practice.netlify.app/)

---

## 🤝 Contribution

Feel free to fork this repo, create branches, and raise pull requests to improve examples and add more scenarios.

---

## 📌 Author

Maintained by **Daniyal Farman** ✨
