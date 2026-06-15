# Interactive Brokers (interactive-brokers)

Interactive Brokers is an online brokerage firm providing trading access to stocks, options, futures, currencies, bonds, and funds across 150+ markets worldwide. IBKR offers comprehensive REST APIs that enable developers and traders to programmatically access trading, portfolio management, market data, and account management capabilities through the IBKR Web API and Client Portal API.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/interactive-brokers/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/interactive-brokers/refs/heads/main/apis.yml)

## Tags

- Brokerage
- Market Data
- Orders
- Portfolio
- Trading

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-05-29

## APIs

### Interactive Brokers Web API

The Interactive Brokers Web API is a RESTful API that provides programmatic access to IBKR trading, portfolio management, market data, and account information. The API consolidates the Client Portal Web API, Digital Account Management, and Flex Web Service into a unified interface. It supports OAuth 2.0 authentication and provides endpoints for order placement, portfolio monitoring, real-time and historical market data, and account management across global markets.

- **Human URL:** [https://www.interactivebrokers.com/campus/ibkr-api-page/webapi-doc/](https://www.interactivebrokers.com/campus/ibkr-api-page/webapi-doc/)
- **Base URL:** `https://localhost:5000/v1/api`

#### Tags

- Brokerage
- Market Data
- Orders
- Portfolio
- Trading

#### Properties

- [Documentation](https://www.interactivebrokers.com/campus/ibkr-api-page/webapi-doc/)
- [OpenAPI](openapi/interactive-brokers-web-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/interactive-brokers-web-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/interactive-brokers-web-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/interactive-brokers-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### Interactive Brokers Client Portal API

The Interactive Brokers Client Portal API is a REST API accessed through a locally running Java gateway that routes authenticated requests to IBKR systems. It provides a lightweight interface for trading, viewing portfolio information, accessing market data, and managing authentication. The API uses a two-tiered session structure with read-only and brokerage session levels.

- **Human URL:** [https://interactivebrokers.github.io/cpwebapi/](https://interactivebrokers.github.io/cpwebapi/)
- **Base URL:** `https://localhost:5000/v1/api`

#### Tags

- Authentication
- Brokerage
- Gateway
- Trading

#### Properties

- [Documentation](https://interactivebrokers.github.io/cpwebapi/)
- [Postman Collection](collections/interactive-brokers-web-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/interactive-brokers-web-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/interactive-brokers)
- [Portal](https://www.interactivebrokers.com/campus/ibkr-api-page/ibkr-api-home/)
- [Documentation](https://www.interactivebrokers.com/campus/ibkr-api-page/webapi-doc/)
- [Website](https://www.interactivebrokers.com/)
- [Git Hub](https://github.com/nicholasgasior/interactive-brokers-api)
- [Login](https://www.interactivebrokers.com/sso/Login)

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
