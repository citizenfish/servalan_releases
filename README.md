# Servalan

Servalan is a desktop app for planning bikepacking and walking routes. You draw a multi-day route on a map and see its heights, climbs and stops while you draw it. You can also open your own GPX files.

This repository holds **Servalan's releases and user guides**, and it is where you can **report a problem or suggest something**. The app's source code is not here.

> **Early feedback builds.** Servalan is in early testing with a small group of feedback users. Expect rough edges, and please tell us about them.

## Get Servalan

Download the latest installer from **[Releases](../../releases)**:

- **macOS** (Apple silicon, macOS 14 or later): `Servalan-<version>-macos-arm64.dmg`
- **Windows:** coming soon.

The feedback builds are not signed yet, so macOS will warn you the first time you open Servalan. [Installing Servalan](docs/install.md) shows how to get past the warning.

## What's in the current release (0.1.0)

0.1.0 is the first feedback build, for Macs with Apple silicon.

- **Open a GPX route** and explore it on the map and its height chart, with distance markers, climb, gradient colours and a time estimate.
- **Draw a new route** in straight lines between points. Heights come in the background from open terrain data.
- **Select a stretch** of a route and cut, copy or remove it. Removing a stretch leaves a gap, which is shown and counted honestly.
- **Paste a stretch,** including from another route shown alongside. A preview shows how it will join before anything changes.
- **Replace a stretch** with a new way, comparing the old way with the new one before you keep it.
- **Look back with the edit history:** undo one change on its own, and save and restore named versions.
- **Use Ordnance Survey maps** of England, Scotland and Wales with your own free OS key.
- **Keep your library on your computer.** You can back it up and download routes as GPX.

## What's not in it yet, but planned

**Next update (0.1.1),** from your feedback on 0.1.0:

- Show another route alongside from your own saved routes, or straight from a GPX file.
- Points along a route are called **route points**, and Pin is taken off the screens.
- A cleaner look for the buttons, lists and tabs, in light and dark.

**Later.** These are planned, roughly in this order. There are no dates yet.

- **Windows.** A Windows build is coming.
- **Following paths.** The line follows real paths and tracks instead of straight lines. It keeps to rights of way, and never sends you down a footpath without saying so.
- **More maps.** A cycle map, satellite and terrain views, overlays such as hill shading and rights of way, and maps you can save for use offline.
- **Places, times and days.** Cafés, shops, water, campsites and more along your route. Arrival times at your own pace, and a trip split into days.
- **Checking a route.** The things worth a look before you ride, such as steep climbs, rough surfaces and long gaps without water. Routes compared side by side.
- **Your rides.** Bring in rides you've recorded, see where you've been on a heatmap, and add notes and photos.
- **Getting it out.** Send a route to your GPS device, add it to Garmin Connect, or print it.
- **An assistant,** off unless you turn it on. It suggests changes for you to preview and accept, and never sends anything anywhere.

## Guides

- [Installing Servalan](docs/install.md)
- [How to get a free OS key](docs/os-key.md), for Ordnance Survey maps of England, Scotland and Wales
- [Reporting a problem](docs/reporting.md)

## Tell us what you think

[Open an issue](../../issues/new/choose) to report a problem or suggest an idea. Please search the existing issues first, in case someone has already raised it.

**No GitHub account?** Use the [feedback form](https://forms.gle/n2zXrZZaZMspB5qz6) instead: you don't need to sign in to GitHub.

## Licences

Servalan includes open-source software and open data. See [Third-party notices](THIRD-PARTY-NOTICES.md).
