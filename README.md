# Mews (mews)

Mews is a cloud property management system (PMS) for hotels, hostels, and apartments. Mews exposes a comprehensive Connector API, a Distributor API for booking, and a Channel Manager API. The Connector API publishes a full OpenAPI 3.0.4 spec covering operations, events, and webhooks for partners.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/mews/refs/heads/main/apis.yml)

## Type
- **x-type:** company

## Tags
- Hospitality, Hotels, PMS, Property Management

## APIs
- **Mews Connector API** — general-purpose partner REST API at `https://api.mews.com`; full OpenAPI 3.0.4 spec stored at `openapi/mews-connector-openapi.yaml`. Docs: https://docs.mews.com/connector-api
- **Mews Distributor API** — booking engine + distribution.
- **Mews Channel Manager API** — channel manager integrations.

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://www.mews.com/)
- [Developer Portal](https://docs.mews.com/)
- [Plans](plans/mews-plans-pricing.yml) — per-property monthly SaaS (reconciled: false)
- [RateLimits](rate-limits/mews-rate-limits.yml) — per-token throttle; honor 429 (reconciled: false)
- [FinOps](finops/mews-finops.yml) — FOCUS-aligned hybrid (reconciled: false)

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
