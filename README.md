# Exchange Data International (exchange-data-international)

Exchange Data International (EDI) is an independent, privately held financial data vendor founded in 1994 by Jonathan Bloch and headquartered in London, with operations in the USA, India, and Morocco serving 450+ institutional clients. EDI sells securities reference data, worldwide equity and fixed income corporate actions, end-of-day pricing, adjustment factors, shares outstanding, derivatives reference and pricing, economic indicators and calendars, fund NAVs, and FX rates. Data is delivered as SFTP flat-file feeds and through a self-serve REST API: the EDI Developer portal (developer.exchange-data.com) documents 24 API products on a shared base at api3.exchange-data.com, with account registration, an API Playground, per-product subscriptions, and JSON or pipe-separated responses. No public OpenAPI or AsyncAPI specification is published.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/exchange-data-international/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/exchange-data-international/refs/heads/main/apis.yml)

## Tags

- Financial
- Market Data
- Corporate Actions
- Reference Data
- End of Day Pricing
- Fixed Income
- Derivatives
- Economic Data
- Stocks
- Exchange

## Timestamps

- **Created:** 2026-07-21
- **Modified:** 2026-07-21

## APIs

### EDI End of Day Pricing Data API

Worldwide end-of-day equity pricing (open, high, low, close, bid, ask, last trade, volume) queried by MIC, LocalCode, or ISIN via the GetLatestEODPrices endpoint, returned as JSON or pipe-separated values with pagination.

