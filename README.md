# RustChain Network Dashboard

Live monitoring dashboard for the [RustChain](https://github.com/Scottcjn/Rustchain) DePIN blockchain.

**Live:** https://cuentaprueba244w-dotcom.github.io/rustchain-dashboard/

## Features

- **Network Health**: Real-time node status with live API health checks
- **Epoch Monitor**: Current epoch, reward pool, visual progress bar
- **Miner Leaderboard**: All active miners with hardware, multipliers, attestations
- **Payout Tracker**: Total RTC paid, unique recipients, transaction count
- **Wallet Lookup**: Search any miner_id for balance, hardware, and multiplier
- **Node Inspector**: Raw JSON view of health, epoch, and miner data
- **Auto-refresh**: Updates every 60 seconds
- **Responsive**: Works on desktop and mobile
- **Zero Dependencies**: Single HTML file, no frameworks, no build step
- **Offline-Ready**: Works after first load, gracefully handles node downtime

## Technology

- Vanilla HTML/CSS/JavaScript
- RustChain Node API (50.28.86.131)
- GitHub Pages hosting
- Dark theme with monospace typography

## API Endpoints Used

| Endpoint | Usage |
|----------|-------|
| /health | Node health status |
| /epoch | Current epoch and reward pool |
| /api/miners | Active miner list |
| /payouts.json | Global payout statistics |
| /wallet/balance | Individual wallet lookup |

## Bounty

Built for the RustChain Micro-Grants program (bounty #402, rustchain-bounties).

RTC wallet: cuentaprueba244w-dotcom

## License

MIT
