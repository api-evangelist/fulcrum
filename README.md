# Fulcrum (fulcrum)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Fulcrum is a field data collection and inspection platform used by teams to build mobile forms, capture geospatial records, attach photos, videos, audio, and signatures, and synchronize the resulting data with back-office systems. The Fulcrum REST API exposes programmatic access to forms, records, media, choice lists, classification sets, projects, layers, memberships, roles, webhooks, ad hoc SQL queries, and changesets.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/fulcrum/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/fulcrum/refs/heads/main/apis.yml)

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
- **Modified:** 2026-05-19

## APIs

### Fulcrum API

The Fulcrum API is a RESTful HTTP API that provides programmatic access to all Fulcrum resources. It supports CRUD operations on forms (apps) and records, uploads of photo, video, audio, and signature media tied to records, management of choice lists and classification sets, project and layer configuration, account memberships and roles, outbound webhooks, and ad hoc SQL queries against a read-only mirror of the customer data. All requests authenticate using an X-ApiToken header and exchange JSON bodies.

- **Human URL:** [https://docs.fulcrumapp.com/reference/](https://docs.fulcrumapp.com/reference/)
- **Base URL:** `https://api.fulcrumapp.com/api/v2`

#### Tags

- Data Collection
- Field Data
- Geospatial
- Forms
- Records
- Media
- Webhooks

#### Properties

- [Documentation](https://docs.fulcrumapp.com/reference/)
- [Getting Started](https://docs.fulcrumapp.com/docs)
- [OpenAPI](openapi/fulcrum-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fulcrum-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fulcrum-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/fulcrumapp)
- [Website](https://www.fulcrumapp.com/)
- [Documentation](https://docs.fulcrumapp.com/)
- [Getting Started](https://docs.fulcrumapp.com/docs)
- [Pricing](https://www.fulcrumapp.com/pricing/)
- [Login](https://web.fulcrumapp.com/users/sign_in)
- [Sign Up](https://web.fulcrumapp.com/users/sign_up)
- [Privacy Policy](https://www.fulcrumapp.com/privacy/)
- [Terms of Service](https://www.fulcrumapp.com/terms/)
- [Support](https://www.fulcrumapp.com/support/)
- [Blog](https://www.fulcrumapp.com/blog/)
- [Integrations](https://www.fulcrumapp.com/integrations/)
- [L L Ms Txt](https://docs.fulcrumapp.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
