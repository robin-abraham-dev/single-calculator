# Partner Earnings Calculator (Single)

A single-card version of the Business Partner Earnings Calculator, designed for GitHub Pages hosting.

## Features
- One calculator card
- Partner Share dropdown (20%, 25%, 30%, 35%, 40%)
- Leverage and Trades sliders with matching number inputs (0–100, 1–100)
- Indian Rupee formatting and current earnings input
- 1.5s animated dots before showing result

## Calculation
1. Total Capital = Clients × Avg Capital
2. Effective Capital = Total Capital × Leverage
3. Monthly Volume = Effective Capital × Trades per month
4. Total Fees = Monthly Volume × 0.05%
5. Monthly Earnings = Total Fees × Partner Share (dropdown)

## Run locally
Just open `index.html` in a browser.

## Deploy to GitHub Pages
1. Create a repo and upload this folder contents to the repo root
2. Settings → Pages → Source: Deploy from a branch → Branch: main, Folder: /(root)
3. Visit: `https://<username>.github.io/<repo>/`
