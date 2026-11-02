# Safe Count Log

A small web app for filling in the store's daily **Safe Count Log**. You type in the day's counts, the app does every calculation, and it prints the finished form on one Letter landscape page.

**Open the app:** https://farzad-chatrsimab.github.io/shoppers-safe-count-log/

Nothing to install. It runs in Chrome or Edge, and the whole app is a single file (`index.html`).

## What it does

- **Safe counts.** Choose **TellerMate receipts** (the printout leaves a box in each safe count column to staple the receipt) or **Enter counts** (type coins and bills; each count is checked against the expected safe float).
- **Daily deposit.** Store and Post Office bag numbers, amounts, total and deposit time.
- **Lottery** (Active and In-Active Offline), **Stamps**, **Transit**, **Other** (garbage bags) and **$10 Shoppers Drug Mart coupons.** Enter the counts and the app works out the totals, assumed sales and variances.
- **Previous totals fill in automatically** from the day before, so assumed sales and variances need no extra math.
- **Preview & Print** shows the form exactly as it prints and flags any variance or missing number first.
- **History** of saved days, plus **Export / Import backup**.

## Daily use

1. Open the link. It starts on today's date.
2. Fill in the sections. Press **Enter** to jump to the next count.
3. Enter **Actual sales** from the sales reports to get the variances.
4. Press **Preview & Print**, staple the TellerMate receipts if you use them, and sign.

## Settings

- **Store number:** shown in the header and on the printout.
- **Expected safe float:** used to check typed-in safe counts (default $3,000.00).
- **Default prices & floats:** stamp, garbage bag and transit prices and the till floats that every new day starts with. A day you've already started keeps its own amounts; change those with **Edit prices** on that day.

## Where the data is kept

Everything is saved **in the browser on the computer you use**. Nothing is sent anywhere, and this repository only holds the blank app.

- Each computer and browser keeps its own saved days.
- Clearing the browser's site data deletes them, so use **Settings → Export backup** now and then.
- To move your days to another computer, export there and **Import backup** on the new one.

## Try it

Settings → **Open the demo** loads sample numbers so you can see a filled-in day and its printout. Nothing in the demo is saved.

## Updating

The site is served by GitHub Pages from `index.html` on the `main` branch. Replace that file and push, and the link updates within a minute or two. Saved days are not affected.
