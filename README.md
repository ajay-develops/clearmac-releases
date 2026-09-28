# ClearMac releases

Downloads and the update feed for ClearMac, a native Mac storage assistant. The app's source is private; this repository only publishes what users install.

- **Downloads:** notarized DMGs are attached to each [release](https://github.com/ajay-develops/clearmac-releases/releases).
- **Update feed:** ClearMac checks `appcast.xml`, served at `https://ajay-develops.github.io/clearmac-releases/appcast.xml`. Every update is signed with ClearMac's EdDSA key, and the app refuses an update whose signature doesn't match.

When ClearMac checks for updates, the request carries only its version (and the version of Sparkle, the update framework). No system profile, account or file information is sent.
