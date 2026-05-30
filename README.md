# Flickr (flickr)

Flickr is the long-running photo, group, people, place, tag, gallery, photoset, and Commons platform now owned by SmugMug. Its REST-like API dispatches every operation through a single endpoint (`https://api.flickr.com/services/rest?method=flickr.{namespace}.{method}`), spanning ~250 methods across 30 namespaces — covering activity, auth, blogs, cameras, collections, commons, contacts, favorites, galleries, groups, group discussions, interestingness, machine tags, panda, people, photos (plus photos.geo / photos.licenses / photos.notes / photos.transform / photos.upload), photosets, places, prefs, profile, push, reflection, stats, tags, test, and URLs. Authentication is API key + OAuth 1.0a (HMAC-SHA1). Commercial use requires a permission-granted commercial key.

**URL:** [Visit APIs.json URL](https://www.flickr.com/services/api/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- Photography, Photos, Social Media, Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### Flickr API

The full Flickr REST API. Method-dispatched single-endpoint API: every call is `GET/POST https://api.flickr.com/services/rest?method=flickr.{namespace}.{method}`. Uploads use a separate `https://up.flickr.com/services/upload` endpoint. Coverage profiled here: ~30 most-important methods across all 30 method namespaces.

**Human URL:** [https://www.flickr.com/services/api/](https://www.flickr.com/services/api/)

**Base URL:** `https://api.flickr.com/services`

#### Tags

- Photography, Photos

#### Properties

- [Documentation](https://www.flickr.com/services/api/)
- [API Reference](https://www.flickr.com/services/api/)
- [OpenAPI](openapi/flickr-openapi.yml)
- [Authentication](https://www.flickr.com/services/api/auth.oauth.html)
- [Quickstart](https://www.flickr.com/services/developer/)
- [SDK — Node.js](https://www.npmjs.com/package/flickr-sdk)
- [SDK — Node.js source](https://github.com/flickr/flickr-sdk)
- [SDK — Python (flickr-api)](https://pypi.org/project/flickr-api/)

#### Naftiko Capabilities

| Capability | File |
|------------|------|
| Activity | [flickr-activity.yaml](capabilities/flickr-activity.yaml) |
| Auth | [flickr-auth.yaml](capabilities/flickr-auth.yaml) |
| Blogs | [flickr-blogs.yaml](capabilities/flickr-blogs.yaml) |
| Cameras | [flickr-cameras.yaml](capabilities/flickr-cameras.yaml) |
| Collections | [flickr-collections.yaml](capabilities/flickr-collections.yaml) |
| Commons | [flickr-commons.yaml](capabilities/flickr-commons.yaml) |
| Contacts | [flickr-contacts.yaml](capabilities/flickr-contacts.yaml) |
| Favorites | [flickr-favorites.yaml](capabilities/flickr-favorites.yaml) |
| Galleries | [flickr-galleries.yaml](capabilities/flickr-galleries.yaml) |
| Groups | [flickr-groups.yaml](capabilities/flickr-groups.yaml) |
| Groups Discuss | [flickr-groups-discuss.yaml](capabilities/flickr-groups-discuss.yaml) |
| Interestingness | [flickr-interestingness.yaml](capabilities/flickr-interestingness.yaml) |
| Machine Tags | [flickr-machine-tags.yaml](capabilities/flickr-machine-tags.yaml) |
| Panda | [flickr-panda.yaml](capabilities/flickr-panda.yaml) |
| People | [flickr-people.yaml](capabilities/flickr-people.yaml) |
| Photos | [flickr-photos.yaml](capabilities/flickr-photos.yaml) |
| Photos Geo | [flickr-photos-geo.yaml](capabilities/flickr-photos-geo.yaml) |
| Photos Licenses | [flickr-photos-licenses.yaml](capabilities/flickr-photos-licenses.yaml) |
| Photos Notes | [flickr-photos-notes.yaml](capabilities/flickr-photos-notes.yaml) |
| Photos Transform | [flickr-photos-transform.yaml](capabilities/flickr-photos-transform.yaml) |
| Photos Upload | [flickr-photos-upload.yaml](capabilities/flickr-photos-upload.yaml) |
| Photosets | [flickr-photosets.yaml](capabilities/flickr-photosets.yaml) |
| Places | [flickr-places.yaml](capabilities/flickr-places.yaml) |
| Prefs | [flickr-prefs.yaml](capabilities/flickr-prefs.yaml) |
| Profile | [flickr-profile.yaml](capabilities/flickr-profile.yaml) |
| Push | [flickr-push.yaml](capabilities/flickr-push.yaml) |
| Reflection | [flickr-reflection.yaml](capabilities/flickr-reflection.yaml) |
| Stats | [flickr-stats.yaml](capabilities/flickr-stats.yaml) |
| Tags | [flickr-tags.yaml](capabilities/flickr-tags.yaml) |
| Test | [flickr-test.yaml](capabilities/flickr-test.yaml) |
| URLs | [flickr-urls.yaml](capabilities/flickr-urls.yaml) |

## Common Properties

- [Website](https://www.flickr.com/)
- [Portal](https://www.flickr.com/services/api/)
- [Getting Started](https://www.flickr.com/services/developer/)
- [Sign Up](https://www.flickr.com/services/apps/create/apply/)
- [Terms of Service](https://www.flickr.com/services/api/tos/)
- [Privacy Policy](https://www.flickr.com/help/privacy)
- [Pricing](https://www.flickr.com/services/api/misc.api_keys.html)
- [Blog](https://blog.flickr.net/)
- [ChangeLog](https://www.flickr.com/services/developer/changelog/)
- [FAQ](https://flickrhelp.com/)
- [Support](https://flickrhelp.com/)
- [GitHub Organization](https://github.com/flickr)
- [GitHub Repository — Flickr API Swagger](https://github.com/flickr/flickr-api-swagger)
- [PublicAPIsListing](https://github.com/public-apis/public-apis)
- [Spectral Rules](rules/flickr-rules.yml)
- [Vocabulary](vocabulary/flickr-vocabulary.yml)
- [JSON-LD](json-ld/flickr-context.jsonld)
- [Plans](plans/flickr-plans-pricing.yml)
- [Rate Limits](rate-limits/flickr-rate-limits.yml)
- [FinOps](finops/flickr-finops.yml)

## Features

| Name | Description |
|------|-------------|
| Method-Dispatched REST API | Single endpoint with `method=flickr.{namespace}.{method}` selector covering 250+ methods across 30 namespaces. |
| Photo Search | Rich text/tag/geo/license/date/content-filter search across the public photo corpus. |
| OAuth 1.0a Authentication | HMAC-SHA1 three-legged OAuth flow for accessing user-owned content. |
| Sync + Async Photo Upload | Multipart upload endpoint with synchronous or ticket-based asynchronous status polling. |
| PubSubHubbub Push | Push subscriptions for change-driven workloads instead of polling. |
| Reflection | flickr.reflection.getMethods and getMethodInfo for programmatic API discovery. |
| Flickr Commons | Institutional partner program (museums, libraries, archives) with no-known-copyright photos. |
| Geotagging | Lat/lon attachment plus Places (WOEID) resolution. |
| Machine Tags | Structured namespace.predicate=value tagging for machine-readable taxonomies. |
| Stats | Per-day view/comment/favorite counts for owned content. |

## Use Cases

| Name | Description |
|------|-------------|
| Photo-Powered App | Build a third-party app that searches, displays, or remixes the public Flickr photo corpus. |
| Photo Backup / Sync | Bulk-upload pipeline pushing a user's photos into Flickr (or pulling them out). |
| Curator Tooling | Editorial workflows that build galleries, photosets, and collections programmatically. |
| Community Bot | Group moderation, topic listing, and reply harvesting for community managers. |
| Cultural Heritage Research | Access Flickr Commons institutional collections for research or aggregation. |
| Geo-Photo Analytics | Map-based analytics over the geotagged photo corpus by place / WOEID. |
| Discovery / Recommendation | Interestingness and Panda feeds plus tag clusters for content-discovery surfaces. |

## Integrations

| Name | Description |
|------|-------------|
| PubSubHubbub | Push subscription protocol used by `flickr.push.*` topics. |
| OAuth 1.0a | Industry-standard delegated-authorization protocol used for all user-context calls. |
| Blogger / WordPress | Configured blog services available through `flickr.blogs.*` for cross-posting from Flickr. |
| SmugMug | Parent company; account ecosystem and import/export flows. |
| Yahoo Login (legacy) | Historic Yahoo-account login path now superseded by direct Flickr accounts. |

## Solutions

| Name | Description |
|------|-------------|
| Non-Commercial API Key | Free API key for personal/non-commercial apps; standard online sign-up. |
| Commercial API Key | Permission-only commercial API key reviewed individually by Flickr. |
| Flickr Pro (consumer) | Consumer-side paid Flickr account (out of scope for API pricing). |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Flickr API](openapi/flickr-openapi.yml) — 53 paths, 61 schemas, covering all 30 Flickr method namespaces.

### JSON Schema

58 standalone JSON Schema (Draft 2020-12) files extracted from the OpenAPI components, one per resource. Located in [json-schema/](json-schema/).

### JSON Structure

58 JSON Structure (json-structure.org) files, derived 1:1 from the JSON Schemas. Located in [json-structure/](json-structure/).

### JSON-LD

- [Flickr JSON-LD Context](json-ld/flickr-context.jsonld) — 58 type declarations and 137 property term mappings aligned with schema.org / Dublin Core / XSD.

### Examples

58 representative example payloads, one per JSON Schema. Located in [examples/](examples/).

## Capabilities

31 self-contained Naftiko capability files in [capabilities/](capabilities/), one per Flickr method namespace. Every file declares both a REST exposer (port 8080) and an MCP exposer (port 9090) routed inline through that capability's own `consumes` block.

## Vocabulary

- [Flickr Vocabulary](vocabulary/flickr-vocabulary.yml) — Unified taxonomy mapping 10 core resources, 9 actions, 31 capability workflows, and 14 personas across operational (OpenAPI) and capability (Naftiko) dimensions.

## Rules

- [Flickr Spectral Ruleset](rules/flickr-rules.yml) — 32 rules across info, paths, operations, tags, parameters, request bodies, responses, schemas, security, HTTP-method, and Microcks categories enforcing Flickr API conventions.

## Plans

- [Flickr Plans + Pricing](plans/flickr-plans-pricing.yml) — Free Non-Commercial API Key and permission-only Commercial API Key, modelled per API Commons Plans 0.1.

## Rate Limits

- [Flickr Rate Limits](rate-limits/flickr-rate-limits.yml) — Per-key 3,600 queries/hour for non-commercial keys, negotiated ceiling for commercial keys, with documented backoff and push-vs-polling policies, modelled per API Commons Rate Limits 0.1.

## FinOps

- [Flickr FinOps](finops/flickr-finops.yml) — FOCUS-aligned FinOps view of the (zero-cost) API surface, with client-side meters for `api_requests`, `photos_uploaded`, `upload_bytes`, `push_subscriptions`, and `oauth_users`.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
