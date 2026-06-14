# Twitch GraphQL

## Overview

Twitch uses GraphQL internally for its web and mobile clients. While Twitch does not offer an officially supported public GraphQL API, the internal GQL endpoint at `https://gql.twitch.tv/gql` is widely documented by the developer community through reverse engineering.

The official public API remains the Twitch Helix REST API at `https://api.twitch.tv/helix`. This document describes the GraphQL type model that underlies both the internal GQL surface and the conceptual data model behind the REST API.

## Endpoint

- **Internal (unofficial):** `https://gql.twitch.tv/gql`
- **Official REST base:** `https://api.twitch.tv/helix`

## Authentication

All requests require a valid OAuth 2.0 token obtained via the Twitch OAuth flow. Client credentials, authorization code, and implicit grant flows are all supported.

- Scopes documentation: https://dev.twitch.tv/docs/authentication/scopes/
- Getting Started: https://dev.twitch.tv/docs/authentication

## Schema

The full GraphQL schema is defined in `twitch-schema.graphql` in this directory. It covers 55 types derived from the Twitch Helix REST API surface and known internal GQL usage, including:

- **Streaming:** Stream, Channel, Video, Clip, Schedule, ScheduleSegment
- **Users & Identity:** User, Follower, Subscription
- **Discovery:** Game, Category, Tag, Emote, Badge
- **Commerce:** BitsLeaderboard, BitsProduct, Reward, Redemption, Goal
- **Engagement:** Poll, PollChoice, Prediction, PredictionOutcome, HypeTrain, Cheer
- **Extensions & Embeds:** Extension
- **Moderation:** Moderation, BanUser, UnbanRequest, Shield, BlockedTerm, AutoMod
- **Chat:** ChatMessage, ChatSettings, Announcer
- **EventSub:** EventSubSubscription, ConduitShard
- **Ads & Creators:** Ad, Creator
- **Community:** Raider, VIP, Guest

## Key Operations

### Queries

- `stream(userId: ID!)` — Fetch a live stream by user ID
- `channel(id: ID!)` — Fetch channel metadata
- `user(id: ID!, login: String)` — Look up a user by ID or login
- `game(id: ID!, name: String)` — Look up a game/category
- `videos(userId: ID!, type: VideoType)` — List VODs for a channel
- `clips(broadcasterId: ID!)` — List clips for a broadcaster
- `searchChannels(query: String!)` — Search channels
- `searchCategories(query: String!)` — Search game categories

### Mutations

- `createPoll(input: CreatePollInput!)` — Start a channel poll
- `endPoll(input: EndPollInput!)` — End a channel poll
- `createPrediction(input: CreatePredictionInput!)` — Create a prediction
- `endPrediction(input: EndPredictionInput!)` — Resolve a prediction
- `banUser(input: BanUserInput!)` — Ban a user from a channel
- `unbanUser(input: UnbanUserInput!)` — Remove a ban
- `createCustomReward(input: CreateCustomRewardInput!)` — Add a channel point reward
- `updateCustomReward(input: UpdateCustomRewardInput!)` — Modify a reward
- `sendChatAnnouncement(input: SendChatAnnouncementInput!)` — Send a chat announcement

## References

- Official Helix REST API docs: https://dev.twitch.tv/docs/api/reference/
- EventSub subscription types: https://dev.twitch.tv/docs/eventsub/eventsub-subscription-types
- Authentication scopes: https://dev.twitch.tv/docs/authentication/scopes/
- Twitch Developer GitHub: https://github.com/twitchdev
- Community GQL reverse engineering reference: https://github.com/mauricew/twitch-graphql-api
