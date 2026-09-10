# Chequebook With Prophecy — v1

A tiny local-first PWA for one chequing account.

## v1 features
- Chronological ledger: Date | Money out | Item | Money in | Balance
- Running balance recalculated on every line
- One-time and recurring transactions
- Weekly, biweekly, monthly-on-date, and last-day-of-month recurrence
- Banking-day adjustment:
  - income on a weekend/Payments Canada closure moves to previous business day
  - debit on a weekend/Payments Canada closure moves to next business day
- 2026 Payments Canada closure dates included
- Local-only browser storage
- JSON export/import backup
- Installable as a PWA once hosted over HTTPS

## Important v1 limitation
The built-in Payments Canada closure table covers 2026 only. Add future-year closures before relying on 2027+ forecasts.

## Install on Samsung/Chrome
1. Host this folder on any HTTPS static host (GitHub Pages is one free option).
2. Open the hosted site in Chrome on the phone.
3. Chrome menu → Add to Home screen / Install app.
4. Set the starting date and chequing balance.
5. Add planned and real-time transactions.

## Privacy
No bank connection, account login, analytics, or remote database. Data stays in browser storage on the device. Export a backup periodically.

## Banking-calendar source
Payments Canada System Closure Schedule:
https://www.payments.ca/system-closure-schedule
