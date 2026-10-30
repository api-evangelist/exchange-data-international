# Exchange Data International

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

Exchange Data International (EDI) is an independent, privately held financial data vendor founded in 1994 by Jonathan Bloch and headquartered in London, with operations in the USA, India, and Morocco serving 450+ institutional clients. EDI sells securities reference data, worldwide equity and fixed income corporate actions, end-of-day pricing, adjustment factors, shares outstanding, derivatives reference and pricing, economic indicators and calendars, fund NAVs, and FX rates. Data is delivered as SFTP flat-file feeds and through a self-serve REST API: the EDI Developer portal (developer.exchange-data.com) documents 24 API products on a shared base at api3.exchange-data.com, with account registration, an API Playground, per-product subscriptions, and JSON or pipe-separated responses. No public OpenAPI or AsyncAPI specification is published.

**Areas:** Finance · Market Data · Corporate Actions · Reference Data · End of Day Pricing · Fixed Income · Derivatives · Economic Data · Stocks

## Exchange Data International on APIs.io

Everything profiled for Exchange Data International is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/exchange-data-international/](https://apis.io/providers/exchange-data-international/)** — or go straight to one of the APIs or properties below.

### APIs (24)

- [EDI End of Day Pricing Data API](https://apis.io/apis/exchange-data-international/end-of-day-pricing-api/) — Worldwide end-of-day equity pricing (open, high, low, close, bid, ask, last trade, volume) queried by MIC, LocalCode, or ISIN via the GetLatestEODPrices…
- [EDI Adjustment Factors Data API](https://apis.io/apis/exchange-data-international/adjustment-factors-api/) — Adjustment factors used to back-adjust end-of-day per-share price series for corporate actions so historical prices can be graphed consistently, via the…
- [EDI Worldwide Equity Analytics API](https://apis.io/apis/exchange-data-international/worldwide-equity-analytics-api/) — Equity analytics measures for worldwide listed securities via the GetLatestEquityAnalytics endpoint on EDI's shared REST base.
- [EDI OTC Data API](https://apis.io/apis/exchange-data-international/otc-data-api/) — Daily over-the-counter bond pricing, including independent zero-coupon and swap-implied yield curves for valuations, via the GetBondLatestPricing endpoint.
- [EDI Derivatives Reference Data API](https://apis.io/apis/exchange-data-international/derivatives-reference-data-api/) — Listed derivatives security master reference data via the GetOptionSecurityMaster endpoint, covering exchange-traded options contract specifications.
- [EDI Derivatives End of Day Pricing API](https://apis.io/apis/exchange-data-international/derivatives-eod-pricing-api/) — End-of-day pricing for listed derivatives via the GetDerivativesPricing endpoint.
- [EDI Worldwide Corporate Actions API](https://apis.io/apis/exchange-data-international/worldwide-corporate-actions-api/) — Worldwide equity corporate actions with 200+ output fields (security identifiers, issuer, event details, dates, payment information) queried by…
- [EDI Exchange Traded Notes API](https://apis.io/apis/exchange-data-international/exchange-traded-notes-api/) — Exchange traded notes data via the GetLatestExchangeTradedNotes endpoint.
- [EDI Worldwide Fixed Income Corporate Actions API](https://apis.io/apis/exchange-data-international/worldwide-fixed-income-corporate-actions-api/) — Fixed income security master and corporate actions coverage for bonds via the GetBondSecurityMaster endpoint.
- [EDI Securities Reference Data API](https://apis.io/apis/exchange-data-international/securities-reference-data-api/) — Consolidated securities reference file (SRF) data for worldwide listed instruments via the GetConsolidatedSRF endpoint.
- [EDI Global Market Holidays and Timings API](https://apis.io/apis/exchange-data-international/global-market-holidays-api/) — Holiday observances and market timings for worldwide exchanges via the GetGlobalMarketHolidays endpoint; the service is divided into five products covering…
- [EDI Worldwide Shares Outstanding API](https://apis.io/apis/exchange-data-international/worldwide-shares-outstanding-api/) — Shares outstanding figures for worldwide listed equities via the GetLatestSharesOutstanding endpoint.
- [EDI DerivActions API](https://apis.io/apis/exchange-data-international/derivactions-api/) — Detailed exchange adjustment notices for listed derivatives in a standardized machine-readable format, queried by underlying MIC, ISIN, or symbol via…
- [EDI Global Economic Indicators API](https://apis.io/apis/exchange-data-international/global-economic-indicators-api/) — Global economic indicator releases via the GetLatestEconomicIndicator endpoint.
- [EDI Economic Calendar API](https://apis.io/apis/exchange-data-international/economic-calendar-api/) — Forward-looking economic calendar events via the GetLatestEconomicCalendar endpoint.
- [EDI Central Bank Calendar API](https://apis.io/apis/exchange-data-international/central-bank-calendar-api/) — Central bank meeting and announcement calendar via the GetLatestCentralBankCalendar endpoint.
- [EDI US Economic Data API](https://apis.io/apis/exchange-data-international/us-economic-data-api/) — United States economic data series via the GetUsEconomicData endpoint (documented on the developer portal with an http:// scheme against the same api3 host).
- [EDI Initial Public Offerings API](https://apis.io/apis/exchange-data-international/initial-public-offerings-api/) — Worldwide initial public offering data via the GetLatestInitialPublicOfferings endpoint.
- [EDI Corporate Bonds Data API](https://apis.io/apis/exchange-data-international/corporate-bonds-evaluated-pricing-api/) — Corporate bond evaluations via the GetLatestCorporateEvaluations endpoint, documented in the catalogue as the Corporate Bonds Data Dictionary product.
- [EDI Option Analytics Service API](https://apis.io/apis/exchange-data-international/option-analytics-api/) — Options analytics including Greeks via the GetLatestOptionsGreeks endpoint.
- [EDI Worldwide Funds Corporate Actions API](https://apis.io/apis/exchange-data-international/worldwide-funds-corporate-actions-api/) — Fund corporate actions coverage; the documented endpoint GetLatestSouthAfricanFundDistributions returns South African fund distribution events.
- [EDI Net Asset Value API](https://apis.io/apis/exchange-data-international/net-asset-value-api/) — Investment fund net asset values via the GetLatestNetAssetValue endpoint.
- [EDI Index Constitution API](https://apis.io/apis/exchange-data-international/index-constitution-api/) — Index constituent reference data via the GetReferenceNameForIndexConstituents endpoint.
- [EDI Foreign Exchange Rates API](https://apis.io/apis/exchange-data-international/foreign-exchange-rates-api/) — Foreign exchange rates via the GetLatestFXRates endpoint.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Exchange Data International Authentication](https://apis.io/security/exchange-data-international/exchange-data-international-authentication/)
- [Exchange Data International Domain Security](https://apis.io/security/exchange-data-international/exchange-data-international-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.exchange-data.com/)
- [Documentation](https://developer.exchange-data.com/api-documentation/)
- [API reference](https://developer.exchange-data.com/api-documentation/)
- [Sign up](https://developer.exchange-data.com/register)
- [Support](https://developer.exchange-data.com/contact)
- [Blog](https://www.exchange-data.com/insights-edi/)
- [Terms of service](https://www.exchange-data.com/terms-and-conditions/)
- [Privacy policy](https://www.exchange-data.com/privacy-policy/)

## API Evangelist rating

**Kin Score 26.1** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 0.0 |
| Contract governance | 4.5 |
| Operational transparency | 0.0 |
| Developer ergonomics | 52.4 |
| Access clarity | 34.2 |

**Agent readiness 5.4** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
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

**Regulatory alignment 23.1** — Securities & Market Data

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/exchange-data-international/](https://apis.io/providers/exchange-data-international/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Exchange Data International: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/exchange-data-international/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
