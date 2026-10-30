# Flickr

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

Flickr is the long-running photo, group, people, place, tag, gallery, photoset, and Commons platform now owned by SmugMug. Its REST-like API dispatches every operation through a single endpoint (https://api.flickr.com/services/rest?method=flickr.{namespace}.{method}), spanning ~250 methods across 30 namespaces — covering activity, auth, blogs, cameras, collections, commons, contacts, favorites, galleries, groups, group discussions, interestingness, machine tags, panda, people, photos (plus photos.geo / photos.licenses / photos.notes / photos.transform / photos.upload), photosets, places, prefs, profile, push, reflection, stats, tags, test, and URLs. Authentication is API key + OAuth 1.0a (HMAC-SHA1). Commercial use requires a permission-granted commercial key.

**Areas:** Photography · Photos · Social Media · Public APIs

## Flickr on APIs.io

Everything profiled for Flickr is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/flickr/](https://apis.io/providers/flickr/)** — or go straight to one of the APIs or properties below.

### APIs (32)

- [Flickr Activity API](https://apis.io/apis/flickr/flickr-activity-api/) — Recent activity on the calling user's photos and contacts
- [Flickr Auth API](https://apis.io/apis/flickr/flickr-auth-api/) — OAuth 1.0a token exchange
- [Flickr Blogs API](https://apis.io/apis/flickr/flickr-blogs-api/) — Configured blogs and posting to them
- [Flickr Cameras API](https://apis.io/apis/flickr/flickr-cameras-api/) — Camera brand and model metadata
- [Flickr Collections API](https://apis.io/apis/flickr/flickr-collections-api/) — Hierarchical collections of photosets
- [Flickr Commons API](https://apis.io/apis/flickr/flickr-commons-api/) — Flickr Commons institutions
- [Flickr Contacts API](https://apis.io/apis/flickr/flickr-contacts-api/) — Calling user's contacts and recent contact activity
- [Flickr Favorites API](https://apis.io/apis/flickr/flickr-favorites-api/) — Photos a user has marked as favorites
- [Flickr Galleries API](https://apis.io/apis/flickr/flickr-galleries-api/) — Curated, themed galleries of photos
- [Flickr Groups API](https://apis.io/apis/flickr/flickr-groups-api/) — Group metadata, membership, and pool management
- [Flickr Groups Discuss API](https://apis.io/apis/flickr/flickr-groups-discuss-api/) — Group discussion topics and replies
- [Flickr Interestingness API](https://apis.io/apis/flickr/flickr-interestingness-api/) — The day's most interesting photos
- [Flickr Machine Tags API](https://apis.io/apis/flickr/flickr-machine-tags-api/) — Namespace, predicate, and value lookups for machine tags
- [Flickr Panda API](https://apis.io/apis/flickr/flickr-panda-api/) — The Flickr Panda firehose of "interesting" photos
- [Flickr People API](https://apis.io/apis/flickr/flickr-people-api/) — People (users), their info, public photos, and groups
- [Flickr Photos API](https://apis.io/apis/flickr/flickr-photos-api/) — Core photo metadata, search, comments, and lifecycle
- [Flickr Photos Geo API](https://apis.io/apis/flickr/flickr-photos-geo-api/) — Geotagging photos with latitude/longitude
- [Flickr Photos Licenses API](https://apis.io/apis/flickr/flickr-photos-licenses-api/) — License catalog and per-photo license assignment
- [Flickr Photos Notes API](https://apis.io/apis/flickr/flickr-photos-notes-api/) — Notes drawn on photos
- [Flickr Photos Transform API](https://apis.io/apis/flickr/flickr-photos-transform-api/) — Rotate photos server-side
- [Flickr Photos Upload API](https://apis.io/apis/flickr/flickr-photos-upload-api/) — Asynchronous upload status polling
- [Flickr Photosets API](https://apis.io/apis/flickr/flickr-photosets-api/) — Photo albums (photosets)
- [Flickr Places API](https://apis.io/apis/flickr/flickr-places-api/) — Place IDs, hierarchies, and resolution
- [Flickr Prefs API](https://apis.io/apis/flickr/flickr-prefs-api/) — Calling user's posting preferences
- [Flickr Profile API](https://apis.io/apis/flickr/flickr-profile-api/) — User profile fields
- [Flickr Public API](https://apis.io/apis/flickr/flickr-public-api/) — The Public API from Flickr — 25 operation(s) for public.
- [Flickr Push API](https://apis.io/apis/flickr/flickr-push-api/) — PubSubHubbub push subscriptions
- [Flickr Reflection API](https://apis.io/apis/flickr/flickr-reflection-api/) — Programmatic discovery of available API methods
- [Flickr Stats API](https://apis.io/apis/flickr/flickr-stats-api/) — View counts and referrers for photos/photosets/collections
- [Flickr Tags API](https://apis.io/apis/flickr/flickr-tags-api/) — Tag clusters, hot lists, and tag-based lookups
- [Flickr Test API](https://apis.io/apis/flickr/flickr-test-api/) — Echo, login, and null test methods
- [Flickr URLs API](https://apis.io/apis/flickr/flickr-urls-api/) — Look up Flickr URLs by user, group, gallery

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Flickr Agentic Access](https://apis.io/agentic-access/flickr/flickr-agentic-access/)

#### JSON Schema (58)

The data models the API reads and writes.

- [ActivityItem](https://apis.io/schemas/flickr/flickr-activity-item/)
- [ActivityList](https://apis.io/schemas/flickr/flickr-activity-list/)
- [Blog](https://apis.io/schemas/flickr/flickr-blog/)
- [BlogList](https://apis.io/schemas/flickr/flickr-blog-list/)
- [Brand](https://apis.io/schemas/flickr/flickr-brand/)
- [BrandList](https://apis.io/schemas/flickr/flickr-brand-list/)
- [Camera](https://apis.io/schemas/flickr/flickr-camera/)
- [CameraList](https://apis.io/schemas/flickr/flickr-camera-list/)
- [Collection](https://apis.io/schemas/flickr/flickr-collection/)
- [CollectionTree](https://apis.io/schemas/flickr/flickr-collection-tree/)
- [Contact](https://apis.io/schemas/flickr/flickr-contact/)
- [ContactList](https://apis.io/schemas/flickr/flickr-contact-list/)
- [EchoResponse](https://apis.io/schemas/flickr/flickr-echo-response/)
- [Exif](https://apis.io/schemas/flickr/flickr-exif/)
- [ExifList](https://apis.io/schemas/flickr/flickr-exif-list/)
- [Gallery](https://apis.io/schemas/flickr/flickr-gallery/)
- [GalleryList](https://apis.io/schemas/flickr/flickr-gallery-list/)
- [Group](https://apis.io/schemas/flickr/flickr-group/)
- [GroupList](https://apis.io/schemas/flickr/flickr-group-list/)
- [Institution](https://apis.io/schemas/flickr/flickr-institution/)
- [InstitutionList](https://apis.io/schemas/flickr/flickr-institution-list/)
- [License](https://apis.io/schemas/flickr/flickr-license/)
- [LicenseList](https://apis.io/schemas/flickr/flickr-license-list/)
- [LoginInfo](https://apis.io/schemas/flickr/flickr-login-info/)
- [MachineTagNamespace](https://apis.io/schemas/flickr/flickr-machine-tag-namespace/)
- …and 33 more published on APIs.io

#### JSON Structure (58)

Data models expressed in JSON Structure.

- [Flickr Activity Item Structure](https://apis.io/json-structure/flickr/flickr-activity-item-structure/)
- [Flickr Activity List Structure](https://apis.io/json-structure/flickr/flickr-activity-list-structure/)
- [Flickr Blog List Structure](https://apis.io/json-structure/flickr/flickr-blog-list-structure/)
- [Flickr Blog Structure](https://apis.io/json-structure/flickr/flickr-blog-structure/)
- [Flickr Brand List Structure](https://apis.io/json-structure/flickr/flickr-brand-list-structure/)
- [Flickr Brand Structure](https://apis.io/json-structure/flickr/flickr-brand-structure/)
- [Flickr Camera List Structure](https://apis.io/json-structure/flickr/flickr-camera-list-structure/)
- [Flickr Camera Structure](https://apis.io/json-structure/flickr/flickr-camera-structure/)
- [Flickr Collection Structure](https://apis.io/json-structure/flickr/flickr-collection-structure/)
- [Flickr Collection Tree Structure](https://apis.io/json-structure/flickr/flickr-collection-tree-structure/)
- [Flickr Contact List Structure](https://apis.io/json-structure/flickr/flickr-contact-list-structure/)
- [Flickr Contact Structure](https://apis.io/json-structure/flickr/flickr-contact-structure/)
- [Flickr Echo Response Structure](https://apis.io/json-structure/flickr/flickr-echo-response-structure/)
- [Flickr Exif List Structure](https://apis.io/json-structure/flickr/flickr-exif-list-structure/)
- [Flickr Exif Structure](https://apis.io/json-structure/flickr/flickr-exif-structure/)
- [Flickr Gallery List Structure](https://apis.io/json-structure/flickr/flickr-gallery-list-structure/)
- [Flickr Gallery Structure](https://apis.io/json-structure/flickr/flickr-gallery-structure/)
- [Flickr Group List Structure](https://apis.io/json-structure/flickr/flickr-group-list-structure/)
- [Flickr Group Structure](https://apis.io/json-structure/flickr/flickr-group-structure/)
- [Flickr Institution List Structure](https://apis.io/json-structure/flickr/flickr-institution-list-structure/)
- [Flickr Institution Structure](https://apis.io/json-structure/flickr/flickr-institution-structure/)
- [Flickr License List Structure](https://apis.io/json-structure/flickr/flickr-license-list-structure/)
- [Flickr License Structure](https://apis.io/json-structure/flickr/flickr-license-structure/)
- [Flickr Login Info Structure](https://apis.io/json-structure/flickr/flickr-login-info-structure/)
- [Flickr Machine Tag Namespace List Structure](https://apis.io/json-structure/flickr/flickr-machine-tag-namespace-list-structure/)
- …and 33 more published on APIs.io

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Flickr Context](https://apis.io/jsonld/flickr/flickr-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Flickr Vocabulary](https://apis.io/vocabularies/flickr/flickr-vocabulary/)

#### Examples (58)

Example requests and responses.

- [Flickr Activity Item Example](https://apis.io/examples/flickr/flickr-activity-item-example/)
- [Flickr Activity List Example](https://apis.io/examples/flickr/flickr-activity-list-example/)
- [Flickr Blog Example](https://apis.io/examples/flickr/flickr-blog-example/)
- [Flickr Blog List Example](https://apis.io/examples/flickr/flickr-blog-list-example/)
- [Flickr Brand Example](https://apis.io/examples/flickr/flickr-brand-example/)
- [Flickr Brand List Example](https://apis.io/examples/flickr/flickr-brand-list-example/)
- [Flickr Camera Example](https://apis.io/examples/flickr/flickr-camera-example/)
- [Flickr Camera List Example](https://apis.io/examples/flickr/flickr-camera-list-example/)
- [Flickr Collection Example](https://apis.io/examples/flickr/flickr-collection-example/)
- [Flickr Collection Tree Example](https://apis.io/examples/flickr/flickr-collection-tree-example/)
- [Flickr Contact Example](https://apis.io/examples/flickr/flickr-contact-example/)
- [Flickr Contact List Example](https://apis.io/examples/flickr/flickr-contact-list-example/)
- [Flickr Echo Response Example](https://apis.io/examples/flickr/flickr-echo-response-example/)
- [Flickr Exif Example](https://apis.io/examples/flickr/flickr-exif-example/)
- [Flickr Exif List Example](https://apis.io/examples/flickr/flickr-exif-list-example/)
- [Flickr Gallery Example](https://apis.io/examples/flickr/flickr-gallery-example/)
- [Flickr Gallery List Example](https://apis.io/examples/flickr/flickr-gallery-list-example/)
- [Flickr Group Example](https://apis.io/examples/flickr/flickr-group-example/)
- [Flickr Group List Example](https://apis.io/examples/flickr/flickr-group-list-example/)
- [Flickr Institution Example](https://apis.io/examples/flickr/flickr-institution-example/)
- [Flickr Institution List Example](https://apis.io/examples/flickr/flickr-institution-list-example/)
- [Flickr License Example](https://apis.io/examples/flickr/flickr-license-example/)
- [Flickr License List Example](https://apis.io/examples/flickr/flickr-license-list-example/)
- [Flickr Login Info Example](https://apis.io/examples/flickr/flickr-login-info-example/)
- [Flickr Machine Tag Namespace Example](https://apis.io/examples/flickr/flickr-machine-tag-namespace-example/)
- …and 33 more published on APIs.io

#### Collections (65)

Postman and Open Collection request collections.

- [Flickr API](https://apis.io/collections/flickr/open-flickr/)
- [Flickr Activity API](https://apis.io/collections/flickr/open-flickr-activity-api/)
- [Flickr Activity Auth API](https://apis.io/collections/flickr/open-flickr-auth-api/)
- [Flickr Activity Blogs API](https://apis.io/collections/flickr/open-flickr-blogs-api/)
- [Flickr Activity Cameras API](https://apis.io/collections/flickr/open-flickr-cameras-api/)
- [Flickr Activity Collections API](https://apis.io/collections/flickr/open-flickr-collections-api/)
- [Flickr Activity Commons API](https://apis.io/collections/flickr/open-flickr-commons-api/)
- [Flickr Activity Contacts API](https://apis.io/collections/flickr/open-flickr-contacts-api/)
- [Flickr Activity Favorites API](https://apis.io/collections/flickr/open-flickr-favorites-api/)
- [Flickr Activity Galleries API](https://apis.io/collections/flickr/open-flickr-galleries-api/)
- [Flickr Activity Groups API](https://apis.io/collections/flickr/open-flickr-groups-api/)
- [Flickr Activity Groups Discuss API](https://apis.io/collections/flickr/open-flickr-groups-discuss-api/)
- [Flickr Activity Interestingness API](https://apis.io/collections/flickr/open-flickr-interestingness-api/)
- [Flickr Activity Machine Tags API](https://apis.io/collections/flickr/open-flickr-machine-tags-api/)
- [Flickr Activity Panda API](https://apis.io/collections/flickr/open-flickr-panda-api/)
- [Flickr Activity People API](https://apis.io/collections/flickr/open-flickr-people-api/)
- [Flickr Activity Photos API](https://apis.io/collections/flickr/open-flickr-photos-api/)
- [Flickr Activity Photos Geo API](https://apis.io/collections/flickr/open-flickr-photos-geo-api/)
- [Flickr Activity Photos Licenses API](https://apis.io/collections/flickr/open-flickr-photos-licenses-api/)
- [Flickr Activity Photos Notes API](https://apis.io/collections/flickr/open-flickr-photos-notes-api/)
- [Flickr Activity Photos Transform API](https://apis.io/collections/flickr/open-flickr-photos-transform-api/)
- [Flickr Activity Photos Upload API](https://apis.io/collections/flickr/open-flickr-photos-upload-api/)
- [Flickr Activity Photosets API](https://apis.io/collections/flickr/open-flickr-photosets-api/)
- [Flickr Activity Places API](https://apis.io/collections/flickr/open-flickr-places-api/)
- [Flickr Activity Prefs API](https://apis.io/collections/flickr/open-flickr-prefs-api/)
- …and 40 more published on APIs.io

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Flickr — jsonschema rules](https://apis.io/rules/flickr/flickr-jsonschema-spectral-rules/)
- [Flickr API Rules](https://apis.io/rules/flickr/flickr-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Flickr Authentication](https://apis.io/security/flickr/flickr-authentication/)
- [Flickr Domain Security](https://apis.io/security/flickr/flickr-domain-security/)
- [Flickr Vulnerability Disclosure](https://apis.io/security/flickr/flickr-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Flickr Scopes](https://apis.io/scopes/flickr/flickr-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Flickr Plans Pricing](https://apis.io/plans/flickr/flickr-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Flickr Rate Limits](https://apis.io/rate-limits/flickr/flickr-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Flickr Finops](https://apis.io/finops/flickr/flickr-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.flickr.com/)
- [Getting started](https://www.flickr.com/services/developer/)
- [Pricing](https://www.flickr.com/services/api/misc.api_keys.html)
- [Support](https://flickrhelp.com/)
- [Changelog](https://www.flickr.com/services/developer/changelog/)
- [Blog](https://blog.flickr.net/)
- [Terms of service](https://www.flickr.com/services/api/tos/)
- [Privacy policy](https://www.flickr.com/help/privacy)
- [GitHub](https://github.com/flickr)
- [Status](https://www.flickr.com/)

## API Evangelist rating

**Kin Score 49.7** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 64.3 |
| Contract quality | 20.4 |
| Contract governance | 27.3 |
| Operational transparency | 52.6 |
| Developer ergonomics | 75.0 |
| Access clarity | 50.0 |

**Agent readiness 25.6** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | mostly |

**Regulatory alignment 40.2** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/flickr/](https://apis.io/providers/flickr/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Flickr: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/flickr/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
