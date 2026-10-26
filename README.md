# Stadia Maps (stadia-maps)

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

Stadia Maps is a cutting-edge mapping platform providing high-quality, detailed maps and location APIs for developers. The platform offers routing and navigation, geocoding and search, elevation data, time zone lookups, isochrone analysis, and account management. Stadia Maps delivers GDPR-compliant EU endpoints, rich map styling options, and official SDKs for TypeScript, Python, Swift, Kotlin, and PHP. Trusted by developers building web, mobile, and data visualization applications worldwide.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/stadia-maps/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/stadia-maps/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Mapping
- Maps
- Geocoding
- Routing
- Navigation
- Geospatial
- Location

## Timestamps

- **Created:** 2024-12-16
- **Modified:** 2026-05-19

## APIs

### Stadia Maps Geospatial API

The Stadia Maps Geospatial API provides routing and turn-by-turn navigation, geocoding and autocomplete search, reverse geocoding, place lookups, elevation profiles, time zone information, road attributes, isochrones, map matching, time-distance matrices, and optimized routing. Secured with API key authentication. EU-region endpoint available for GDPR compliance.

- **Human URL:** [https://docs.stadiamaps.com/](https://docs.stadiamaps.com/)
- **Base URL:** `https://api.stadiamaps.com`

#### Tags

- Attributes
- Autocomplete
- Elevation
- Geospatial
- Geocoding
- Isochrone
- Lookups
- Mapping
- Match
- Navigation
- Place
- Reverse
- Roads
- Routes
- Routing
- Search
- Time Zone

#### Properties

- [Documentation](https://docs.stadiamaps.com/)
- [OpenAPI](openapi/stadia-maps-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://docs.stadiamaps.com/authentication/)
- [Documentation](https://docs.stadiamaps.com/routing/)
- [Documentation](https://docs.stadiamaps.com/geocoding-search-autocomplete/)
- [Spectral Ruleset](rules/stadia-maps-rules.yml)
- [JSON Schema](json-schema/stadia-maps-location-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](json-ld/stadia-maps-context.jsonld)
- [Vocabulary](vocabulary/stadia-maps-vocabulary.yml)

### Stadia Maps Account Management API

The Stadia Maps Account Management API enables programmatic management of properties, domains, and API keys. Useful for managing large numbers of properties, automating domain allowlisting, and programmatically rotating API keys. Access is available on request.

- **Human URL:** [https://docs.stadiamaps.com/client-api/](https://docs.stadiamaps.com/client-api/)
- **Base URL:** `https://client.stadiamaps.com/api/v1`

#### Tags

- Account Management
- API Keys
- Domains
- Properties

#### Properties

- [Documentation](https://docs.stadiamaps.com/client-api/)
- [OpenAPI](https://client.stadiamaps.com/api/v1/openapi/) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/stadia-maps)
- [Portal](https://stadiamaps.com/)
- [Documentation](https://docs.stadiamaps.com/)
- [API Reference](https://docs.stadiamaps.com/api-reference/)
- [Pricing](https://stadiamaps.com/pricing/)
- [Contact](https://stadiamaps.com/contact/)
- [Authentication](https://docs.stadiamaps.com/authentication/)
- [GitHub Organization](https://github.com/stadiamaps)
- [SDK](https://www.npmjs.com/package/@stadiamaps/api)
- [SDK](https://pypi.org/project/stadiamaps-api/)
- [M C P Server](https://github.com/stadiamaps/stadiamaps-mcp-server-ts)
- [L L Ms Txt](https://docs.stadiamaps.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
