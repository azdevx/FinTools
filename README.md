# FinTools 💰

**FinTools** is an all-in-one financial toolkit designed to help you understand, manage, and plan your finances in one place.

🌐 **Live Demo:** https://azdevx.github.io/FinTools/

## ✨ Features

FinTools brings together several practical financial tools in a single web app:

### 📊 Finance Tracker

Track your personal finances and get a clear overview of your financial health.

* Record income and expenses
* Categorize spending
* Monitor your balance and net worth
* View income and expense trends
* Analyze spending by category
* Set and track savings goals
* Create simple budgets
* Export your financial data to JSON
* Import previously exported data
* Choose between USD, EUR, GBP, and JPY
* Store data locally in your browser

### 💳 Debt Planner

Plan your path toward becoming debt-free.

* Add multiple debts
* Track balance, interest rate, and minimum payment
* Calculate estimated payoff time
* Estimate total interest paid
* Compare:

  * **Avalanche** — highest interest first
  * **Snowball** — lowest balance first
* Visualize your remaining debt over time

### 🛒 E-commerce Simulator

Explore the economics of an e-commerce business and estimate profitability.

Model important variables such as:

* Selling price
* Product cost
* Shipping
* Packaging
* Advertising costs
* Conversion rate
* Delivery rate
* Return rate
* Payment gateway fees
* Other operating costs

The simulator is designed especially around **COD and dropshipping-style business models**.

### 📈 Investment Planner

Explore how savings and compound growth can affect your long-term wealth.

* Initial investment
* Monthly contributions
* Investment period
* Expected annual return
* Projected final balance
* Total contributions
* Estimated interest earned
* Growth visualization

## 🖥️ Live Application

Try FinTools here:

**https://azdevx.github.io/FinTools/**

Available tools:

| Tool                 | Description                                         |
| -------------------- | --------------------------------------------------- |
| Finance Tracker      | Manage income, expenses, budgets, and savings goals |
| Debt Planner         | Plan and visualize debt payoff                      |
| E-commerce Simulator | Estimate e-commerce profitability                   |
| Investment Planner   | Project long-term compound growth                   |

## 🛠️ Tech

The application is a browser-based React application using a modern component-based UI and interactive data visualizations.

The deployed build uses:

* React
* React Router
* Recharts
* Tailwind-style utility classes
* Radix UI components
* GitHub Pages

The current repository contains the production build in `dist/`.

## 🚀 Deployment

FinTools is deployed through **GitHub Pages**.

The repository includes a GitHub Actions workflow that automatically publishes the `dist/` directory whenever changes are pushed to the `main` branch.

Deployment flow:

```text
GitHub Repository
       ↓
     main
       ↓
GitHub Actions
       ↓
     dist/
       ↓
GitHub Pages
       ↓
https://azdevx.github.io/FinTools/
```

## 📁 Project Structure

```text
FinTools/
├── .github/
│   └── workflows/
│       └── deploy.yml
├── dist/
│   ├── index.html
│   ├── robots.txt
│   └── assets/
└── README.md
```

## 💾 Data & Privacy

FinTools is designed to keep personal financial data in the browser.

The Finance Tracker uses browser `localStorage` for transactions, savings goals, and currency preferences. It also provides JSON export/import functionality so users can create their own backups.

No account is required to use the tools.

> **Note:** Financial calculations are estimates intended for planning and educational purposes. They should not be considered professional financial advice.

## 🎯 Project Goals

FinTools aims to make everyday financial planning:

* Simple
* Accessible
* Visual
* Practical
* Easy to use

Instead of using several different calculators and spreadsheets, FinTools brings common financial planning tasks together in one place.

## 📌 Roadmap

Potential future improvements include:

* [ ] More currencies
* [ ] Advanced budgeting tools
* [ ] Recurring transactions
* [ ] More investment scenarios
* [ ] Additional debt payoff strategies
* [ ] PDF/CSV reports
* [ ] Improved mobile experience
* [ ] More e-commerce scenarios
* [ ] Financial dashboard improvements

## 🤝 Contributing

Contributions, suggestions, and bug reports are welcome.

Feel free to open an issue or submit a pull request.

## 📄 License

Add your preferred license here.

For example:

```text
MIT License
```

---

Made with ❤️ by **azdevx**

🌐 https://azdevx.github.io/FinTools/
💻 https://github.com/azdevx/FinTools
