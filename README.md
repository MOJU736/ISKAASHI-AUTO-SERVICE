# Iskaashi Auto Service

Single-file SIM / data-package business manager. Open `index.html` in a browser — no server or install needed.

- **SIM Inventory** – add SIMs (MSISDN, dealer, ICCID), stock → assigned, assign to customer
- **Customers** – history, SIMs, active subscriptions, balance
- **Packages** – price, cost, automatic profit/margin
- **Subscriptions** – SIM + customer + package, start/next payment date, paid/unpaid, data used/remaining, automatic monthly renewal billing
- **Payments** – Cash / Mobile Money / Bank, reference, history, outstanding balance
- **Dashboard** – stock, assigned, active customers, revenue, cost, profit, unpaid customers, upcoming renewals
- **Reports** – by package, customers, payments (date range), SIM inventory, monthly performance (CSV export on each)
- **Data protection** – data stays in this browser (localStorage); JSON backup/restore, CSV exports, audit log

Data lives only in the browser you use — download a JSON backup regularly (the app reminds you after 7 days).
