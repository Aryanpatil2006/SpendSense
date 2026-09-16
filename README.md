# 💰 SpendWise — Smart Student Expense Tracker with Visual Logs

## 1. Project Overview

**SpendWise** is a smart web-based expense tracking application designed especially for students. It helps users record, organize, analyze, and understand their daily spending habits through an interactive and visual dashboard.

Students can enter expenses such as food, transportation, academic supplies, entertainment, shopping, health, and bills. The application automatically categorizes expenses, provides spending analytics, tracks budgets, identifies unusual spending patterns, and generates useful reports.

The main goal of SpendWise is to transform simple expense logging into an easy-to-understand visual financial management experience.

### 🎯 Tagline

> **Track. Understand. Improve Your Spending.**

---

## 2. Features

### 📝 Smart Expense Logger

* Add daily expenses quickly.
* Enter amount, date, description, category, payment method, and notes.
* Supports student-focused expense categories.
* Automatically saves expense records in the browser.

### 🧠 Smart Expense Categorization

SpendWise recognizes common keywords related to expenses and organizes them into categories such as:

* 🍔 Food & Dining
* 🚌 Transportation
* 📚 Academic & Study
* 🍿 Entertainment
* 🛍️ Shopping
* 💊 Health & Wellness
* ⚡ Bills & Utilities
* 📦 Other / Miscellaneous

### 📊 Interactive Dashboard

The dashboard provides an overview of:

* Total spending
* Today's spending
* Current month's spending
* Previous month's spending
* Number of transactions
* Daily average spending
* Highest spending category
* Month-over-month spending changes

### 📈 Visual Analytics

* Category-wise spending analysis
* Spending distribution
* Budget progress
* Monthly spending insights
* Interactive visual representations of expenses

### 🗓️ Expense Timeline

* View expenses chronologically.
* Edit existing transactions.
* Delete unwanted transactions.
* Quickly add new expenses.

### 🔥 Expense Heatmap

The application provides a visual representation of spending activity across different days, helping users identify spending patterns.

### 💰 Budget Management

* Set monthly budgets for different categories.
* Track spending against category limits.
* Monitor remaining budget.
* Identify categories approaching their limits.

### 🚨 Spending Anomaly Detection

SpendWise includes an anomaly detection service that can identify unusual spending patterns and help users notice unexpected expenses.

### 📋 Reports & CSV Support

* Export expense records to CSV.
* Import expense records from CSV.
* Validate imported data.
* Display errors for invalid CSV records.

### 💾 Local Data Storage

Expense and budget information is stored using the browser's **LocalStorage**, allowing the application to retain data between sessions.

### 🔄 Demo Data

The project includes sample student expense data so that the application can be demonstrated immediately after installation.

### 🧹 Data Management

Users can:

* Reset data to the default demo dataset.
* Clear recorded expenses.
* Import external expense records.

---

## 3. Technologies and Tools Used

### Frontend

* **React 19**
* **TypeScript**
* **Vite**
* **Tailwind CSS**
* **Lucide React**
* **Motion**

### Development Tools

* **Node.js**
* **npm**
* **TypeScript**
* **Git & GitHub**
* **Visual Studio Code**

### Data & Application Services

* Browser **LocalStorage** for persistent expense and budget data
* Custom TypeScript analytics engine
* Custom expense parser
* Custom anomaly detection service
* CSV import/export functionality

### Project Architecture

```text
SpendWise
│
├── React UI
│   ├── Dashboard
│   ├── Smart Logger
│   ├── Expense Timeline
│   ├── Heatmap
│   ├── Budget Manager
│   ├── Analytics
│   └── Reports
│
├── Services
│   ├── Expense Parser
│   ├── Analytics Engine
│   ├── Anomaly Detector
│   └── Local Storage
│
├── Data
│   ├── Categories
│   └── Sample Expenses
│
└── TypeScript Models
```

---

## 4. Installation and Running the Project

### Prerequisites

Make sure the following are installed:

* **Node.js** — Version 18 or higher recommended
* **npm**
* **Git** (if cloning from GitHub)

Check your installation:

```bash
node --version
npm --version
```

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Move into the project directory:

```bash
cd spendwise
```

### Step 2: Install Dependencies

Run:

```bash
npm install
```

This installs all required project dependencies.

### Step 3: Start the Development Server

Run:

```bash
npm run dev
```

The application will start using Vite.

Open the URL displayed in the terminal, normally:

```text
http://localhost:3000
```

### Step 4: Build the Project

To create a production build:

```bash
npm run build
```

### Step 5: Preview the Production Build

```bash
npm run preview
```

---

## 5. Testing Instructions

After starting the application, perform the following tests.

### Test 1 — Dashboard

1. Open the application.
2. Go to the **Dashboard**.
3. Verify that sample expense data is displayed.
4. Check total spending, transaction count, category information, and other statistics.

### Test 2 — Add Expense

1. Open **Smart Logger**.
2. Enter an expense amount.
3. Enter a description such as:

```text
Lunch at canteen
```

