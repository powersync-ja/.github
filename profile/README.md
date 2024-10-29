<p align="center">
  <a href="https://www.powersync.com" target="_blank"><img src="https://github.com/powersync-ja/.github/assets/7372448/d2538c43-c1a0-4c47-9a76-41462dba484f"/></a>
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
PowerSync keeps backend databases in sync with on-device SQLite databases embedded in a client SDK. It enables instantly-responsive local-first & offline-first apps that remain available even when network connectivity is poor or non-existent. 

[Local-first is a paradigm](https://www.powersync.com/blog/local-first-is-a-big-deal-especially-for-the-web) where your app code works directly with a client-side embedded database, which automatically syncs with a backend database in the background. It overlaps with the offline-first paradigm.

PowerSync is designed to be backend database agnostic, and currently supports Postgres (stable), MongoDB (alpha), and MySQL (alpha).

PowerSync is also designed to be client-side framework agnostic, and currently supports [Flutter](https://docs.powersync.com/client-sdk-references/flutter), [React Native & Expo](https://docs.powersync.com/client-sdk-references/react-native-and-expo), [web/JS](https://docs.powersync.com/client-sdk-references/js-web), [Kotlin Multiplatform](https://www.powersync.com/blog/build-local-first-kotlin-multiplatform-apps-with-powersync) (beta) and [Swift](https://docs.powersync.com/client-sdk-references/swift) (alpha)

Additional supported backend databases and client SDKs are [on our roadmap](https://roadmap.powersync.com/).

## Quick links
- [Website](https://www.powersync.com/)
- [Documentation](https://docs.powersync.com/)
- [Philosophy](https://docs.powersync.com/powersync-philosophy)
- [Quickstart guide](https://docs.powersync.com/usage/quickstart-guide)
- [Example/demo apps](https://docs.powersync.com/resources/demo-apps-example-projects)

## How do I get started?
See the [introduction](https://docs.powersync.com/) and the [Quickstart guide](https://docs.powersync.com/usage/quickstart-guide) to get started.

**Tutorials:**
- [Building an offline-first chat app with Flutter, Supabase and PowerSync](https://www.powersync.com/blog/flutter-tutorial-building-an-offline-first-chat-app-with-supabase-and-powersync) (blog post)
- [Building an offline-first chat app with Flutter, Supabase and PowerSync](https://youtu.be/LqJ0oix7ybQ?si=atvahziUQy-Lpakm) (video)
- [Building an offline-first chat app with React Native, Supabase and PowerSync](https://bndkt.com/blog/2023/building-an-offline-first-chat-app-using-powersync-and-supabase) (by community member [@bndkt](https://github.com/bndkt))

## Repos

### PowerSync client SDKs
Client SDKs are open-source, available under the Apache 2.0 license:
- [Flutter/Dart SDK](https://github.com/powersync-ja/powersync.dart)
- [React Native SDK](https://github.com/powersync-ja/powersync-js/tree/main/packages/react-native)
- [Web/JS](https://github.com/powersync-ja/powersync-js/tree/main/packages/web)
- [Kotlin Multiplatform](https://github.com/powersync-ja/powersync-kotlin) (currently in beta)
- [Swift](https://github.com/powersync-ja/powersync-kotlin-swift-demo) (currently in open alpha)

### PowerSync Service
The [PowerSync Service](https://github.com/powersync-ja/powersync-service) is source-available under an [FSL license](https://www.powersync.com/legal/fsl).

The following deployment options are available:
1. **PowerSync Cloud**: A cloud-based service with [pricing plans](https://www.powersync.com/pricing)
2. **PowerSync Open Edition**: A free [source-available self-hosted version](https://docs.powersync.com/self-hosting/getting-started)
3. **PowerSync Enterprise Self-Hosted Edition**: A [self-hosted Enterprise Edition](https://docs.powersync.com/self-hosting/enterprise) with dedicated support plans, extra functionality and custom pricing.

See also: [Licensing & Terms](https://www.powersync.com/legal/overview) overview.

### Other supporting client-side libraries
Open-source under Apache 2.0 or MIT license:
- [powersync-sqlite-core](https://github.com/powersync-ja/powersync-sqlite-core) — Rust-based SQLite extension used by PowerSync client SDKs.
- [sqlite_async.dart](https://github.com/powersync-ja/sqlite_async.dart) — SQLite library for Dart & Flutter (used by PowerSync Flutter/Dart SDK, and can also be used stand-alone)
- [drift_sqlite_async](https://github.com/powersync-ja/drift_sqlite_async/) — ORM integration for [Drift](https://drift.simonbinder.eu/) for Dart & Flutter (usable with PowerSync Flutter/Dart SDK)

### Examples and demo apps
See here: [Demo Apps / Examples](https://docs.powersync.com/resources/demo-apps-example-projects)

Demo apps are listed under the backend they use, but you can easily wire up your own backend as documented [here](https://docs.powersync.com/usage/installation/app-backend-setup).

We're constantly expanding our list of example implementations. If you'd like to see an example currently not available, [let us know on Discord](https://discord.gg/powersync). 

## Team
PowerSync was spun off from [JourneyApps](https://github.com/journeyapps-platform), a product that's been in production for over 10 years. PowerSync was founded by [@cahofmeyr](https://github.com/cahofmeyr) and [@rkistner](https://github.com/rkistner). Learn more about the team [here](https://www.powersync.com/team).

## Contributing
See the [Community Code of Conduct](https://www.powersync.com/community-code-of-conduct) for our community pledge, standards, responsibilities and guidelines.

## Support
We have an [open community Discord](https://discord.gg/powersync). Join us there for questions, help or just a friendly chat.
