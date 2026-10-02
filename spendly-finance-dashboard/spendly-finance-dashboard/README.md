# Spendly — Personal Finance Dashboard

A colorful, responsive finance dashboard inspired by modern banking and analytics interfaces.

## Features
- Dashboard cards for balance, income, expenses, and savings.
- Add and delete income/expense transactions.
- Monthly filtering and transaction search.
- Expense-by-category doughnut chart and cash-flow chart.
- Transaction history with type and category filters.
- Savings goal with editable target and progress.
- Analytics page with savings-rate insight.
- JSON backup export and local data reset.
- Responsive sidebar and animated interface.
- LocalStorage persistence; data remains in this browser.

## Run
Open `index.html` in a browser, or use VS Code Live Server. Chart.js and Google Fonts use CDNs and need an internet connection.

## Stack
HTML5, CSS3, JavaScript, Chart.js, LocalStorage.

## Interview preparation
**How is balance calculated?** Balance is total recorded income minus total recorded expenses for the selected month.

**How do you show expense categories?** The app totals expense records by category and passes those values to a Chart.js doughnut chart.

**Why LocalStorage?** It provides simple browser-side persistence without requiring a backend. It is suitable for a demo, but not secure multi-device financial storage.

**How would you improve this for production?** Add authentication, a secure backend/database, input validation, recurring transactions, and encrypted backup/sync.
