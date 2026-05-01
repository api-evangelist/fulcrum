# Fulcrum (fulcrum)

Fulcrum is a field data collection and inspection platform used by teams to build mobile forms, capture geospatial records, attach photos, videos, audio, and signatures, and synchronize the resulting data with back-office systems. The Fulcrum REST API exposes programmatic access to forms, records, media, choice lists, classification sets, projects, layers, memberships, roles, webhooks, ad hoc SQL queries, and changesets.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/fulcrum/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Data Collection
- Field Data
- Geospatial
- Process Management
- Mobile

## Timestamps

- **Created:** 2024-11-13
- **Modified:** 2026-04-28

## APIs

### Fulcrum API

The Fulcrum API is a RESTful HTTP API that provides programmatic access to all Fulcrum resources. It supports CRUD operations on forms (apps) and records, uploads of photo, video, audio, and signature media tied to records, management of choice lists and classification sets, project and layer configuration, account memberships and roles, outbound webhooks, and ad hoc SQL queries against a read-only mirror of the customer data. All requests authenticate using an X-ApiToken header and exchange JSON bodies.

**Human URL:** https://docs.fulcrumapp.com/reference/

**Base URL:** `https://api.fulcrumapp.com/api/v2`

#### Tags

- Data Collection, Field Data, Geospatial, Forms, Records, Media, Webhooks

#### Properties

- [Documentation](https://docs.fulcrumapp.com/reference/)
- [Getting Started](https://docs.fulcrumapp.com/docs)
- [OpenAPI](openapi/fulcrum-api-openapi.yml)

## Artifacts

| Type | File | Description |
|------|------|-------------|
| OpenAPI | [openapi/fulcrum-api-openapi.yml](openapi/fulcrum-api-openapi.yml) | Fulcrum REST API covering forms, records, media, choice lists, classification sets, projects, layers, memberships, roles, webhooks, changesets, and SQL query |

## Common Properties

- [Website](https://www.fulcrumapp.com/)
- [Documentation](https://docs.fulcrumapp.com/)
- [GettingStarted](https://docs.fulcrumapp.com/docs)
- [Pricing](https://www.fulcrumapp.com/pricing/)
- [Login](https://web.fulcrumapp.com/users/sign_in)
- [SignUp](https://web.fulcrumapp.com/users/sign_up)
- [PrivacyPolicy](https://www.fulcrumapp.com/privacy/)
- [TermsOfService](https://www.fulcrumapp.com/terms/)
- [Support](https://www.fulcrumapp.com/support/)
- [Blog](https://www.fulcrumapp.com/blog/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