- **Human URL:** [https://developer.exchange-data.com/api-documentation/end_of_day_pricing_data](https://developer.exchange-data.com/api-documentation/end_of_day_pricing_data)
- **Base URL:** `https://api3.exchange-data.com`

#### Tags

- Pricing
- End of Day
- Equities

#### Properties

- [Documentation](https://developer.exchange-data.com/api-documentation/end_of_day_pricing_data)

### EDI Adjustment Factors Data API

Adjustment factors used to back-adjust end-of-day per-share price series for corporate actions so historical prices can be graphed consistently, via the GetLatestAdjustmentFactors endpoint.

- **Human URL:** [https://developer.exchange-data.com/api-documentation/adjustment_factors_data](https://developer.exchange-data.com/api-documentation/adjustment_factors_data)
- **Base URL:** `https://api3.exchange-data.com`

#### Tags

- Adjustment Factors
- Pricing
- Corporate Actions

#### Properties

- [Documentation](https://developer.exchange-data.com/api-documentation/adjustment_factors_data)

### EDI Worldwide Equity Analytics API

Equity analytics measures for worldwide listed securities via the GetLatestEquityAnalytics endpoint on EDI's shared REST base.

- **Human URL:** [https://developer.exchange-data.com/api-documentation/worldwide_equity_analytics](https://developer.exchange-data.com/api-documentation/worldwide_equity_analytics)
- **Base URL:** `https://api3.exchange-data.com`

#### Tags

- Equities
- Analytics

#### Properties

- [Documentation](https://developer.exchange-data.com/api-documentation/worldwide_equity_analytics)

### EDI OTC Data API

Daily over-the-counter bond pricing, including independent zero-coupon and swap-implied yield curves for valuations, via the GetBondLatestPricing endpoint.

- **Human URL:** [https://developer.exchange-data.com/api-documentation/bond_price_otc_data](https://developer.exchange-data.com/api-documentation/bond_price_otc_data)
- **Base URL:** `https://api3.exchange-data.com`

#### Tags

- Bonds
- OTC
- Pricing
- Yield Curves

#### Properties

- [Documentation](https://developer.exchange-data.com/api-documentation/bond_price_otc_data)

### EDI Derivatives Reference Data API

Listed derivatives security master reference data via the GetOptionSecurityMaster endpoint, covering exchange-traded options contract specifications.

- **Human URL:** [https://developer.exchange-data.com/api-documentation/derivatives_reference_data](https://developer.exchange-data.com/api-documentation/derivatives_reference_data)
- **Base URL:** `https://api3.exchange-data.com`

#### Tags

- Derivatives
- Options
- Reference Data

#### Properties

- [Documentation](https://developer.exchange-data.com/api-documentation/derivatives_reference_data)

### EDI Derivatives End of Day Pricing API

End-of-day pricing for listed derivatives via the GetDerivativesPricing endpoint.

- **Human URL:** [https://developer.exchange-data.com/api-documentation/derivatives_end_of_day_pricing](https://developer.exchange-data.com/api-documentation/derivatives_end_of_day_pricing)
- **Base URL:** `https://api3.exchange-data.com`

#### Tags

- Derivatives
- Pricing
- End of Day

#### Properties

- [Documentation](https://developer.exchange-data.com/api-documentation/derivatives_end_of_day_pricing)

### EDI Worldwide Corporate Actions API

Worldwide equity corporate actions with 200+ output fields (security identifiers, issuer, event details, dates, payment information) queried by OperationalMic, LocalCode, ISIN, or event code via GetLatestCorporateActions, in JSON or PSV.

- **Human URL:** [https://developer.exchange-data.com/api-documentation/world_corporate_actions](https://developer.exchange-data.com/api-documentation/world_corporate_actions)
- **Base URL:** `https://api3.exchange-data.com`

#### Tags

- Corporate Actions
- Equities
- Dividends

#### Properties

- [Documentation](https://developer.exchange-data.com/api-documentation/world_corporate_actions)

### EDI Exchange Traded Notes API

Exchange traded notes data via the GetLatestExchangeTradedNotes endpoint.

- **Human URL:** [https://developer.exchange-data.com/api-documentation/exchange_traded_notes](https://developer.exchange-data.com/api-documentation/exchange_traded_notes)
- **Base URL:** `https://api3.exchange-data.com`

#### Tags

- ETN
- Exchange Traded Products

#### Properties

- [Documentation](https://developer.exchange-data.com/api-documentation/exchange_traded_notes)

### EDI Worldwide Fixed Income Corporate Actions API

Fixed income security master and corporate actions coverage for bonds via the GetBondSecurityMaster endpoint.

- **Human URL:** [https://developer.exchange-data.com/api-documentation/worldwide_fixed_income_corporate_action](https://developer.exchange-data.com/api-documentation/worldwide_fixed_income_corporate_action)
- **Base URL:** `https://api3.exchange-data.com`

#### Tags

- Fixed Income
- Bonds
- Corporate Actions
- Reference Data

#### Properties

- [Documentation](https://developer.exchange-data.com/api-documentation/worldwide_fixed_income_corporate_action)

### EDI Securities Reference Data API

Consolidated securities reference file (SRF) data for worldwide listed instruments via the GetConsolidatedSRF endpoint.

- **Human URL:** [https://developer.exchange-data.com/api-documentation/securities_reference_data](https://developer.exchange-data.com/api-documentation/securities_reference_data)
- **Base URL:** `https://api3.exchange-data.com`

#### Tags

- Reference Data
- Securities
- ISIN

#### Properties

- [Documentation](https://developer.exchange-data.com/api-documentation/securities_reference_data)

### EDI Global Market Holidays and Timings API

Holiday observances and market timings for worldwide exchanges via the GetGlobalMarketHolidays endpoint; the service is divided into five products covering holidays and trading hours.

- **Human URL:** [https://developer.exchange-data.com/api-documentation/financial_public_holidays](https://developer.exchange-data.com/api-documentation/financial_public_holidays)
- **Base URL:** `https://api3.exchange-data.com`

#### Tags

- Market Holidays
- Trading Calendar
- Exchanges

#### Properties

- [Documentation](https://developer.exchange-data.com/api-documentation/financial_public_holidays)

### EDI Worldwide Shares Outstanding API

Shares outstanding figures for worldwide listed equities via the GetLatestSharesOutstanding endpoint.

- **Human URL:** [https://developer.exchange-data.com/api-documentation/worldwide_shares_outstanding](https://developer.exchange-data.com/api-documentation/worldwide_shares_outstanding)
- **Base URL:** `https://api3.exchange-data.com`

#### Tags

- Shares Outstanding
- Equities
- Reference Data

#### Properties

- [Documentation](https://developer.exchange-data.com/api-documentation/worldwide_shares_outstanding)

### EDI DerivActions API

Detailed exchange adjustment notices for listed derivatives in a standardized machine-readable format, queried by underlying MIC, ISIN, or symbol via GetLatestDerivActions.

- **Human URL:** [https://developer.exchange-data.com/api-documentation/deriv_actions](https://developer.exchange-data.com/api-documentation/deriv_actions)
- **Base URL:** `https://api3.exchange-data.com`

#### Tags

- Derivatives
- Corporate Actions
- Adjustment Notices

#### Properties

- [Documentation](https://developer.exchange-data.com/api-documentation/deriv_actions)

### EDI Global Economic Indicators API

Global economic indicator releases via the GetLatestEconomicIndicator endpoint.

- **Human URL:** [https://developer.exchange-data.com/api-documentation/economic_indicator](https://developer.exchange-data.com/api-documentation/economic_indicator)
- **Base URL:** `https://api3.exchange-data.com`

#### Tags

- Economic Data
- Indicators
- Macro

#### Properties

- [Documentation](https://developer.exchange-data.com/api-documentation/economic_indicator)

### EDI Economic Calendar API

Forward-looking economic calendar events via the GetLatestEconomicCalendar endpoint.

- **Human URL:** [https://developer.exchange-data.com/api-documentation/economic_calendar](https://developer.exchange-data.com/api-documentation/economic_calendar)
- **Base URL:** `https://api3.exchange-data.com`

#### Tags

- Economic Data
- Calendar
- Macro

#### Properties

- [Documentation](https://developer.exchange-data.com/api-documentation/economic_calendar)

### EDI Central Bank Calendar API

Central bank meeting and announcement calendar via the GetLatestCentralBankCalendar endpoint.

- **Human URL:** [https://developer.exchange-data.com/api-documentation/central_bank_calendar](https://developer.exchange-data.com/api-documentation/central_bank_calendar)
- **Base URL:** `https://api3.exchange-data.com`

#### Tags

- Central Banks
- Calendar
- Macro

#### Properties

- [Documentation](https://developer.exchange-data.com/api-documentation/central_bank_calendar)

### EDI US Economic Data API

United States economic data series via the GetUsEconomicData endpoint (documented on the developer portal with an http:// scheme against the same api3 host).

- **Human URL:** [https://developer.exchange-data.com/api-documentation/economic_data](https://developer.exchange-data.com/api-documentation/economic_data)
- **Base URL:** `https://api3.exchange-data.com`

#### Tags

- Economic Data
- United States
- Macro

#### Properties

- [Documentation](https://developer.exchange-data.com/api-documentation/economic_data)

### EDI Initial Public Offerings API

Worldwide initial public offering data via the GetLatestInitialPublicOfferings endpoint.

- **Human URL:** [https://developer.exchange-data.com/api-documentation/initial_public_offerings](https://developer.exchange-data.com/api-documentation/initial_public_offerings)
- **Base URL:** `https://api3.exchange-data.com`

#### Tags

- IPO
- Equities
- New Issues

#### Properties

- [Documentation](https://developer.exchange-data.com/api-documentation/initial_public_offerings)

### EDI Corporate Bonds Data API

Corporate bond evaluations via the GetLatestCorporateEvaluations endpoint, documented in the catalogue as the Corporate Bonds Data Dictionary product.

- **Human URL:** [https://developer.exchange-data.com/api-documentation/corporate_bonds_data_dictionary](https://developer.exchange-data.com/api-documentation/corporate_bonds_data_dictionary)
- **Base URL:** `https://api3.exchange-data.com`

#### Tags

- Fixed Income
- Corporate Bonds
- Evaluated Pricing

#### Properties

- [Documentation](https://developer.exchange-data.com/api-documentation/corporate_bonds_data_dictionary)

### EDI Option Analytics Service API

Options analytics including Greeks via the GetLatestOptionsGreeks endpoint.

- **Human URL:** [https://developer.exchange-data.com/api-documentation/option_analytics_service](https://developer.exchange-data.com/api-documentation/option_analytics_service)
- **Base URL:** `https://api3.exchange-data.com`

#### Tags

- Options
- Greeks
- Analytics
- Derivatives

#### Properties

- [Documentation](https://developer.exchange-data.com/api-documentation/option_analytics_service)

### EDI Worldwide Funds Corporate Actions API

Fund corporate actions coverage; the documented endpoint GetLatestSouthAfricanFundDistributions returns South African fund distribution events.

- **Human URL:** [https://developer.exchange-data.com/api-documentation/worldwide_funds_corporate_action](https://developer.exchange-data.com/api-documentation/worldwide_funds_corporate_action)
- **Base URL:** `https://api3.exchange-data.com`

#### Tags

- Funds
- Corporate Actions
- Distributions

#### Properties

- [Documentation](https://developer.exchange-data.com/api-documentation/worldwide_funds_corporate_action)

### EDI Net Asset Value API

Investment fund net asset values via the GetLatestNetAssetValue endpoint.

- **Human URL:** [https://developer.exchange-data.com/api-documentation/net_asset_value](https://developer.exchange-data.com/api-documentation/net_asset_value)
- **Base URL:** `https://api3.exchange-data.com`

#### Tags

- Funds
- NAV
- Pricing

#### Properties

- [Documentation](https://developer.exchange-data.com/api-documentation/net_asset_value)

### EDI Index Constitution API

Index constituent reference data via the GetReferenceNameForIndexConstituents endpoint.

- **Human URL:** [https://developer.exchange-data.com/api-documentation/index_constitution](https://developer.exchange-data.com/api-documentation/index_constitution)
- **Base URL:** `https://api3.exchange-data.com`

#### Tags

- Indices
- Constituents
- Reference Data

#### Properties

- [Documentation](https://developer.exchange-data.com/api-documentation/index_constitution)

### EDI Foreign Exchange Rates API

Foreign exchange rates via the GetLatestFXRates endpoint.

- **Human URL:** [https://developer.exchange-data.com/api-documentation/foreign_exchange_rates](https://developer.exchange-data.com/api-documentation/foreign_exchange_rates)
- **Base URL:** `https://api3.exchange-data.com`

#### Tags

- FX
- Currencies
- Rates

#### Properties

- [Documentation](https://developer.exchange-data.com/api-documentation/foreign_exchange_rates)

## Common Properties

- [Website](https://www.exchange-data.com/)
- [Portal](https://developer.exchange-data.com/)
- [Documentation](https://developer.exchange-data.com/api-documentation/)
- [Sign Up](https://developer.exchange-data.com/register)
- [Blog](https://www.exchange-data.com/insights-edi/)
- [LinkedIn](https://www.linkedin.com/company/exchange-data-international/)
- [Terms of Service](https://www.exchange-data.com/terms-and-conditions/)
- [Privacy Policy](https://www.exchange-data.com/privacy-policy/)
- [Support](https://developer.exchange-data.com/contact)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
