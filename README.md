# tastytrade

tastytrade is an options-focused brokerage that provides a public Open API
for programmatic access to accounts, trading, market data, and streaming. The
API is used by individual traders, algorithm developers, and third-party
platform integrators to build automated trading systems, portfolio dashboards,
and risk management tools on top of the tastytrade infrastructure.

## APIs Covered

| API | Type | Base URL |
|-----|------|----------|
| tastytrade REST API | REST / JSON | https://api.tastyworks.com |
| DXLink Market Data Streaming | WebSocket | wss://tasty-openapi-ws.dxfeed.com |
| Account Streamer | WebSocket | wss://streamer.tastyworks.com |

## Key Capabilities

- Account balances, buying power, and margin requirements
- Positions and open orders
- Transaction history
- Real-time quotes, option chains, and market metrics
- Submit, modify, and cancel orders (equity, crypto, options, futures)
- Multi-leg option strategy construction
- Watchlist create and sync
- Order chains for tracking rolled options
- Real-time account update streaming

## Authentication

The API supports two authentication patterns:

1. **Session tokens** — POST `/sessions` with username and password. Tokens expire after 15 minutes. Include in the `Authorization` header on each request.
2. **OAuth 2.0** — For partner and third-party integrations requiring long-lived access. See the [OAuth guide](https://developer.tastytrade.com/oauth/).

All requests must include a `User-Agent` header in `<product>/<version>` format, or they will receive a 401 error.

## Environments

| Environment | REST Base URL | Account Streamer |
|------------|---------------|------------------|
| Production | https://api.tastyworks.com | wss://streamer.tastyworks.com |
| Sandbox | https://api.cert.tastyworks.com | wss://streamer.cert.tastyworks.com |

The sandbox resets every 24 hours (trades, positions, and balances are cleared; accounts persist). Sandbox quotes are 15-minute delayed.

## Resources

- Developer Portal: https://developer.tastytrade.com/
- API Overview: https://developer.tastytrade.com/api-overview/
- OAuth Guide: https://developer.tastytrade.com/oauth/
- Sandbox: https://developer.tastytrade.com/sandbox/
- FAQ: https://developer.tastytrade.com/faq/
- Release Notes: https://developer.tastytrade.com/release-notes/
- JavaScript SDK: https://github.com/tastytrade/tastytrade-api-js
- Postman Collection: https://www.postman.com/tastytradeapi/tastytrade-api/
- Terms of Service: https://assets.tastyworks.com/production/documents/USA/open_api_terms_and_conditions.pdf
- API Support: api.support@tastytrade.com

## Plans and Pricing

API access is included with a tastytrade brokerage account at no additional
charge. Trade commissions follow tastytrade's standard schedule (e.g., $1.00
per equity options contract to open, commission-free equity trades). See
`plans/plans.yml`, `rate-limits/rate-limits.yml`, and `finops/finops.yml`
for details.
