# Portfolio Update Guide

This portfolio is already structured for GitHub Pages and uses your ASM logo.

## 1. Main files

```text
index.html              Homepage
style.css               Full professional design
script.js               Mobile menu and project filters
assets/logos/asm-logo.jpg
assets/cv.pdf
projects/               All project and sector pages
```

## 2. What to update first

### Update GitHub username links

Search for:

```text
https://github.com/asm-sol/
```

Replace with your exact repo links if different.

### Update live demo links

Search for:

```text
https://asm-sol.github.io/
```

Replace with the real GitHub Pages demo link for each project.

### Update CV

Replace this file whenever your CV changes:

```text
assets/cv.pdf
```

Keep the same filename so the Download CV button keeps working.

## 3. How to update each project

Each project has its own folder:

```text
projects/blockchain/nft-mmo/
projects/blockchain/solana-ticketing/
projects/trading/polymarket-hub/
projects/trading/wallet-analyzer/
projects/trading/gold-ml-bot/
projects/ai-ml/football-prediction/
projects/data-analytics/sales-dashboard/
projects/backend/api-systems/
```

Inside each folder:

```text
index.html      The actual case study page
README.md       Notes for the repo/project
screenshots/    Add screenshots here
images/         Add diagrams/architecture images here
```

## 4. Project-by-project checklist

### NFT MMO Blockchain Ecosystem

Update:
- GitHub repo link
- Unity screenshots
- Creature/NFT screenshots
- Rarity table
- Breeding flow diagram
- Solana minting architecture diagram

Best screenshots:
- World map
- Character sprite
- Battle UI
- Creature collection
- Minting or marketplace flow

### Solana Blockchain Ticketing Platform

Update:
- Solana bounty repo link
- Anchor instruction list
- Account model diagram
- Ticket purchase flow
- Ticket verification flow
- Test results screenshot

Best screenshots:
- Event creation UI
- Ticket minting transaction
- Wallet ticket ownership
- Resale/transfer example
- Validator/check-in screen

### Polymarket Automated Trading Hub

Update:
- Repo link
- API route screenshot
- Trading dashboard screenshot
- Backtest or performance chart
- Risk management explanation

Best screenshots:
- Dashboard
- Terminal bot logs
- Market analysis output
- Risk settings
- Database schema

### Crypto Wallet Analyzer & Copy Trading Bot

Update:
- Repo link
- Wallet leaderboard screenshot
- Wallet detail page
- PnL chart
- Copy trade settings
- Risk control examples

Best screenshots:
- Top wallets table
- Wallet PnL graph
- Trade history
- Copy-trading config
- Risk warnings

### Gold Commodity ML Trading Bot

Update:
- Repo link
- Model metrics
- Walk-forward validation chart
- Equity curve
- Feature importance
- Backtest assumptions

Best screenshots:
- Model performance table
- Equity curve
- Drawdown chart
- Signal output
- Training logs

### Football Match Prediction System

Update:
- Repo link
- Prediction dashboard
- Backtest table
- Calibration plot
- Discord alert screenshot
- Example match prediction

Best screenshots:
- Upcoming match predictions
- Probability output
- Value bet alert
- Backtest results
- Discord bot message

### Sales Performance Dashboard

Update:
- Repo link
- Power BI screenshots
- SQL cleaning scripts
- KPI formulas
- Dashboard insights

Best screenshots:
- Revenue dashboard
- Monthly growth chart
- Customer analysis
- Product/category performance
- SQL query examples

### Backend API Systems

Update:
- Repo link
- API docs screenshot
- Swagger/OpenAPI screenshot
- Database schema
- Deployment notes
- Example endpoints

Best screenshots:
- FastAPI docs
- Endpoint response
- Database tables
- Logs
- Deployment page

## 5. How to add screenshots to a project page

Example for the ticketing project:

1. Put image here:

```text
projects/blockchain/solana-ticketing/screenshots/ticket-demo.png
```

2. Open:

```text
projects/blockchain/solana-ticketing/index.html
```

3. Add this where you want the image:

```html
<img src="screenshots/ticket-demo.png" alt="Ticketing demo screenshot" style="width:100%;border-radius:22px;margin-top:20px;">
```

## 6. How to create a new project page

1. Copy an existing project folder.
2. Rename the folder.
3. Edit `index.html`.
4. Add the project card to the homepage in `index.html`.
5. Add the project to the correct sector page.

## 7. GitHub Pages upload steps

```bash
git init
git add .
git commit -m "Add professional ASM portfolio"
git branch -M main
git remote add origin https://github.com/YOURUSERNAME/YOURUSERNAME.github.io.git
git push -u origin main
```

Then:

```text
GitHub repo → Settings → Pages → Deploy from branch → main → /root → Save
```

Your site will be live at:

```text
https://YOURUSERNAME.github.io
```
