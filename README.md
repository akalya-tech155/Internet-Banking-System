# 🏦 Internet Banking System Automation

A Playwright + TypeScript automation project that tests the core features of an Internet Banking System using the Page Object Model (POM) and Git feature branching workflow.

## 📌 Project Overview

This project automates the following banking functionalities:

- ✅ Account Creation
- ✅ Deposit Money
- ✅ Withdraw Money
- ✅ Transaction History
- ✅ Invalid Amount Validation (Negative Testing)

The project demonstrates industry-standard automation practices, including:
- Playwright Test Framework
- TypeScript
- Page Object Model (POM)
- Assertions
- Git Feature Branch Workflow

---

## 🛠️ Tech Stack

- Playwright
- TypeScript
- Node.js
- Git
- GitHub

---

## 📁 Project Structure

```
Internet-Banking-System/
│
├── pages/
│   ├── RegisterPage.ts
│   ├── DepositPage.ts
│   ├── WithdrawPage.ts
│   └── TransactionPage.ts
│
├── tests/
│   ├── createAccount.spec.ts
│   ├── deposit.spec.ts
│   ├── withdraw.spec.ts
│   ├── transactionHistory.spec.ts
│   └── invalidAmount.spec.ts
│
├── playwright.config.ts
├── package.json
├── tsconfig.json
└── README.md
```

---

## 🌿 Git Branch Strategy

```
main
├── feature/create-account
├── feature/deposit
├── feature/withdraw
├── feature/transaction-history
└── bugfix/invalid-amount
```

Each feature is developed on its own branch and merged into `main` after completion.

---

## 🚀 Features

### 1. Account Creation

- Register a new customer
- Verify successful account creation

---

### 2. Deposit

- Login
- Deposit money into an account
- Verify updated balance

---

### 3. Withdraw

- Login
- Withdraw money
- Verify updated balance

---

### 4. Transaction History

- View transaction history
- Validate:
  - Date
  - Transaction Type
  - Amount
  - Balance

---

### 5. Invalid Amount Validation

Negative test cases:

- Deposit negative amount
- Deposit zero amount
- Deposit non-numeric value
- Verify error message
- Verify balance remains unchanged

---

## ▶️ Installation

Clone the repository

```bash
git clone <repository-url>
```

Navigate to the project

```bash
cd Internet-Banking-System
```

Install dependencies

```bash
npm install
```

Install Playwright browsers

```bash
npx playwright install
```

---

## ▶️ Running Tests

Run all tests

```bash
npx playwright test
```

Run a specific test

```bash
npx playwright test tests/deposit.spec.ts
```

Run tests in headed mode

```bash
npx playwright test --headed
```

Generate HTML report

```bash
npx playwright show-report
```

---

## ✅ Test Scenarios

| Feature | Status |
|----------|--------|
| Account Creation | ✅ |
| Deposit | ✅ |
| Withdraw | ✅ |
| Transaction History | ✅ |
| Invalid Amount Validation | ✅ |

---

## 📚 Concepts Covered

- Playwright Automation
- Page Object Model (POM)
- Locators
- Assertions
- Test Organization
- Git Branching
- Git Merge
- Negative Testing
- Balance Validation

---

## 👨‍💻 Author

**AKALYA**

GitHub: https://github.com/your-github-username

---

## ⭐ Future Enhancements

- Login Automation
- Fund Transfer
- Account Summary
- Multiple Account Support
- Data-Driven Testing
- Cross-Browser Testing
- CI/CD Integration with GitHub Actions