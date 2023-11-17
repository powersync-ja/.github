<p align="center">
  <a href="https://www.powersync.com" target="_blank"><img src="https://github.com/powersync-ja/.github/assets/19345049/602bafa0-41ce-4cee-a432-56848c278722"/></a>
</p>

<br></br>
<p align="center">
<a href="https://docs.powersync.co/"><img src="https://img.shields.io/badge/status%20-%20beta%20-%20%23aa00ff"/></a>
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


# Sync layer for your existing Postgres and backend
Enable offline-first architecture for real-time reactive apps that remain available even when network connectivity is poor or non-existent.

## Quick links
- [Website](https://www.powersync.com/)
- [Documentation](https://docs.powersync.co/)
- [Philosophy](https://docs.powersync.co/powersync-philosophy)
- [Quickstart guide](https://docs.powersync.co/usage/quickstart-guide)
- [Example apps](https://docs.powersync.co/resources/examples-demo-apps)

## What is PowerSync?
PowerSync is a service that keeps backend SQL databases in sync with on-device SQLite databases embedded in a client SDK. 

## How do I get started?
PowerSync provides a drop-in sync layer for your existing database and backend. Currently supports Postgres with [Flutter](https://pub.dev/packages/powersync), [React Native](https://www.npmjs.com/package/@journeyapps/powersync-sdk-react-native) and [web](https://github.com/powersync-ja/powersync-web-sdk). Additional backend database support and SDKs are [on the way](https://roadmap.powersync.com/).

See the [introduction](https://docs.powersync.co/) and the [Quickstart guide](https://docs.powersync.co/usage/quickstart-guide) to get started.

**Examples:**
- [Building an offline-first chat app with React Native, Supabase and PowerSync](https://bndkt.com/blog/2023/building-an-offline-first-chat-app-using-powersync-and-supabase)
- [Building an offline-first chat app with Flutter, Supabase and PowerSync](https://youtu.be/LqJ0oix7ybQ?si=atvahziUQy-Lpakm)

## Repos
We plan on releasing an open-source version of the PowerSync service. Supporting self-hosting is one of the steps to get there. Client SDKs are available under the Apache-2.0 license.

### Standalone projects
- [Asynchronous interface for SQLite on Dart & Flutter](https://github.com/powersync-ja/sqlite_async.dart)

### Client SDKs
- [Flutter/Dart SDK](https://github.com/powersync-ja/powersync.dart)
- [React Native SDK](https://github.com/powersync-ja/powersync-react-native-sdk)
- [Web/JS](https://github.com/powersync-ja/powersync-web-sdk)

### Examples and demo apps
We're constantly expanding our list of example implementations. If you'd like to see an example currently not available, [let us know on Discord](https://discord.gg/powersync). Demo apps are listed under the backend they use, but you can easily wire up your own backend as documented [here](https://docs.powersync.co/usage/installation/app-backend-setup).

🟨 **Web**
Supabase Backend:
- [NextJS To-Do List App](https://github.com/powersync-ja/powersync-web-sdk/tree/main/demos/powersync-nextjs-demo)

💙 **Flutter**
Supabase Backend:
- [To-Do List App](https://github.com/powersync-ja/powersync-supabase-flutter-todolist-demo)
- [Trello Clone App](https://github.com/powersync-ja/powersync-supabase-flutter-trello-demo)
- [Simple Chat App](https://github.com/powersync-ja/powersync-supabase-flutter-simple-chat-demo)

⚛️ **React Native & Expo**
Supabase Backend:
- [To-Do List App](https://github.com/powersync-ja/powersync-supabase-react-native-todolist-demo)
- [PowerChat - Group Chat App](https://github.com/powersync-ja/powersync-supabase-react-native-group-chat-demo)

**Django Custom Backend:**
- [To-Do List App](https://github.com/powersync-ja/powersync-django-react-native-todolist-demo)

🛠️ **Custom Backend Example**
- [Django To-Do List](https://github.com/powersync-ja/powersync-django-backend-todolist-demo)

## Team
PowerSync was spun off from [JourneyApps](https://github.com/journeyapps-platform), a product that's been in production for over 10 years. PowerSync was founded by [@cahofmeyr](https://github.com/cahofmeyr) and [@rkistner](https://github.com/rkistner) and built by the JourneyApps engineering team.

## Contributing
See the [Community Code of Conduct](https://www.powersync.com/community-code-of-conduct) for our community pledge, standards, responsibilities and guidelines.

## Support
We have an [open community Discord](https://discord.gg/powersync). Join us there for questions, help or just a friendly chat.
