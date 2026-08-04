# Flickr (flickr)

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

Flickr is the long-running photo, group, people, place, tag, gallery, photoset, and Commons platform now owned by SmugMug. Its REST-like API dispatches every operation through a single endpoint (https://api.flickr.com/services/rest?method=flickr.{namespace}.{method}), spanning ~250 methods across 30 namespaces — covering activity, auth, blogs, cameras, collections, commons, contacts, favorites, galleries, groups, group discussions, interestingness, machine tags, panda, people, photos (plus photos.geo / photos.licenses / photos.notes / photos.transform / photos.upload), photosets, places, prefs, profile, push, reflection, stats, tags, test, and URLs. Authentication is API key + OAuth 1.0a (HMAC-SHA1). Commercial use requires a permission-granted commercial key.

**APIs.json:** [https://www.flickr.com/services/api/](https://www.flickr.com/services/api/)

## Tags

- Photography
- Photos
- Social Media
- Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### Flickr API

The full Flickr REST API. Method-dispatched single-endpoint API: every call is `GET/POST https://api.flickr.com/services/rest?method=flickr.{namespace}.{method}`. Uploads use a separate `https://up.flickr.com/services/upload` endpoint. Coverage profiled here: ~30 most-important methods across all 30 method namespaces (activity, auth, blogs, cameras, collections, commons, contacts, favorites, galleries, groups, groupsDiscuss, interestingness, machinetags, panda, people, photos, photos.geo, photos.licenses, photos.notes, photos.transform, photos.upload, photosets, places, prefs, profile, push, reflection, stats, tags, test, urls).

- **Human URL:** [https://www.flickr.com/services/api/](https://www.flickr.com/services/api/)
- **Base URL:** `https://api.flickr.com/services`

#### Tags

- Photography
- Photos

#### Properties

- [Documentation](https://www.flickr.com/services/api/)
- [API Reference](https://www.flickr.com/services/api/)
- [OpenAPI](openapi/flickr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flickr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flickr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://www.flickr.com/services/api/auth.oauth.html)
- [Quickstart](https://www.flickr.com/services/developer/)
- [SDK](https://www.npmjs.com/package/flickr-sdk)
- [SDK](https://github.com/flickr/flickr-sdk)
- [SDK](https://pypi.org/project/flickr-api/)

## Common Properties

- [Website](https://www.flickr.com/)
- [Portal](https://www.flickr.com/services/api/)
- [Getting Started](https://www.flickr.com/services/developer/)
- [Sign Up](https://www.flickr.com/services/apps/create/apply/)
- [Terms of Service](https://www.flickr.com/services/api/tos/)
- [Privacy Policy](https://www.flickr.com/help/privacy)
- [Pricing](https://www.flickr.com/services/api/misc.api_keys.html)
- [Blog](https://blog.flickr.net/)
- [Changelog](https://www.flickr.com/services/developer/changelog/)
- [F A Q](https://flickrhelp.com/)
- [Support](https://flickrhelp.com/)
- [Status Page](https://www.flickr.com/)
- [GitHub Organization](https://github.com/flickr)
- [GitHub Repository](https://github.com/flickr/flickr-api-swagger)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [Spectral Rules](rules/flickr-rules.yml)
- [Vocabulary](vocabulary/flickr-vocabulary.yml)
- [J S O N- L D](json-ld/flickr-context.jsonld)
- [Plans](plans/flickr-plans-pricing.yml)
- [Rate Limits](rate-limits/flickr-rate-limits.yml)
- [Fin Ops](finops/flickr-finops.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
