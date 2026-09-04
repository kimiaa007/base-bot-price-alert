# base-bot-price-alert

Price alert bot for tokens on Base. Monitors prices and notifies users when thresholds are hit.

## Stack
- Solidity (optional onchain logic)
- Kotlin (bot logic)
- Base (L2)

## Structure
- `contracts/` — optional Solidity helpers
- `clients/kotlin/` — Kotlin bot code

## Notes
- Can use price oracles or DEX pools for price feeds.
- Extend with Telegram/Discord/Email notifications.

## License
MIT
