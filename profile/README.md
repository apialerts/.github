<p align="center">
  <img src="https://raw.githubusercontent.com/apialerts/.github/refs/heads/main/assets/logo.png" width="100" alt="API Alerts" />
</p>

<h3 align="center">Effortless Project Notifications<br>
Send once, deliver everywhere.</h3>

<p align="center">
  <a href="https://apialerts.com">Website</a> &bull;
  <a href="https://apialerts.com/docs">Documentation</a> &bull;
  <a href="https://apps.apple.com/us/app/api-alerts/id6476410789">App Store</a> &bull;
  <a href="https://play.google.com/store/apps/details?id=com.apialerts">Google Play</a>
</p>

API Alerts is an event notification platform. Send one event from your code and deliver it to push, Slack, Discord, email, SMS, WhatsApp, or a webhook.

Minimal:
```bash
curl -X POST https://api.apialerts.com/event \
  -H "Authorization: Bearer <API_KEY>" \
  -H "Content-Type: application/json" \
  -d '{"message": "Deploy complete"}'
```

With all options:
```bash
curl -X POST https://api.apialerts.com/event \
  -H "Authorization: Bearer <API_KEY>" \
  -H "Content-Type: application/json" \
  -d '{
    "message": "New user signed up",
    "channel": "signups",
    "link": "https://dashboard.example.com/users/123",
    "tags": ["signup", "organic"]
  }'
```

See the full [API Reference](https://apialerts.com/docs/api-reference/introduction) for details.

### SDKs

Fire and forget philosophy. Configure once, send from anywhere.

|            | GitHub Repo                                                       | Version                                                                                       |
|------------|-------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|
| C#         | [apialerts-csharp](https://github.com/apialerts/apialerts-csharp) | ![NuGet](https://img.shields.io/nuget/v/ApiAlerts)                                             |
| Dart       | [apialerts-dart](https://github.com/apialerts/apialerts-dart)     | ![pub](https://img.shields.io/pub/v/apialerts)                                                 |
| Godot      | [apialerts-godot](https://github.com/apialerts/apialerts-godot)   | ![GitHub tag](https://img.shields.io/github/v/tag/apialerts/apialerts-godot?filter=!*-*)       |
| Go         | [apialerts-go](https://github.com/apialerts/apialerts-go)         | ![GitHub tag](https://img.shields.io/github/v/tag/apialerts/apialerts-go?filter=!*-*)          |
| Java       | [apialerts-java](https://github.com/apialerts/apialerts-java)     | via [Kotlin](https://github.com/apialerts/apialerts-kotlin)                                    |
| JavaScript | [apialerts-js](https://github.com/apialerts/apialerts-js)         | ![npm](https://img.shields.io/npm/v/apialerts)                                                 |
| Kotlin     | [apialerts-kotlin](https://github.com/apialerts/apialerts-kotlin) | ![Maven Central](https://img.shields.io/maven-central/v/com.apialerts/client?versionPrefix=1) |
| PHP        | [apialerts-php](https://github.com/apialerts/apialerts-php)       | ![Packagist](https://img.shields.io/packagist/v/apialerts/apialerts)                          |
| Python     | [apialerts-python](https://github.com/apialerts/apialerts-python) | ![PyPI](https://img.shields.io/pypi/v/apialerts)                                               |
| Ruby       | [apialerts-ruby](https://github.com/apialerts/apialerts-ruby)     | ![Gem](https://img.shields.io/gem/v/apialerts)                                                 |
| Rust       | [apialerts-rust](https://github.com/apialerts/apialerts-rust)     | ![crates.io](https://img.shields.io/crates/v/apialerts)                                        |
| Swift      | [apialerts-swift](https://github.com/apialerts/apialerts-swift)   | ![GitHub tag](https://img.shields.io/github/v/tag/apialerts/apialerts-swift?filter=!*-*)       |

### Tools

|               | GitHub Repo                                                 | Version                                                                              | Platforms                               |
|---------------|-------------------------------------------------------------|--------------------------------------------------------------------------------------|-----------------------------------------|
| CLI           | [cli](https://github.com/apialerts/cli)                     | ![GitHub release](https://img.shields.io/github/v/release/apialerts/cli?filter=!*-*) | macOS, Linux (apt,rpm,aur), Windows, GO |

### Integrations

|               | GitHub Repo                                                 | Version                                                                                        |
|---------------|-------------------------------------------------------------|------------------------------------------------------------------------------------------------|
| GitHub Action | [notify-action](https://github.com/apialerts/notify-action) | ![GitHub release](https://img.shields.io/github/v/release/apialerts/notify-action?filter=!*-*) |
| Zapier        | [zapier](https://github.com/apialerts/zapier)               | v3 Coming Soon                                                                                  |

### Destinations

Send one event, deliver it everywhere. All destinations are available now in open beta:

- **Push** - iOS and Android app
- **Slack** - post to your channels
- **Discord** - rich embeds to your server
- **Email** - delivered via Amazon SES
- **SMS** - Twilio-backed
- **WhatsApp** - Twilio-backed
- **Webhooks** - forward events as JSON to any URL

### Open Beta

API Alerts 2.0 is in open beta: event routing and multi-destination delivery on top of push. Opt in from your dashboard, no waitlist. More destinations and inbound connectors (Microsoft Teams, Telegram, PagerDuty, and more) are planned through 2026.

### Get Started

Create a free account at [apialerts.com](https://apialerts.com), grab an API key, and send your first event. Check the [docs](https://apialerts.com/docs) for setup guides.
