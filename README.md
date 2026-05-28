# POLYTRACK · Multi-Account Intelligence

> Real-time Polymarket multi-account position tracker with consensus analysis and live trade feed.

## Features

- **Track up to 20 wallets** simultaneously via Polymarket Data API
- **Common positions** — find markets where multiple accounts agree
- **Trade activity feed** — chronological log of all trades across accounts
- **Account detail** — per-wallet portfolio breakdown with P&L
- **Auto-refresh** — poll every 30s / 1min / 5min / 10min
- **Overlap filter** — set minimum account threshold for consensus view

## Live Demo

🔗 [Open on GitHub Pages](https://YOUR_USERNAME.github.io/polytrack)

## Usage

1. Add up to 20 Polygon wallet addresses (0x…)
2. Click **SCAN ALL ACCOUNTS**
3. Switch tabs: Common Positions / All Positions / Trade Activity / Account Detail
4. Enable auto-refresh for live tracking

## API

Uses [Polymarket Data API](https://data-api.polymarket.com):
- `GET /positions?user={address}` — open positions
- `GET /activity?user={address}` — trade history

No API key required. CORS-enabled public endpoints.

## Deploy

```bash
git clone https://github.com/YOUR_USERNAME/polytrack
cd polytrack
# open index.html in browser — or push to GitHub Pages
```

## Tech

Pure HTML/CSS/JS — zero dependencies, zero build step. Deploy anywhere.
# POLYTRACK
