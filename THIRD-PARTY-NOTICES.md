# Third-party notices

Flight Deck Suite is built with, and on, the work of other people and projects. Thank you to their authors. Each item
keeps its own licence; the links lead to the authoritative text. Each app also lists its credits in its own About
page, and each release's package includes the notices for the files it ships.

## Logbook (with Playback and Hangar)

| Component or data | Used for | Licence | Link |
|---|---|---|---|
| Python | the language Logbook runs in | Python Software Foundation License | <https://www.python.org/> |
| PyInstaller | packs Logbook into one program | GPL-2.0, with its bootloader exception | <https://pyinstaller.org/> |
| Microsoft SimConnect | the sim's own interface | Microsoft Flight Simulator SDK terms, © Microsoft Corporation | <https://docs.flightsimulator.com/> |
| OurAirports | airports and runways | public domain | <https://ourairports.com/> |
| Natural Earth | the map | public domain | <https://www.naturalearthdata.com/> |
| topojson-client | drawing the map | ISC | <https://github.com/topojson/topojson-client> |
| timezonefinder | each airport's time zone | MIT | <https://github.com/jannikmi/timezonefinder> |
| timezone-boundary-builder | time zone boundaries, data © OpenStreetMap contributors | ODbL 1.0 | <https://github.com/evansiroky/timezone-boundary-builder> |
| FFmpeg | the share copies of landing videos; a separate program, run on the PC | GPL | <https://ffmpeg.org/> |
| VATSIM Spy data project | VATSIM airports, for Share my flight (downloaded by the app) | CC BY-SA 4.0 | <https://github.com/vatsimnetwork/vatspy-data-project> |

Services used, each under its own terms: SimBrief (the latest flight plan, with your username), VATSIM (weather
reports, events and the public data feed), Tailscale Funnel and GitHub Pages (Share my flight), Google Calendar (only
when you choose Add to Google Calendar). OBS Studio, used for video clips, is a separate program under its own
licence (GPL-2.0) and is not included.

## Squawk

| Component or data | Used for | Licence | Link |
|---|---|---|---|
| VATSIM public data feeds | network data, weather and events | VATSIM's terms | <https://vatsim.net/> |
| VATSIM Spy data project | airspace boundaries (downloaded by the app) | CC BY-SA 4.0 | <https://github.com/vatsimnetwork/vatspy-data-project> |
| Natural Earth | coastlines | public domain | <https://www.naturalearthdata.com/> |
| OurAirports | runways | public domain | <https://ourairports.com/> |
| Open-Meteo | the destination's time zone | CC BY 4.0 (data) | <https://open-meteo.com/> |

Services used, each under its own terms: SimBrief (the flight plan, with your username), Tailscale (the private link
between the PC and the phone) and the Apple Push Notification service (notifications, encrypted on the PC). vPilot,
which Squawk plugs into, is a separate program by its own developer.

## Ramp

| Component or data | Used for | Licence | Link |
|---|---|---|---|
| Microsoft Edge WebView2 SDK | Ramp's window | BSD-style (below) | <https://www.nuget.org/packages/Microsoft.Web.WebView2> |
| Microsoft SimConnect | the sim's own interface | Microsoft Flight Simulator SDK terms, © Microsoft Corporation | <https://docs.flightsimulator.com/> |
| adsb.lol contributors | which airlines park where | ODbL 1.0 | <https://www.adsb.lol/> |
| OpenStreetMap contributors | stand checks | ODbL 1.0 | <https://www.openstreetmap.org/copyright> |
| OurAirports | the airport list | public domain | <https://ourairports.com/> |
| Wikipedia contributors | airlines and destinations where the open data has too little | CC BY-SA 4.0 | <https://www.wikipedia.org/> |
| OpenFlights | airline names | ODbL 1.0 | <https://openflights.org/> |
| timezone-boundary-builder | each airport's time zone, data © OpenStreetMap contributors | ODbL 1.0 | <https://github.com/evansiroky/timezone-boundary-builder> |

Ramp shows the aircraft and liveries of FSLTL (FS Live Traffic Liveries), which you install yourself; it only reads
them. Services used, each under its own terms: SimBrief (the arrival airport, with your username), VATSIM's public
data feed (stands used by other pilots) and, if you switch it on, GSX's Remote Control Server (read only).

### Microsoft Edge WebView2 SDK

Copyright (C) Microsoft Corporation. All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the
following conditions are met:

* Redistributions of source code must retain the above copyright notice, this list of conditions and the following
  disclaimer.
* Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following
  disclaimer in the documentation and/or other materials provided with the distribution.
* The name of Microsoft Corporation, or the names of its contributors may not be used to endorse or promote products
  derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES,
INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY,
WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

## Flight Deck Manager

| Component | Used for | Licence | Link |
|---|---|---|---|
| Microsoft Edge WebView2 SDK | the Manager's window | BSD-style (the notice under Ramp) | <https://www.nuget.org/packages/Microsoft.Web.WebView2> |

The Manager downloads the suite's own apps from this repository's releases; each app's package carries its own
notices.

## The website

Served by GitHub Pages. It uses no outside scripts, fonts or images; the type is the reader's own Georgia or a
similar serif.

---

Flight Deck Suite © 2026 Malcolm Syme · mcsyme11@gmail.com
