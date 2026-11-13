# Flight Deck Suite

**Free companion apps for Microsoft Flight Simulator 2024 on the VATSIM network.** An automatic logbook with an accurate landing rate and landing replays, a phone remote for vPilot, parked airliners at the empty gates and a finder for everything in the Community folder, installed, updated and removed by one app: **Flight Deck Manager**.

**[Website](https://mcsyme11-byte.github.io/Flight-Suite-Releases/)** · [Before you start](https://mcsyme11-byte.github.io/Flight-Suite-Releases/before-you-start.html) · [Manual downloads](https://mcsyme11-byte.github.io/Flight-Suite-Releases/downloads.html)

> This repository hosts the official downloads, release notes and website of Flight Deck Suite. The source code is maintained privately.
>
> **Status:** the first public release was published on Nov 10, 2026 (Flight Deck Manager 0.1.1, Logbook 4.9, Ramp 0.3.1 and Squawk 6.6). Since then: Squawk 6.7 (Nov 11) and Flight Deck Manager 0.1.3 (Nov 13). Every version's changes are on the [What's new](https://mcsyme11-byte.github.io/Flight-Suite-Releases/whats-new.html) page. Vantage is coming soon.

---

## The apps

| App | What it does | Needs |
|---|---|---|
| **Logbook** | Logs every flight by itself, with the landing rate from the sim's own touchdown value, graded for the aircraft's class; runway, touchdown point, crab angle and a stable-approach check; a logbook site on the PC; Share my flight | MSFS 2024 (Share my flight uses Tailscale) |
| **Playback** (with Logbook) | A black box for every landing; the sim flies your landing back while you're parked, with screenshots and, with OBS Studio, video clips | Logbook · OBS Studio optional |
| **Hangar** (with Logbook) | Every add-on in the Community folder with its type, maker, version and size; duplicates and liveries grouped. Read only | Logbook |
| **Squawk** | A vPilot plugin and an iPhone and iPad app: ATC messages with quick replies, the connection and transponder, a live map with your SimBrief route, and alerts | A VATSIM account, vPilot, an iPhone or iPad, Tailscale |
| **Ramp** | Parked, cold-and-dark airliners on empty stands in the right airlines for each airport; keeps your gate and VATSIM pilots' stands clear | MSFS 2024, FSLTL Base Models, Microsoft Edge WebView2 |
| **Vantage** | Cameras, sound and feel | Coming soon |

### Landing grades (fpm)

| Aircraft class | Butter | Smooth | Firm | Hard | Very hard |
|---|---|---|---|---|---|
| Light aircraft | <40 | <120 | <240 | <450 | 450+ |
| Business and regional | <80 | <220 | <350 | <600 | 600+ |
| Single-aisle airliners | <60 | <180 | <300 | <600 | 600+ |
| Wide-body airliners | <100 | <260 | <400 | <600 | 600+ |
| Very large airliners | <120 | <300 | <450 | <600 | 600+ |

## Flight Deck Manager

- **Pick the apps you want:** install one, some or all; each works on its own.
- **Checks the PC first** for what each app needs, and links to anything missing. Microsoft Edge WebView2 it adds itself.
- **Updates in one place:** every download is checked against its published SHA-256 checksum before it's installed.
- **Your flights are kept:** removing an app keeps your flights, recordings and settings unless you choose otherwise.
- **Start with MSFS:** apps can open with the sim. The Manager asks first and changes the sim's start list (exe.xml) only while MSFS is closed, keeping a backup.

## Downloads

| File | Description |
|---|---|
| **FlightDeckManager-Setup.exe** | The recommended installer. It installs Flight Deck Manager for the current Windows user (no administrator rights required); the Manager then installs and updates the apps. |
| Each app's package | For PCs where the Manager can't be used, on the [Manual downloads](https://mcsyme11-byte.github.io/Flight-Suite-Releases/downloads.html) page. These copies do not update automatically. |
| `CHECKSUMS.txt` | The SHA-256 checksum of every file in a release. |

## System requirements

- Windows 10 or Windows 11, 64-bit
- Microsoft Flight Simulator 2024 (Steam or Microsoft Store)
- For Squawk: a VATSIM account, vPilot, an iPhone or iPad, and Tailscale (free for personal use)
- For Ramp: FSLTL Base Models (free)
- For Playback's video clips: OBS Studio (optional)
- Recommended: a SimBrief account; for Share my flight's always-on page, a GitHub account (both free)
- An internet connection to download and update the apps

## Before you start

The apps work alongside a few free programs made by other people. The [Before you start](https://mcsyme11-byte.github.io/Flight-Suite-Releases/before-you-start.html) guide explains, step by step, how to get each one from its official website (Part 1), and then how to set up each app once it's installed (Part 2: Logbook's first start, Squawk on the phone, and Share my flight's live link and always-on page):

| What | For | Official website |
|---|---|---|
| Microsoft Flight Simulator 2024 | every app | [Steam](https://store.steampowered.com/app/2537590) · [flightsimulator.com](https://www.flightsimulator.com/) |
| A VATSIM account | Squawk, and flying online | [my.vatsim.net/register](https://my.vatsim.net/register) |
| vPilot | Squawk | [vpilot.rosscarlson.dev](https://vpilot.rosscarlson.dev/Download) |
| Tailscale (PC and phone) | Squawk; Logbook's Share my flight | [Windows](https://tailscale.com/download/windows) · [App Store](https://apps.apple.com/app/tailscale/id1470499037) |
| FSLTL Base Models | Ramp | [fslivetrafficliveries.com](https://www.fslivetrafficliveries.com/) (through the FlyByWire Installer) |
| Microsoft Edge WebView2 | Ramp and the Manager (added by the Manager if missing) | [Microsoft](https://developer.microsoft.com/microsoft-edge/webview2/) |
| OBS Studio (optional) | Playback's video clips | [obsproject.com](https://obsproject.com/download) |
| GSX's Remote Control Server (optional) | Ramp, if you use GSX | in GSX's settings |
| A SimBrief account (recommended) | your flight plan in Logbook, Squawk and Ramp | [simbrief.com](https://www.simbrief.com/) |
| A GitHub account (optional) | Share my flight's always-on page | [github.com/signup](https://github.com/signup) |

## Installation

1. Download **FlightDeckManager-Setup.exe** and open it.
2. If Windows displays **"Windows protected your PC"**, select **More info**, then **Run anyway**. The warning appears because the Manager is new and is not yet signed with a commercial code-signing certificate; it does not indicate a problem with the software.
3. Choose your apps and select **Install**. The Manager checks the PC, downloads each app, checks it and installs it, and keeps them up to date from then on.

**To uninstall:** Windows Settings › Apps › Installed apps › Flight Deck Manager › Uninstall. Your flights, recordings and settings (`Documents\Flight Deck Suite` and `%LOCALAPPDATA%\Flight Deck Suite`) are kept; these folders may be deleted manually.

## Privacy

The suite has no accounts, advertising, analytics or tracking, and sends nothing to the developer. Everything is stored on your own PC. The apps contact outside services only for the features that need them (for example GitHub for updates, VATSIM's public data, SimBrief with your username, and Tailscale for the link to your phone). See the full [Privacy Policy](https://mcsyme11-byte.github.io/Flight-Suite-Releases/legal.html#privacy-manager).

## Terms and licences

Flight Deck Suite is free to download and use, and is provided as is, without warranty. See the [Terms of Use](https://mcsyme11-byte.github.io/Flight-Suite-Releases/legal.html#terms-manager) and [LICENSE.md](LICENSE.md).

The suite uses open-source software and open data, each under its own licence. See [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md).

Flight Deck Suite is an independent project and is not made by, endorsed by or affiliated with Microsoft, Asobo Studio, VATSIM, the developer of vPilot, Tailscale, the OBS Project, FSLTL, FlyByWire Simulations or FSDreamTeam. For simulation use only.

## Support

Questions and problem reports may be sent to **Malcolm Syme** at [mcsyme11@gmail.com](mailto:mcsyme11@gmail.com). A Discord server is coming soon.

- **When reporting a problem:** include the app and its version (shown in Flight Deck Manager's About page, or the app's own About page) and what happened.
- **Copy report** in the Manager or the app adds the details needed (version, settings and the last lines of its log).

---

Flight Deck Suite © 2026 Malcolm Syme. All rights reserved.
