<p align="center">
  <img src="https://raw.githubusercontent.com/apialerts/.github/refs/heads/main/assets/logo.png" width="100" alt="API Alerts" />
</p>

<h2 align="center">Effortless Project Notifications<br>
<sub>Send once, deliver everywhere.</sub></h2>

<p align="center">
  <a href="https://apialerts.com">Website</a> &bull;
  <a href="https://apialerts.com/docs">Documentation</a> &bull;
  <a href="https://apps.apple.com/us/app/api-alerts/id6476410789">App Store</a> &bull;
  <a href="https://play.google.com/store/apps/details?id=com.apialerts">Google Play</a>
</p>

API Alerts is an event notification platform. Send events from your code and get notified instantly on your phone.

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

### SDKs & Tools

Fire and forget philosophy.

|            | GitHub Repo                                                       | Version                                                                                         |
|------------|-------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|
| CLI        | [cli](https://github.com/apialerts/cli)                           | ![GitHub release](https://img.shields.io/github/v/release/apialerts/cli?filter=!*-*)            |
| Go         | [apialerts-go](https://github.com/apialerts/apialerts-go)         | ![GitHub tag](https://img.shields.io/github/v/tag/apialerts/apialerts-go?filter=!*-*)           |
| JavaScript | [apialerts-js](https://github.com/apialerts/apialerts-js)         | ![npm](https://img.shields.io/npm/v/apialerts-js)                                               |
| Kotlin     | [apialerts-kotlin](https://github.com/apialerts/apialerts-kotlin) | ![Maven Central](https://img.shields.io/maven-central/v/com.apialerts/client?versionPrefix=1.0) |
| Python     | [apialerts-python](https://github.com/apialerts/apialerts-python) | ![PyPI](https://img.shields.io/pypi/v/apialerts)                                                |
| Rust       | [apialerts-rust](https://github.com/apialerts/apialerts-rust)     | ![crates.io](https://img.shields.io/crates/v/apialerts)                                         |
| Swift      | [apialerts-swift](https://github.com/apialerts/apialerts-swift)   | ![GitHub tag](https://img.shields.io/github/v/tag/apialerts/apialerts-swift?filter=!*-*)        |

More SDKs in development and coming soon.

### Destinations

Route events to the channels your team already uses.

- **Push Notifications** — available now via the mobile app
- **Slack, Email, SMS, WhatsApp, Webhooks, Zapier** — coming soon
- More destinations planned for 2026 and beyond

### Get Started

Create a free account at [apialerts.com](https://apialerts.com), grab an API key, and send your first event. Check the [docs](https://apialerts.com/docs) for setup guides.
