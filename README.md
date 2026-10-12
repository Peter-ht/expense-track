# Expense Tracker with Live Currency Conversion

Expense Tracker is a client-side web app for people who travel, freelance internationally, or shop from foreign stores. It allows users to record expenses in the currency they paid with and immediately view converted values and total spending in a selected home currency.

## Live demo

After enabling GitHub Pages, add the published URL here:

https://Peter-ht.github.io/expense-tracker/

## Features

| Feature | Description |
|---|---|
| Add expenses | Save a description, amount, currency, and category |
| Live conversion | Convert expenses using current exchange rates |
| Home currency | Change the currency used for totals |
| Running total | Automatically calculate total spending |
| Delete expenses | Remove individual expense records |
| Category filtering | Filter by Food, Transport, Shopping, Accommodation, or Other |
| Error handling | Display a useful message when the API is unavailable |
| Responsive design | Works on desktop and mobile screens |

## Technology

| Technology | Usage |
|---|---|
| HTML | Semantic application structure |
| CSS | Responsive layout and visual styling |
| JavaScript ES modules | Separate API, state, UI, utility, and entry-point logic |
| ExchangeRate API | https://open.er-api.com/v6/latest/USD |
| Jest | Unit testing pure utility functions |
| ESLint | Static analysis |
| GitHub Pages | Static deployment |

## Run locally

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/expense-tracker.git
cd expense-tracker
