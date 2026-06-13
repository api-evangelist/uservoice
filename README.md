# UserVoice

UserVoice is a product feedback and ideation platform with a REST API for managing ideas, gathering votes, tracking status, and syncing user feedback with product roadmaps.

## APIs

- **Admin API v2** - Administrative operations, data syncing, content moderation, and exports. Base URL: `https://SUBDOMAIN.uservoice.com/api/v2/admin/`
- **Helpdesk API v1** - End-user and admin support functionality via OAuth 1.0a
- **Idea Collection API** - Custom feedback capture across web and mobile via OAuth PKCE

## Authentication

- Admin API v2: Bearer token (API key via trusted client setup in Admin Console)
- Helpdesk API v1: OAuth 1.0a (2-legged or 3-legged)
- Idea Collection API: OAuth Authorization Code Flow with PKCE

## SDKs

- [iOS SDK](https://github.com/uservoice/uservoice-ios-sdk) (Objective-C)
- [Android SDK](https://github.com/uservoice/uservoice-android-sdk) (Java, archived)
- [Ruby Client](https://github.com/uservoice/uservoice-ruby) (archived)

## Links

- [Developer Portal](https://developer.uservoice.com/)
- [API Documentation](https://developer.uservoice.com/docs/)
- [Admin API Reference](https://developer.uservoice.com/docs/api/v2/reference/)
- [Pricing](https://www.uservoice.com/pricing/)
- [Status Page](https://status.uservoice.com/)
- [Blog](https://www.uservoice.com/blog/)
- [GitHub Organization](https://github.com/uservoice)
- [LinkedIn](https://www.linkedin.com/company/uservoice)
- [X / Twitter](https://twitter.com/uservoice)

## Maintainer

Kin Lane - kin@apievangelist.com
