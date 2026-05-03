# Stadia Maps (stadia-maps)

Stadia Maps is a cutting-edge mapping platform providing high-quality, detailed maps and location APIs for developers. The platform offers routing and turn-by-turn navigation, geocoding and autocomplete search, reverse geocoding, place lookups, elevation data, time zone information, isochrone analysis, map matching, and account management. Stadia Maps delivers GDPR-compliant EU endpoints, rich map styling options, and official SDKs for TypeScript, Python, Swift, Kotlin, and PHP.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/stadia-maps/refs/heads/main/apis.yml)

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
- **Modified:** 2026-05-02

## APIs

### Stadia Maps Geospatial API

The Stadia Maps Geospatial API provides routing and turn-by-turn navigation, geocoding and autocomplete search, reverse geocoding, place lookups, elevation profiles, time zone information, road attributes, isochrones, map matching, time-distance matrices, and optimized routing. Secured with API key authentication. EU-region endpoint available for GDPR compliance.

**Base URL:** https://api.stadiamaps.com

#### Properties

- [OpenAPI](openapi/stadia-maps-openapi.yml)
- [Documentation](https://docs.stadiamaps.com/)
- [Authentication](https://docs.stadiamaps.com/authentication/)
- [Routing Docs](https://docs.stadiamaps.com/routing/)
- [Geocoding Docs](https://docs.stadiamaps.com/geocoding-search-autocomplete/)
- [Spectral Ruleset](rules/stadia-maps-rules.yml)
- [Naftiko Capability](capabilities/geospatial-services.yaml)
- [JSON Schema](json-schema/stadia-maps-location-schema.json)
- [JSON-LD Context](json-ld/stadia-maps-context.jsonld)
- [Vocabulary](vocabulary/stadia-maps-vocabulary.yml)

### Stadia Maps Account Management API

The Stadia Maps Account Management API enables programmatic management of properties, domains, and API keys. Access is available on request.

**Base URL:** https://client.stadiamaps.com/api/v1

#### Properties

- [Documentation](https://docs.stadiamaps.com/client-api/)
- [OpenAPI](https://client.stadiamaps.com/api/v1/openapi/)

## Common Properties

- [Portal](https://stadiamaps.com/)
- [Documentation](https://docs.stadiamaps.com/)
- [API Reference](https://docs.stadiamaps.com/api-reference/)
- [Pricing](https://stadiamaps.com/pricing/)
- [Contact](https://stadiamaps.com/contact/)
- [Authentication](https://docs.stadiamaps.com/authentication/)
- [GitHub Organization](https://github.com/stadiamaps)
- [TypeScript SDK](https://www.npmjs.com/package/@stadiamaps/api)
- [Python SDK](https://pypi.org/project/stadiamaps-api/)

## Artifacts

### JSON Schema

- [Location Schema](json-schema/stadia-maps-location-schema.json)
- [Route Schema](json-schema/stadia-maps-route-schema.json)

### JSON Structure

- [Location Structure](json-structure/stadia-maps-location-structure.json)

### JSON-LD

- [Context](json-ld/stadia-maps-context.jsonld)

### Examples

- [Autocomplete](examples/stadia-maps-autocomplete-example.json)
- [Route](examples/stadia-maps-route-example.json)
- [Timezone Lookup](examples/stadia-maps-tz-lookup-example.json)

### Rules

- [Spectral Ruleset](rules/stadia-maps-rules.yml)

### Capabilities

- [Geospatial Services](capabilities/geospatial-services.yaml)
  - Shared: [Geospatial API](capabilities/shared/geospatial-api.yaml)

### Vocabulary

- [Stadia Maps Vocabulary](vocabulary/stadia-maps-vocabulary.yml)
