# Pennywise --- Expense Tracker

Pennywise is a responsive, browser-based personal expense tracker built
with HTML, CSS, and vanilla JavaScript. It provides a dashboard for
monitoring income, expenses, budgets, and spending insights.

## Features

-   **Dashboard:** View total balance, income, expenses, and savings
    rate for the selected month.
-   **Cash-flow chart:** Compare income and expenses across six date
    ranges in the selected month.
-   **Monthly budgets:** Track spending against sample limits for Food,
    Transport, Shopping, and Bills.
-   **Transaction management:** Add income or expense transactions with
    a name, amount, category, and date. Delete transactions when needed.
-   **Transaction search:** Search by transaction name, category, type,
    or amount.
-   **Transaction filters:** Filter by income/expense, category, and
    date range.
-   **Sorting:** Sort transactions by newest, oldest, amount, or name.
-   **Insights:** Review income, expenses, net savings, savings rate,
    average daily spending, transaction counts, category spending, and
    the largest expense.
-   **Responsive design:** Includes desktop navigation and a collapsible
    mobile sidebar.
-   **Local persistence:** Saves transaction data in the browser using
    `localStorage`.

## How to Use

### Add a transaction

1.  Click **Add transaction**.
2.  Enter a transaction name and amount.
3.  Choose **Income** or **Expense**.
4.  Select a category and date.
5.  Click **Save transaction**.

### Search and filter transactions

1.  Open **Transactions** from the sidebar.
2.  Enter text in the search field or choose a type, category, and date
    range.
3.  Select a sort order.
4.  Click **Clear filters** to reset the search controls.
5.  Use the × control in a transaction row to delete it.

The month selector in the top bar determines which month's transactions
are displayed and analyzed. Date filters further narrow the transactions
within that selected month.

### View insights

Open **Insights** to see a summary of the selected month, including
income, expenses, net savings, savings rate, average daily spending,
category breakdown, and largest expense.

### View budgets

Open **Budgets** or click **View all** in the dashboard's Monthly
budgets card to review spending against the sample category limits.

## Project Structure

``` text
pennywise/
└── index.html    # Application markup, styles, and JavaScript
```

The current implementation is a single-file application: HTML, CSS, and
JavaScript are contained in `index.html`.

