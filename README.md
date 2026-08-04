# Twitch (twitch)

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

Twitch is a live streaming platform for gamers, content creators, and communities.

**APIs.json:** [https://www.twitch.tv](https://www.twitch.tv)

## Tags

- Entertainment
- Gaming
- Live Video
- Streaming
- Video

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### Twitch API

The Twitch API enables developers to build experiences that integrate with Twitch, including retrieving stream data, managing users, and interacting with chat.

- **Human URL:** [https://dev.twitch.tv/](https://dev.twitch.tv/)
- **Base URL:** `https://api.twitch.tv/helix`

#### Tags

- Chat
- Gaming
- Streaming
- Video

#### Properties

- [Documentation](https://dev.twitch.tv/docs/api/)
- [OpenAPI](https://dev.twitch.tv/docs/api/reference) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://dev.twitch.tv/docs/authentication)
- [Getting Started](https://dev.twitch.tv/docs/api/get-started)
- [Rate Limits](https://dev.twitch.tv/docs/api/guide#rate-limits)
- [Webhooks](https://dev.twitch.tv/docs/eventsub)
- [A P I  Status](https://devstatus.twitch.tv/)
- [Terms of Service](https://www.twitch.tv/p/legal/terms-of-service/)
- [Privacy Policy](https://www.twitch.tv/p/legal/privacy-notice/)
- [Scopes](https://dev.twitch.tv/docs/authentication/scopes/)
- [Changelog](https://dev.twitch.tv/docs/change-log/)
- [Migration  Guide](https://dev.twitch.tv/docs/api/migration)
- [Concepts](https://dev.twitch.tv/docs/api/guide)
- [Clips](https://dev.twitch.tv/docs/api/clips)
- [Videos](https://dev.twitch.tv/docs/api/videos/)
- [OpenAPI](openapi/twitch-helix-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/twitch-helix.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/twitch-helix.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Twitch EventSub

EventSub is Twitch's webhook-based subscription service for receiving real-time notifications about events on Twitch.

- **Human URL:** [https://dev.twitch.tv/docs/eventsub](https://dev.twitch.tv/docs/eventsub)
- **Base URL:** `https://api.twitch.tv/helix/eventsub`

#### Tags

- Events
- Notifications
- Webhooks

#### Properties

- [Documentation](https://dev.twitch.tv/docs/eventsub)
- [Subscription  Types](https://dev.twitch.tv/docs/eventsub/eventsub-subscription-types)
- [Web Socket  Reference](https://dev.twitch.tv/docs/eventsub/websocket-reference/)
- [Handling  Web Socket  Events](https://dev.twitch.tv/docs/eventsub/handling-websocket-events/)
- [Handling  Conduit  Events](https://dev.twitch.tv/docs/eventsub/handling-conduit-events/)
- [AsyncAPI](asyncapi/twitch-eventsub-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/twitch-drops.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/twitch-drops.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/twitch-extensions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/twitch-extensions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/twitch-helix.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/twitch-helix.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/twitch-igdb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/twitch-igdb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/twitch-insights-analytics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/twitch-insights-analytics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/twitch-video-broadcast.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/twitch-video-broadcast.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Twitch Chat API

IRC and WebSocket-based APIs for integrating with Twitch chat.

- **Human URL:** [https://dev.twitch.tv/docs/chat](https://dev.twitch.tv/docs/chat)
- **Base URL:** `wss://irc-ws.chat.twitch.tv:443`

#### Tags

- Chat
- Irc
- Messaging
- Websocket

#### Properties

- [Documentation](https://dev.twitch.tv/docs/chat)
- [Chat  Commands](https://dev.twitch.tv/docs/irc/commands)
- [Chat  Badges](https://dev.twitch.tv/docs/irc/tags#privmsg-tags)
- [Authentication](https://dev.twitch.tv/docs/chat/authenticating/)
- [Postman Collection](collections/twitch-drops.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/twitch-drops.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/twitch-extensions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/twitch-extensions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/twitch-helix.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/twitch-helix.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/twitch-igdb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/twitch-igdb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/twitch-insights-analytics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/twitch-insights-analytics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/twitch-video-broadcast.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/twitch-video-broadcast.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Twitch Embed API

APIs for embedding Twitch live streams, video on demand, clips, and chat into external websites.

- **Human URL:** [https://dev.twitch.tv/docs/embed/](https://dev.twitch.tv/docs/embed/)
- **Base URL:** `https://embed.twitch.tv`

#### Tags

- Chat
- Clips
- Embed
- Player
- Video

#### Properties

- [Documentation](https://dev.twitch.tv/docs/embed/)
- [Video and  Clips](https://dev.twitch.tv/docs/embed/video-and-clips/)
- [Chat](https://dev.twitch.tv/docs/embed/chat/)
- [Everything](https://dev.twitch.tv/docs/embed/everything/)
- [Postman Collection](collections/twitch-drops.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/twitch-drops.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/twitch-extensions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/twitch-extensions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/twitch-helix.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/twitch-helix.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/twitch-igdb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/twitch-igdb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/twitch-insights-analytics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/twitch-insights-analytics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/twitch-video-broadcast.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/twitch-video-broadcast.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Twitch Extensions API

APIs for building interactive extensions that run as overlays or panels on Twitch channels, communicating via a sandboxed iframe.

- **Human URL:** [https://dev.twitch.tv/docs/extensions/](https://dev.twitch.tv/docs/extensions/)
- **Base URL:** `https://api.twitch.tv/helix/extensions`

#### Tags

- Extensions
- Interactive
- Overlays
- Panels

#### Properties

- [Documentation](https://dev.twitch.tv/docs/extensions/)
- [Building  Extensions](https://dev.twitch.tv/docs/extensions/building/)
- [Extensions  Reference](https://dev.twitch.tv/docs/extensions/reference/)
- [Frontend  A P I  Usage](https://dev.twitch.tv/docs/extensions/frontend-api-usage/)
- [OpenAPI](openapi/twitch-extensions-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/twitch-extensions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/twitch-extensions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Twitch Drops API

APIs for game developers to create and manage Drops campaigns that grant in-game rewards to Twitch viewers watching streamers play their game.

- **Human URL:** [https://dev.twitch.tv/docs/drops/](https://dev.twitch.tv/docs/drops/)
- **Base URL:** `https://api.twitch.tv/helix`

#### Tags

- Campaigns
- Drops
- Gaming
- Rewards

#### Properties

- [Documentation](https://dev.twitch.tv/docs/drops/)
- [Campaign  Guide](https://dev.twitch.tv/docs/drops/campaign-guide)
- [Technical  Guide](https://dev.twitch.tv/docs/drops/technical-guide/)
- [OpenAPI](openapi/twitch-drops-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/twitch-drops.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/twitch-drops.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Twitch Video Broadcast API

API for retrieving ingest server information used by broadcasters to send live video streams to Twitch via RTMP.

- **Human URL:** [https://dev.twitch.tv/docs/video-broadcast/](https://dev.twitch.tv/docs/video-broadcast/)
- **Base URL:** `https://ingest.twitch.tv`

#### Tags

- Broadcast
- Ingest
- Rtmp
- Streaming
- Video

#### Properties

- [Documentation](https://dev.twitch.tv/docs/video-broadcast/)
- [API Reference](https://dev.twitch.tv/docs/video-broadcast/reference/)
- [OpenAPI](openapi/twitch-video-broadcast-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/twitch-video-broadcast.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/twitch-video-broadcast.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Twitch Insights and Analytics API

APIs for accessing extension and game analytics data including views, clicks, hours watched, and concurrent streamers as downloadable CSV reports.

- **Human URL:** [https://dev.twitch.tv/docs/insights/](https://dev.twitch.tv/docs/insights/)
- **Base URL:** `https://api.twitch.tv/helix/analytics`

#### Tags

- Analytics
- Insights
- Metrics
- Reporting

#### Properties

- [Documentation](https://dev.twitch.tv/docs/insights/)
- [Dashboard](https://dev.twitch.tv/insights/)
- [OpenAPI](openapi/twitch-insights-analytics-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/twitch-insights-analytics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/twitch-insights-analytics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### IGDB API

The Internet Game Database API provides comprehensive video game information including metadata, ratings, and media, and is owned and operated by Twitch.

- **Human URL:** [https://api-docs.igdb.com/](https://api-docs.igdb.com/)
- **Base URL:** `https://api.igdb.com/v4`

#### Tags

- Database
- Games
- Metadata
- Ratings

#### Properties

- [Documentation](https://api-docs.igdb.com/)
- [Authentication](https://dev.twitch.tv/docs/authentication)
- [OpenAPI](openapi/twitch-igdb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/twitch-igdb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/twitch-igdb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/twitch-tv)
- [Developer  Portal](https://dev.twitch.tv/)
- [Console](https://dev.twitch.tv/console)
- [Blog](https://blog.twitch.tv/en/tags/developers/)
- [Git Hub](https://github.com/twitchdev)
- [Extensions](https://dev.twitch.tv/docs/extensions)
- [C L I  Tools](https://dev.twitch.tv/docs/cli)
- [Support](https://dev.twitch.tv/support/)
- [Forum](https://discuss.dev.twitch.com/)
- [Feedback](https://twitch.uservoice.com/forums/310213-developers)
- [Community  Resources](https://dev.twitch.tv/code/)
- [Products](https://dev.twitch.tv/products/)
- [Changelog](https://dev.twitch.tv/docs/change-log/)
- [Product  Lifecycle](https://dev.twitch.tv/docs/product-lifecycle/)
- [Authentication](https://dev.twitch.tv/docs/authentication)
- [Mobile  Deep  Links](https://dev.twitch.tv/docs/mobile-deeplinks/)
- [Game  Engine  Plugins](https://dev.twitch.tv/docs/game-engine-plugins/)
- [Terms of Service](https://www.twitch.tv/p/legal/terms-of-service/)
- [Privacy Policy](https://www.twitch.tv/p/legal/privacy-notice/)
- [JSON-LD](json-ld/twitch-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/twitch-stream-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/twitch-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/twitch-channel-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/twitch-clip-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/twitch-subscription-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/twitch-video-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/twitch-stream-structure.json)
- [JSON Structure](json-structure/twitch-channel-structure.json)
- [JSON Structure](json-structure/twitch-user-structure.json)
- [Vocabulary](vocabulary/twitch-vocabulary.yml)
- [Spectral Rules](rules/twitch-rules.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