4. Select the appropriate category/payment method.
5. Save the expense.
6. Verify that the new transaction appears in the expense records.

### Test 3 — Edit Expense

1. Open **Expense Logs**.
2. Select an existing expense.
3. Click the edit option.
4. Change the amount or description.
5. Save the changes.
6. Verify that the updated information is displayed.

### Test 4 — Delete Expense

1. Open the expense timeline.
2. Select an expense.
3. Delete it.
4. Confirm that the transaction has been removed.

### Test 5 — Budget Management

1. Open **Budgets**.
2. Set a monthly budget for a category.
3. Add expenses belonging to that category.
4. Verify that the budget progress changes accordingly.

### Test 6 — Analytics

1. Open **Analytics**.
2. Check category-wise spending.
3. Verify that the displayed analytics change after adding or deleting expenses.

### Test 7 — Expense Heatmap

1. Open **Heatmap**.
2. Verify that spending activity is represented according to recorded expense dates.
3. Add additional expenses and check whether the visualization updates.

### Test 8 — CSV Export

1. Open **Reports**.
2. Export the expense data.
3. Verify that a CSV file is generated.
4. Open the CSV file and confirm that expense details are present.

### Test 9 — CSV Import

1. Prepare a CSV containing expense records.
2. Import the CSV through the Reports section.
3. Verify that valid records are added.
4. Confirm that invalid records generate appropriate validation errors.

### Test 10 — Data Persistence

1. Add a new expense.
2. Refresh the browser.
3. Verify that the expense is still available.

This confirms that browser LocalStorage is working correctly.

### Test 11 — Reset Demo Data

1. Use the **Reset Data** option.
2. Confirm the reset operation.
3. Verify that the original sample student dataset is restored.

---

## 6. Screenshots

Screenshots are recommended for the project submission.

Add screenshots of the following application screens to this README:

### Dashboard

```text
![SpendWise Dashboard](screenshots/dashboard.png)
```

### Smart Expense Logger

```text
![Smart Expense Logger](screenshots/smart-logger.png)
```

### Expense Timeline

```text
![Expense Timeline](screenshots/expense-timeline.png)
```

### Analytics

```text
![Visual Analytics](screenshots/analytics.png)
```

### Budget Management

```text
![Budget Management](screenshots/budgets.png)
```

### Expense Heatmap

```text
![Expense Heatmap](screenshots/heatmap.png)
```

### Reports

```text
![Reports](screenshots/reports.png)
```

> **Note:** Create a `screenshots` folder in the project root and place the corresponding images inside it before submitting the final GitHub repository.

---

## 7. Project Structure

```text
spendwise/
│
├── src/
│   ├── components/
│   │   ├── Navbar.tsx
│   │   ├── Dashboard.tsx
│   │   ├── SmartLogger.tsx
│   │   ├── ExpenseTimeline.tsx
│   │   ├── ExpenseHeatmap.tsx
│   │   ├── BudgetManager.tsx
│   │   ├── VisualAnalytics.tsx
│   │   ├── ReportsView.tsx
│   │   └── EditExpenseModal.tsx
│   │
│   ├── services/
│   │   ├── expenseParser.ts
│   │   ├── analyticsEngine.ts
│   │   ├── anomalyDetector.ts
│   │   └── storage.ts
│   │
│   ├── data/
│   │   ├── categories.ts
│   │   └── sampleData.ts
│   │
│   ├── App.tsx
│   ├── main.tsx
│   ├── index.css
│   └── types.ts
│
├── index.html
├── package.json
├── tsconfig.json
├── vite.config.ts
├── .env.example
├── .gitignore
└── README.md
```

---

## 8. Important Notes

* SpendWise currently stores expense and budget information in the browser's LocalStorage.
* The application includes demo student data for easy testing and presentation.
* CSV import/export can be used for transferring expense records.
* Do not commit private API keys or other secrets to GitHub.
* If environment variables are required in a future version, configure them using a local `.env` file.

---

## 9. Future Enhancements

Possible future improvements include:

* User authentication and individual accounts
* Cloud database synchronization
* Mobile application
* AI-powered personalized spending insights
* Receipt image scanning using OCR
* Voice-based expense entry
* Automatic bank/UPI transaction integration
* Advanced monthly financial reports
* Notification-based budget alerts
* More advanced machine-learning-based spending prediction

---

## 10. Conclusion

SpendWise provides students with a simple and interactive way to record and understand their everyday expenses. Instead of displaying only a list of transactions, the application combines expense logging, categorization, budgets, analytics, visual logs, anomaly detection, and reporting in one platform.

The project demonstrates the practical use of modern frontend technologies and data-processing techniques to solve a common student problem: **understanding where their money goes and managing it more effectively.**

---

## 👨‍💻 Project Information

**Project Name:** SpendWise
**Project Type:** Student Expense Management Web Application
**Primary Users:** Students
**Frontend:** React + TypeScript
**Build Tool:** Vite
**Styling:** Tailwind CSS
**Data Storage:** Browser LocalStorage

> **Track. Understand. Improve Your Spending.**
