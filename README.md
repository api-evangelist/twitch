# Twitch

Twitch is a live streaming platform for gamers, content creators, and communities. The Twitch developer ecosystem provides APIs for building integrations ranging from chatbots to game overlays, stream management tools, analytics dashboards, and real-time event-driven applications.

**URL:** [https://dev.twitch.tv/](https://dev.twitch.tv/)

## Tags

Entertainment, Gaming, Live Video, Streaming, Video

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-03

## APIs

### Twitch API (Helix)

The primary Twitch REST API providing access to streams, users, channels, clips, videos, chat, subscriptions, moderation, polls, predictions, raids, schedules, and analytics.

**Human URL:** [https://dev.twitch.tv/](https://dev.twitch.tv/)
**Base URL:** https://api.twitch.tv/helix

**Tags:** Chat, Gaming, Streaming, Video

**Properties**
- [Documentation](https://dev.twitch.tv/docs/api/)
- [OpenAPI](openapi/twitch-helix-openapi.yml)
- [Authentication](https://dev.twitch.tv/docs/authentication)
- [Getting Started](https://dev.twitch.tv/docs/api/get-started)
- [Rate Limits](https://dev.twitch.tv/docs/api/guide#rate-limits)
- [Scopes](https://dev.twitch.tv/docs/authentication/scopes/)
- [Change Log](https://dev.twitch.tv/docs/change-log/)
- [Migration Guide](https://dev.twitch.tv/docs/api/migration)

### Twitch EventSub

EventSub is Twitch's subscription service for receiving real-time notifications about platform events via webhooks or WebSocket connections.

**Human URL:** [https://dev.twitch.tv/docs/eventsub](https://dev.twitch.tv/docs/eventsub)

**Tags:** Events, Notifications, Webhooks

**Properties**
- [Documentation](https://dev.twitch.tv/docs/eventsub)
- [AsyncAPI](asyncapi/twitch-eventsub-asyncapi.yml)
- [Subscription Types](https://dev.twitch.tv/docs/eventsub/eventsub-subscription-types)
- [WebSocket Reference](https://dev.twitch.tv/docs/eventsub/websocket-reference/)

### Twitch Extensions API

APIs for building interactive extensions that run as overlays or panels on Twitch channels, communicating via a sandboxed iframe.

**Human URL:** [https://dev.twitch.tv/docs/extensions/](https://dev.twitch.tv/docs/extensions/)

**Tags:** Extensions, Interactive, Overlays, Panels

**Properties**
- [Documentation](https://dev.twitch.tv/docs/extensions/)
- [OpenAPI](openapi/twitch-extensions-openapi.yml)

### Twitch Drops API

APIs for game developers to create and manage Drops campaigns that grant in-game rewards to Twitch viewers.

**Human URL:** [https://dev.twitch.tv/docs/drops/](https://dev.twitch.tv/docs/drops/)

**Tags:** Campaigns, Drops, Gaming, Rewards

**Properties**
- [Documentation](https://dev.twitch.tv/docs/drops/)
- [OpenAPI](openapi/twitch-drops-openapi.yml)

### Twitch Video Broadcast API

API for retrieving ingest server information used by broadcasters to send live video to Twitch via RTMP.

**Human URL:** [https://dev.twitch.tv/docs/video-broadcast/](https://dev.twitch.tv/docs/video-broadcast/)

**Tags:** Broadcast, Ingest, Rtmp, Streaming, Video

**Properties**
- [Documentation](https://dev.twitch.tv/docs/video-broadcast/)
- [OpenAPI](openapi/twitch-video-broadcast-openapi.yml)

### Twitch Insights and Analytics API

APIs for accessing extension and game analytics data as downloadable reports.

**Human URL:** [https://dev.twitch.tv/docs/insights/](https://dev.twitch.tv/docs/insights/)

**Tags:** Analytics, Insights, Metrics, Reporting

**Properties**
- [Documentation](https://dev.twitch.tv/docs/insights/)
- [OpenAPI](openapi/twitch-insights-analytics-openapi.yml)

### IGDB API

The Internet Game Database API provides comprehensive video game information including metadata, ratings, and media. Owned and operated by Twitch.

**Human URL:** [https://api-docs.igdb.com/](https://api-docs.igdb.com/)

**Tags:** Database, Games, Metadata, Ratings

**Properties**
- [Documentation](https://api-docs.igdb.com/)
- [OpenAPI](openapi/twitch-igdb-openapi.yml)

## Common Properties

- [Developer Portal](https://dev.twitch.tv/)
- [Console](https://dev.twitch.tv/console)
- [Blog](https://blog.twitch.tv/en/tags/developers/)
- [GitHub](https://github.com/twitchdev)
- [Extensions](https://dev.twitch.tv/docs/extensions)
- [CLI Tools](https://dev.twitch.tv/docs/cli)
- [Support](https://dev.twitch.tv/support/)
- [Forum](https://discuss.dev.twitch.com/)
- [Terms of Service](https://www.twitch.tv/p/legal/terms-of-service/)
- [Privacy Policy](https://www.twitch.tv/p/legal/privacy-notice/)

## Artifacts

### JSON Schemas

| Schema | Description |
|---|---|
| [Stream](json-schema/twitch-stream-schema.json) | Live stream object |
| [User](json-schema/twitch-user-schema.json) | Twitch user |
| [Channel](json-schema/twitch-channel-schema.json) | Broadcaster channel |
| [Clip](json-schema/twitch-clip-schema.json) | Video clip |
| [Subscription](json-schema/twitch-subscription-schema.json) | Channel subscription |
| [Video](json-schema/twitch-video-schema.json) | VOD/highlight video |

### JSON Structures

| Structure | Description |
|---|---|
| [Stream](json-structure/twitch-stream-structure.json) | Live stream field documentation |
| [Channel](json-structure/twitch-channel-structure.json) | Channel field documentation |
| [User](json-structure/twitch-user-structure.json) | User field documentation |

### JSON-LD Context

- [Twitch Context](json-ld/twitch-context.jsonld)

### Examples

| Example | Description |
|---|---|
| [Get Streams](examples/twitch-get-streams-example.json) | List active live streams |
| [Get Users](examples/twitch-get-users-example.json) | Retrieve user information |
| [Get Clips](examples/twitch-get-clips-example.json) | Retrieve video clips |
| [Search Channels](examples/twitch-search-channels-example.json) | Search for channels |
| [Create Clip](examples/twitch-create-clip-example.json) | Create a clip from a live stream |

### Spectral Rules

- [Twitch Rules](rules/twitch-rules.yml) — Enforces Twitch API naming, security, and pagination conventions

### Naftiko Capabilities

**Shared API Definitions**
- [Helix](capabilities/shared/helix.yaml) — Twitch Helix API
- [IGDB](capabilities/shared/igdb.yaml) — Internet Game Database API

**Workflow Capabilities**
- [Content Discovery](capabilities/content-discovery.yaml) — Live stream, channel, clip, and game discovery (8 tools)
- [Channel Management](capabilities/channel-management.yaml) — Chat, polls, subscriptions, and clip management (7 tools)

### Vocabulary

- [Twitch Vocabulary](vocabulary/twitch-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
