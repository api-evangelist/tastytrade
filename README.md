# tastytrade

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

tastytrade is an options-focused brokerage offering a public Open API that provides full read and write access to real-time account data, positions, balances, transaction history, market data, option chains, and order execution across equities, options, futures, and crypto. The API uses REST over HTTPS with JSON payloads for synchronous operations and WebSocket connections (DXLink for market data, dedicated account streamer for real-time account updates). OAuth 2.0 and session-token authentication are both supported, with a safe sandbox environment for development and testing.

**Areas:** Finance · Brokerage · Trading · Options · Futures · Stocks · Cryptocurrency · Market Data · WebSocket · Investing · Financial Services

## tastytrade on APIs.io

Everything profiled for tastytrade is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/tastytrade/](https://apis.io/providers/tastytrade/)** — or go straight to one of the APIs or properties below.

### APIs (29)

- [tastytrade DXLink Market Data Streaming API](https://apis.io/apis/tastytrade/tastytrade-dxlink-market-data-streaming-api/) — Real-time market data streaming via DXLink, a WebSocket-based protocol backed by dxFeed. Clients fetch a quote token from the tastytrade REST API and use it…
- [tastytrade Account Streamer API](https://apis.io/apis/tastytrade/tastytrade-account-streamer-api/) — WebSocket-based account streaming that delivers real-time notifications for order fills, position changes, account balance updates, and margin requirement…
- [tastytrade Accounts API](https://apis.io/apis/tastytrade/tastytrade-accounts-api/) — Operations about accounts
- [tastytrade API Quote Tokens API](https://apis.io/apis/tastytrade/tastytrade-api-quote-tokens-api/) — Operations about api-quote-tokens
- [tastytrade Available Dates API](https://apis.io/apis/tastytrade/tastytrade-available-dates-api/) — The Available Dates API from tastytrade — 1 operation(s) for available dates.
- [tastytrade Backtests API](https://apis.io/apis/tastytrade/tastytrade-backtests-api/) — The Backtests API from tastytrade — 4 operation(s) for backtests.
- [tastytrade Balance Snapshots API](https://apis.io/apis/tastytrade/tastytrade-balance-snapshots-api/) — Operations about balance-snapshots
- [tastytrade Complex Orders API](https://apis.io/apis/tastytrade/tastytrade-complex-orders-api/) — Allows an API client to retreive information about complex orders on a per account basis.
- [tastytrade Customers API](https://apis.io/apis/tastytrade/tastytrade-customers-api/) — Operations about customers
- [tastytrade Futures Option Chains API](https://apis.io/apis/tastytrade/tastytrade-futures-option-chains-api/) — Operations about futures-option-chains
- [tastytrade Instruments API](https://apis.io/apis/tastytrade/tastytrade-instruments-api/) — Operations about instruments
- [tastytrade Margin Requirements API](https://apis.io/apis/tastytrade/tastytrade-margin-requirements-api/) — allows a client to fetch margin-requirements for positions and orders
- [tastytrade Margin Requirements Public Configuration API](https://apis.io/apis/tastytrade/tastytrade-margin-requirements-public-configuration-api/) — Operations about margin-requirements-public-configurations
- [tastytrade Market Data Controller API](https://apis.io/apis/tastytrade/tastytrade-market-data-controller-api/) — The market-data-controller API from tastytrade — 1 operation(s) for market-data-controller.
- [tastytrade Market Metrics API](https://apis.io/apis/tastytrade/tastytrade-market-metrics-api/) — The Market Metrics API from tastytrade — 3 operation(s) for market metrics.
- [tastytrade Market Time API](https://apis.io/apis/tastytrade/tastytrade-market-time-api/) — Operations about market-times
- [tastytrade Net Liq Controller API](https://apis.io/apis/tastytrade/tastytrade-net-liq-controller-api/) — The net-liq-controller API from tastytrade — 1 operation(s) for net-liq-controller.
- [tastytrade Option Chains API](https://apis.io/apis/tastytrade/tastytrade-option-chains-api/) — Operations about option-chains
- [tastytrade Orders API](https://apis.io/apis/tastytrade/tastytrade-orders-api/) — Allows an API client to view, filter, create, cancel and replace orders.
- [tastytrade Pairs Watchlists API](https://apis.io/apis/tastytrade/tastytrade-pairs-watchlists-api/) — Allows an API client to fetch pairs watchlists.
- [tastytrade Positions API](https://apis.io/apis/tastytrade/tastytrade-positions-api/) — Operations about positions
- [tastytrade Public Watchlists API](https://apis.io/apis/tastytrade/tastytrade-public-watchlists-api/) — Allows an API client to fetch tastyworks watchlists.
- [tastytrade Quote Alerts API](https://apis.io/apis/tastytrade/tastytrade-quote-alerts-api/) — Operations about quote-alerts
- [tastytrade Simulate Trade API](https://apis.io/apis/tastytrade/tastytrade-simulate-trade-api/) — The Simulate Trade API from tastytrade — 1 operation(s) for simulate trade.
- [tastytrade Span API](https://apis.io/apis/tastytrade/tastytrade-span-api/) — Operations about spans
- [tastytrade Symbols API](https://apis.io/apis/tastytrade/tastytrade-symbols-api/) — The Symbols API from tastytrade — 1 operation(s) for symbols.
- [tastytrade Trading Status API](https://apis.io/apis/tastytrade/tastytrade-trading-status-api/) — Allows an API client to request information about the basic trade status of an account. \ This includes information about the strategies an account can trade.
- [tastytrade Transactions API](https://apis.io/apis/tastytrade/tastytrade-transactions-api/) — Operations about transactions
- [tastytrade User Watchlists API](https://apis.io/apis/tastytrade/tastytrade-user-watchlists-api/) — Allows an API client to fetch a user's watchlists.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Tastytrade Agentic Access](https://apis.io/agentic-access/tastytrade/tastytrade-agentic-access/)

#### JSON Schema (66)

The data models the API reads and writes.

- [TradingStatus](https://apis.io/schemas/tastytrade/account-status-TradingStatus/)
- [Account](https://apis.io/schemas/tastytrade/accounts-and-customers-Account/)
- [AccountAuthorityDecorator](https://apis.io/schemas/tastytrade/accounts-and-customers-AccountAuthorityDecorator/)
- [Customer](https://apis.io/schemas/tastytrade/accounts-and-customers-Customer/)
- [QuoteStreamerTokenAuthResult](https://apis.io/schemas/tastytrade/accounts-and-customers-QuoteStreamerTokenAuthResult/)
- [AvailableSymbolDates](https://apis.io/schemas/tastytrade/backtesting-AvailableSymbolDates/)
- [BacktestGet](https://apis.io/schemas/tastytrade/backtesting-BacktestGet/)
- [BacktestPost](https://apis.io/schemas/tastytrade/backtesting-BacktestPost/)
- [EntryConditions](https://apis.io/schemas/tastytrade/backtesting-EntryConditions/)
- [ExitConditions](https://apis.io/schemas/tastytrade/backtesting-ExitConditions/)
- [Leg](https://apis.io/schemas/tastytrade/backtesting-Leg/)
- [Snapshot](https://apis.io/schemas/tastytrade/backtesting-Snapshot/)
- [Trial](https://apis.io/schemas/tastytrade/backtesting-Trial/)
- [AccountBalance](https://apis.io/schemas/tastytrade/balances-and-positions-AccountBalance/)
- [AccountBalanceSnapshot](https://apis.io/schemas/tastytrade/balances-and-positions-AccountBalanceSnapshot/)
- [CurrentPosition](https://apis.io/schemas/tastytrade/balances-and-positions-CurrentPosition/)
- [CompactOptionChainSerializer](https://apis.io/schemas/tastytrade/instruments-CompactOptionChainSerializer/)
- [Cryptocurrency](https://apis.io/schemas/tastytrade/instruments-Cryptocurrency/)
- [Equity](https://apis.io/schemas/tastytrade/instruments-Equity/)
- [EquityOption](https://apis.io/schemas/tastytrade/instruments-EquityOption/)
- [Future](https://apis.io/schemas/tastytrade/instruments-Future/)
- [FutureOption](https://apis.io/schemas/tastytrade/instruments-FutureOption/)
- [FutureOptionProduct](https://apis.io/schemas/tastytrade/instruments-FutureOptionProduct/)
- [FutureProduct](https://apis.io/schemas/tastytrade/instruments-FutureProduct/)
- [FuturesNestedOptionChainSerializer](https://apis.io/schemas/tastytrade/instruments-FuturesNestedOptionChainSerializer/)
- …and 41 more published on APIs.io

#### JSON-LD (2)

Linked-data contexts for the provider's vocabulary.

- [Tastytrade Api Context](https://apis.io/jsonld/tastytrade/tastytrade-api/)
- [Tastytrade Context](https://apis.io/jsonld/tastytrade/tastytrade-context/)

#### Examples (38)

Example requests and responses.

- [Account Status Getaccountsaccountnumbertradingstatus](https://apis.io/examples/tastytrade/account-status-getAccountsAccountNumberTradingStatus/)
- [Accounts And Customers Getapiquotetokens](https://apis.io/examples/tastytrade/accounts-and-customers-getApiQuoteTokens/)
- [Accounts And Customers Getcustomerscustomerid](https://apis.io/examples/tastytrade/accounts-and-customers-getCustomersCustomerId/)
- [Accounts And Customers Getcustomerscustomeridaccounts](https://apis.io/examples/tastytrade/accounts-and-customers-getCustomersCustomerIdAccounts/)
- [Backtesting Getbacktests](https://apis.io/examples/tastytrade/backtesting-GetBacktests/)
- [Backtesting Getbacktestslogs](https://apis.io/examples/tastytrade/backtesting-GetBacktestsLogs/)
- [Backtesting Getusersbacktests](https://apis.io/examples/tastytrade/backtesting-GetUsersBacktests/)
- [Balances And Positions Getaccountsaccountnumberbalancesnapshots](https://apis.io/examples/tastytrade/balances-and-positions-getAccountsAccountNumberBalanceSnapshots/)
- [Balances And Positions Getaccountsaccountnumberbalances](https://apis.io/examples/tastytrade/balances-and-positions-getAccountsAccountNumberBalances/)
- [Balances And Positions Getaccountsaccountnumberbalancescurrency](https://apis.io/examples/tastytrade/balances-and-positions-getAccountsAccountNumberBalancesCurrency/)
- [Instruments Getfuturesoptionchainssymbol](https://apis.io/examples/tastytrade/instruments-getFuturesOptionChainsSymbol/)
- [Instruments Getfuturesoptionchainssymbolnested](https://apis.io/examples/tastytrade/instruments-getFuturesOptionChainsSymbolNested/)
- [Instruments Getinstrumentscryptocurrencies](https://apis.io/examples/tastytrade/instruments-getInstrumentsCryptocurrencies/)
- [Margin Requirements Createmarginaccountsaccountnumberdryrun](https://apis.io/examples/tastytrade/margin-requirements-createMarginAccountsAccountNumberDryRun/)
- [Margin Requirements Getmarginaccountsaccountnumberrequirements](https://apis.io/examples/tastytrade/margin-requirements-getMarginAccountsAccountNumberRequirements/)
- [Market Data Getmarketdatabytype](https://apis.io/examples/tastytrade/market-data-getMarketDataByType/)
- [Market Metrics Getmarketmetricsdividendssymbol](https://apis.io/examples/tastytrade/market-metrics-getMarketMetricsDividendsSymbol/)
- [Market Metrics Getmarketmetricsearningssymbol](https://apis.io/examples/tastytrade/market-metrics-getMarketMetricsEarningsSymbol/)
- [Market Metrics Getmarketmetricsindex](https://apis.io/examples/tastytrade/market-metrics-getMarketMetricsIndex/)
- [Market Sessions Getmarkettimeequitiessessionscurrent](https://apis.io/examples/tastytrade/market-sessions-getMarketTimeEquitiesSessionsCurrent/)
- [Market Sessions Getmarkettimesessions](https://apis.io/examples/tastytrade/market-sessions-getMarketTimeSessions/)
- [Market Sessions Getmarkettimesessionscurrent](https://apis.io/examples/tastytrade/market-sessions-getMarketTimeSessionsCurrent/)
- [Net Liquidating Value History Getnetliqhistory](https://apis.io/examples/tastytrade/net-liquidating-value-history-getNetLiqHistory/)
- [Orders Getaccountsaccountnumbercomplexorders](https://apis.io/examples/tastytrade/orders-getAccountsAccountNumberComplexOrders/)
- [Orders Getaccountsaccountnumbercomplexorderslive](https://apis.io/examples/tastytrade/orders-getAccountsAccountNumberComplexOrdersLive/)
- …and 13 more published on APIs.io

#### Collections (27)

Postman and Open Collection request collections.

- [Account Status accounts API](https://apis.io/collections/tastytrade/open-tastytrade-accounts-api/)
- [Account Status accounts api-quote-tokens API](https://apis.io/collections/tastytrade/open-tastytrade-api-quote-tokens-api/)
- [Account Status accounts Available Dates API](https://apis.io/collections/tastytrade/open-tastytrade-available-dates-api/)
- [Account Status accounts Backtests API](https://apis.io/collections/tastytrade/open-tastytrade-backtests-api/)
- [Account Status accounts balance-snapshots API](https://apis.io/collections/tastytrade/open-tastytrade-balance-snapshots-api/)
- [Account Status accounts complex-orders API](https://apis.io/collections/tastytrade/open-tastytrade-complex-orders-api/)
- [Account Status accounts customers API](https://apis.io/collections/tastytrade/open-tastytrade-customers-api/)
- [Account Status accounts futures-option-chains API](https://apis.io/collections/tastytrade/open-tastytrade-futures-option-chains-api/)
- [Account Status accounts instruments API](https://apis.io/collections/tastytrade/open-tastytrade-instruments-api/)
- [Account Status accounts margin-requirements API](https://apis.io/collections/tastytrade/open-tastytrade-margin-requirements-api/)
- [Account Status accounts margin-requirements-public-configuration API](https://apis.io/collections/tastytrade/open-tastytrade-margin-requirements-public-configuration-api/)
- [Account Status accounts market-data-controller API](https://apis.io/collections/tastytrade/open-tastytrade-market-data-controller-api/)
- [Account Status accounts Market Metrics API](https://apis.io/collections/tastytrade/open-tastytrade-market-metrics-api/)
- [Account Status accounts market-time API](https://apis.io/collections/tastytrade/open-tastytrade-market-time-api/)
- [Account Status accounts net-liq-controller API](https://apis.io/collections/tastytrade/open-tastytrade-net-liq-controller-api/)
- [Account Status accounts option-chains API](https://apis.io/collections/tastytrade/open-tastytrade-option-chains-api/)
- [Account Status accounts orders API](https://apis.io/collections/tastytrade/open-tastytrade-orders-api/)
- [Account Status accounts pairs-watchlists API](https://apis.io/collections/tastytrade/open-tastytrade-pairs-watchlists-api/)
- [Account Status accounts positions API](https://apis.io/collections/tastytrade/open-tastytrade-positions-api/)
- [Account Status accounts public-watchlists API](https://apis.io/collections/tastytrade/open-tastytrade-public-watchlists-api/)
- [Account Status accounts quote-alerts API](https://apis.io/collections/tastytrade/open-tastytrade-quote-alerts-api/)
- [Account Status accounts Simulate Trade API](https://apis.io/collections/tastytrade/open-tastytrade-simulate-trade-api/)
- [Account Status accounts span API](https://apis.io/collections/tastytrade/open-tastytrade-span-api/)
- [Account Status accounts Symbols API](https://apis.io/collections/tastytrade/open-tastytrade-symbols-api/)
- [Account Status accounts trading-status API](https://apis.io/collections/tastytrade/open-tastytrade-trading-status-api/)
- …and 2 more published on APIs.io

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [tastytrade — jsonschema rules](https://apis.io/rules/tastytrade/tastytrade-jsonschema-spectral-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Tastytrade Domain Security](https://apis.io/security/tastytrade/tastytrade-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Plans](https://apis.io/plans/tastytrade/plans/)

#### Rate limits (1)

Published request limits.

- [Rate Limits](https://apis.io/rate-limits/tastytrade/rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Finops](https://apis.io/finops/tastytrade/finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://tastytrade.com/)
- [Documentation](https://developer.tastytrade.com/)
- [Changelog](https://developer.tastytrade.com/release-notes/)
- [Blog](https://tastytrade.com/newsroom/)
- [Terms of service](https://assets.tastyworks.com/production/documents/USA/open_api_terms_and_conditions.pdf)
- [GitHub](https://github.com/tastytrade/)

## API Evangelist rating

**Kin Score 40.2** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 49.3 |
| Contract governance | 23.5 |
| Operational transparency | 26.3 |
| Developer ergonomics | 57.1 |
| Access clarity | 15.8 |

**Agent readiness 24.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | mostly (partial credit) |

**Regulatory alignment 25.0** — Securities & Market Data

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/tastytrade/](https://apis.io/providers/tastytrade/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for tastytrade: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/tastytrade/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
