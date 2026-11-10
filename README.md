# Safe Count Log

A small web app for filling in the store's daily **Safe Count Log**. You type in the day's counts, the app does every calculation, and it prints the finished form on one Letter landscape page.

**Open the app:** https://farzad-chatrsimab.github.io/shoppers-safe-count-log/

Nothing to install. It runs in Chrome or Edge, and you can also install it as an app (see below).

## Install it as an app

The Safe Count Log is a Progressive Web App, so it can be installed and works offline once it has been opened.

- **Chrome or Edge on a computer:** open the link and click **Install app** in the top bar (or the install icon at the right of the address bar).
- **iPhone or iPad (Safari):** tap Share → **Add to Home Screen**.
- **Android (Chrome):** tap ⋮ → **Install app**.

It then opens in its own window, with its own icon, like any other program. Saved days are shared between the installed app and the same browser.

## What it does

- **Safe counts.** Choose **TellerMate receipts** (the printout leaves a box in each safe count column to staple the receipt) or **Enter counts** (type coins and bills; each count is checked against the expected safe float).
- **Daily deposit.** Store and Post Office bag numbers, amounts, total and deposit time.
- **Lottery** (Active and In-Active Offline), **Stamps**, **Transit**, **Other** (garbage bags) and **$10 Shoppers Drug Mart coupons.** Enter the counts and the app works out the totals, assumed sales and variances.
- **Previous totals fill in automatically** from the day before, so assumed sales and variances need no extra math.
- **Preview & Print** shows the form exactly as it prints and flags any variance or missing number first.
- **History** of saved days, plus **Export / Import backup**.

## Daily use

1. Open the link. It starts on today's date.
2. Fill in the sections. Press **Enter** to jump to the next count. Click a section's header to fold it away; a folded section still shows its total or variance.
3. Enter **Actual sales** from the sales reports to get the variances.
4. Press **Preview & Print**, staple the TellerMate receipts if you use them, and sign.

## Settings

- **General:** store number, expected safe float (default $3,000.00), and whether new days start with TellerMate receipts or typed counts.
- **Items & prices:** the rows in Stamps, Other and Transit. Add, rename, reorder, price or remove them.
- **Lottery:** the ticket price points counted in both lottery sections. Add or remove prices.
- **Floats:** the till floats every new day starts with.
- **Your data:** backup, import, the demo, and starting over.

New days use these lists. A day you've already started keeps its own, unless you press **Use these items today too** (anything already counted is kept).

## Where the data is kept

Everything is saved **in the browser on the computer you use**. Nothing is sent anywhere, and this repository only holds the blank app.

- Each computer and browser keeps its own saved days.
- Clearing the browser's site data deletes them, so use **Settings → Export backup** now and then.
- To move your days to another computer, export there and **Import backup** on the new one.

## Try it

Settings → **Open the demo** loads sample numbers so you can see a filled-in day and its printout. Nothing in the demo is saved.

## Updating

The site is served by GitHub Pages from the `main` branch:

- `index.html` is the app; `manifest.webmanifest` and `sw.js` make it installable and offline-ready; `assets/` holds the logo and icons.
- Push a change and the link updates within a minute or two. The app always checks for a newer `index.html` when it's online.
- If you replace a file in `assets/`, also bump `VERSION` in `sw.js` so installed copies pick it up.

Saved days are not affected by updates.

## Credits

Designed and developed by **Farzad Chatrsimab**.
