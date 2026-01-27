<p align="center">
  <a href="https://www.powersync.com" target="_blank"><img src="https://github.com/user-attachments/assets/bee5c04c-3ff5-4e30-bca8-1e4abe772e7f"/></a>
</p>

<p align="center">
  <a href="https://docs.powersync.com/"><img src="https://img.shields.io/badge/status%20-%20stable%20-%20%23aa00ff"/></a>
  <a href="https://github.com/powersync-ja"><img src="https://img.shields.io/github/stars/powersync-ja?style=social"/></a>
  <a href="https://discord.gg/powersync" target="_blank"><img src="https://img.shields.io/discord/1138230179878154300?style=social&logo=discord&logoColor=%235865f2&label=Join%20Discord%20server"/></a>
  <a href="https://www.youtube.com/@powersync_" target="_blank"><img src="https://img.shields.io/youtube/channel/subscribers/UCSDdZvrZuizmc2EMBuTs2Qg?style=social&label=YouTube%20%40powersync_"/></a>
  <a href="https://twitter.com/powersync_" target="_blank"><img src="https://img.shields.io/twitter/follow/powersync_?&label=%40powersync_&style=social"/></a>
</p>

<p align="center">
  <table class="video-table">
    <tr>
      <td><a href="https://youtu.be/MGQP3DmZG00" target="_blank"><img src="https://img.youtube.com/vi/MGQP3DmZG00/maxresdefault.jpg" style="max-width: 50%"></a></td>
      <td><a href="https://youtu.be/QQ5KcB3o-4g" target="_blank"><img src="https://img.youtube.com/vi/QQ5KcB3o-4g/maxresdefault.jpg" style="max-width: 50%"></a></td>
    </tr>
  </table>
</p>

# PowerSync: Backend DB <> SQLite bi-directional sync engine
PowerSync keeps backend databases in sync with on-device SQLite databases embedded in a client SDK. It lets you avoid the complexities of using APIs to move app state over the network, and enables instantly-responsive local-first & offline-first apps that remain available even when network connectivity is poor or non-existent.

[Local-first is a paradigm](https://www.powersync.com/blog/local-first-is-a-big-deal-especially-for-the-web) where your app code works directly with a client-side embedded database, which automatically syncs with a backend database in the background. It overlaps with the idea of offline-first.

PowerSync is designed to be backend database agnostic, and currently supports Postgres, MongoDB, MySQL (beta), and SQL Server (alpha).

PowerSync is also designed to be client-side framework agnostic, and provides a wide range of [client SDKs](#powersync-client-sdks).

Additional supported backend databases and client SDKs are [on our roadmap](https://roadmap.powersync.com/).

## Quick links
- [Website](https://www.powersync.com/)
- [Documentation](https://docs.powersync.com/)
- [Setup guide](https://docs.powersync.com/intro/setup-guide)
- [Our philosophy](https://docs.powersync.com/intro/powersync-philosophy)
- [Example/demo apps](https://docs.powersync.com/intro/examples)

## How do I get started?
See our [Setup guide](https://docs.powersync.com/intro/setup-guide).

## Repos

### PowerSync client SDKs
Client SDKs are open-source, available under the Apache 2.0 license:
- [Flutter/Dart SDK](https://github.com/powersync-ja/powersync.dart)
- [React Native SDK](https://github.com/powersync-ja/powersync-js/tree/main/packages/react-native)
- [Web/JavaScript](https://github.com/powersync-ja/powersync-js/tree/main/packages/web)
- [Capacitor](https://github.com/powersync-ja/powersync-js/tree/main/packages/capacitor)
- [Kotlin](https://github.com/powersync-ja/powersync-kotlin)
- [Swift](https://github.com/powersync-ja/powersync-swift)
- [.NET](https://github.com/powersync-ja/powersync-dotnet) (currently in alpha)
- [Node.js](https://github.com/powersync-ja/powersync-js/tree/main/packages/node) (currently in beta)

### PowerSync Service
The [PowerSync Service](https://github.com/powersync-ja/powersync-service) is source-available under an [FSL license](https://www.powersync.com/legal/fsl).

The following deployment options are available:
1. **PowerSync Cloud**: A cloud-based managed service — see [pricing plans](https://www.powersync.com/pricing).
2. **PowerSync Open Edition**: A free [source-available self-hosted version](https://docs.powersync.com/intro/self-hosting).
3. **PowerSync Enterprise Self-Hosted Edition**: A [self-hosted version](https://docs.powersync.com/intro/self-hosting#enterprise-self-hosted-edition) with dedicated support, advanced features and custom pricing. See the "Self-host PowerSync" section on our [Pricing](https://www.powersync.com/pricing) page for more details.

See also: [Licensing & Terms](https://www.powersync.com/legal/overview) overview.

### Other supporting client-side libraries
Open-source under Apache 2.0 or MIT license:
- [powersync-sqlite-core](https://github.com/powersync-ja/powersync-sqlite-core) — Rust-based SQLite extension used by PowerSync client SDKs.
- [sqlite_async.dart](https://github.com/powersync-ja/sqlite_async.dart) — SQLite library for Dart & Flutter (used by PowerSync Flutter/Dart SDK, and can also be used stand-alone)
- [drift_sqlite_async](https://github.com/powersync-ja/drift_sqlite_async/) — ORM integration for [Drift](https://drift.simonbinder.eu/) for Dart & Flutter (usable with PowerSync Flutter/Dart SDK)

## Feature Requests & Proposals

Got ideas? We'd love to hear them! Here are a couple of ways you can get involved:

### Feature requests
Have an idea for a new feature or improvement? Head over to [our public roadmap](https://roadmap.powersync.com/) to submit your suggestion or upvote existing ones.

### Technical proposals
Want to contribute technical implementation details? Join the conversations in our [PowerSync Service Proposals](https://github.com/powersync-ja/powersync-service/discussions/categories/proposals) where you can share your thoughts on existing proposals or propose new ones.

## Company & Team
PowerSync is a product of the software company [JourneyApps](https://journeyapps.com/). PowerSync was spun off from [JourneyApps Platform](https://github.com/journeyapps-platform), a product that's been in production for over 10 years. Learn more about the company [here](https://www.powersync.com/company).

## Contributing
See the [Community Code of Conduct](https://www.powersync.com/community-code-of-conduct) for our community pledge, standards, responsibilities and guidelines.

## Support
We have an open community [Discord server](https://discord.gg/powersync). Join us there for questions, help or just a friendly chat.
