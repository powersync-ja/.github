<p align="center">
  <a href="https://www.powersync.com" target="_blank"><img src="https://github.com/powersync-ja/.github/assets/19345049/602bafa0-41ce-4cee-a432-56848c278722"/></a>
</p>

<p align="center">
  <a href="https://docs.powersync.com/"><img src="https://img.shields.io/badge/status%20-%20stable%20-%20%23aa00ff"/></a>
  <a href="https://github.com/powersync-ja"><img src="https://img.shields.io/github/stars/powersync-ja?style=social"/></a>
  <a href="https://discord.gg/powersync" target="_blank"><img src="https://img.shields.io/discord/1138230179878154300?style=social&logo=discord&logoColor=%235865f2&label=Join%20Discord%20server"/></a>
  <a href="https://www.youtube.com/@powersync_" target="_blank"><img src="https://img.shields.io/youtube/channel/subscribers/UCSDdZvrZuizmc2EMBuTs2Qg?style=social&label=YouTube%20%40powersync_"/></a>
  <a href="https://twitter.com/powersync_" target="_blank"><img src="https://img.shields.io/twitter/follow/powersync_?&label=%40powersync_&style=social"/></a>
</p>

<p align="center">
  <table class="foo">
    <tr>
      <td><a href="https://youtu.be/QQ5KcB3o-4g" target="_blank"><img src="https://img.youtube.com/vi/QQ5KcB3o-4g/maxresdefault.jpg" style="max-width: 50%"></a></td>
      <td><a href="https://bndkt.com/blog/2023/building-an-offline-first-chat-app-using-powersync-and-supabase" target="_blank"><img width="1200" src="https://github.com/powersync-ja/.github/assets/19345049/e75e5d12-f1bf-46fe-a25e-81b862e2b83c"></a></td>
    </tr>
  </table>
</p>

# PowerSync: Postgres<>SQLite sync layer for your existing backend
PowerSync keeps backend SQL databases in sync with on-device SQLite databases embedded in a client SDK. It enables real-time reactive offline-first/local-first apps that remain available even when network connectivity is poor or non-existent. 

Offline-first / local-first is a paradigm where your app code works directly with a client-side embedded database, which automatically syncs with a backend database in the background.

PowerSync currently supports Postgres with [Flutter](https://pub.dev/packages/powersync), [React Native](https://www.npmjs.com/package/@journeyapps/powersync-sdk-react-native) and [web](https://github.com/powersync-ja/powersync-web-sdk). Additional backend database support and SDKs are [on the way](https://roadmap.powersync.com/).


## Quick links
- [Website](https://www.powersync.com/)
- [Documentation](https://docs.powersync.com/)
- [Philosophy](https://docs.powersync.com/powersync-philosophy)
- [Quickstart guide](https://docs.powersync.com/usage/quickstart-guide)
- [Example apps](https://docs.powersync.com/resources/examples-demo-apps)

## How do I get started?
See the [introduction](https://docs.powersync.com/) and the [Quickstart guide](https://docs.powersync.com/usage/quickstart-guide) to get started.

**Tutorials:**
- [Building an offline-first chat app with Flutter, Supabase and PowerSync](https://www.powersync.com/blog/flutter-tutorial-building-an-offline-first-chat-app-with-supabase-and-powersync) (blog post)
- [Building an offline-first chat app with Flutter, Supabase and PowerSync](https://youtu.be/LqJ0oix7ybQ?si=atvahziUQy-Lpakm) (video)
- [Building an offline-first chat app with React Native, Supabase and PowerSync](https://bndkt.com/blog/2023/building-an-offline-first-chat-app-using-powersync-and-supabase) (by community member [@bndkt](https://github.com/bndkt))

## Repos
We plan on releasing an open-source version of the [PowerSync service](https://docs.powersync.com/architecture/powersync-service). Supporting self-hosting is one of the steps to get there. 

### Client SDKs
Client SDKs are open-source, available under the Apache 2.0 license:
- [Flutter/Dart SDK](https://github.com/powersync-ja/powersync.dart)
- [React Native SDK](https://github.com/powersync-ja/powersync-react-native-sdk)
- [Web/JS](https://github.com/powersync-ja/powersync-web-sdk)

### Standalone libraries
Open-source, MIT license:
- [sqlite_async](https://github.com/powersync-ja/sqlite_async.dart) — asynchronous interface for SQLite on Dart & Flutter (used by PowerSync Flutter/Dart SDK)

### Examples and demo apps
See here: [Demo Apps / Examples](https://docs.powersync.com/resources/demo-apps-examples)

Demo apps are listed under the backend they use, but you can easily wire up your own backend as documented [here](https://docs.powersync.com/usage/installation/app-backend-setup).

We're constantly expanding our list of example implementations. If you'd like to see an example currently not available, [let us know on Discord](https://discord.gg/powersync). 

## Team
PowerSync was spun off from [JourneyApps](https://github.com/journeyapps-platform), a product that's been in production for over 10 years. PowerSync was founded by [@cahofmeyr](https://github.com/cahofmeyr) and [@rkistner](https://github.com/rkistner) and built by the JourneyApps engineering team.

## Contributing
See the [Community Code of Conduct](https://www.powersync.com/community-code-of-conduct) for our community pledge, standards, responsibilities and guidelines.

## Support
We have an [open community Discord](https://discord.gg/powersync). Join us there for questions, help or just a friendly chat.
