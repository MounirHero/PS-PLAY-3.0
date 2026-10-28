# Third-party notices

PS Play is built on the work of many open-source projects. This file lists the third-party components it includes or
links against, their origin and their licence. Where a component is under the GPL, PS Play's corresponding source code
is made available under the same terms (see [Licence](#licence-of-ps-play) at the end).

The list is grouped by licence. A component appears once, under its own licence.

---

## GPL-3.0 / GPL-2.0 (copyleft)

PS Play links against the following GPL components. Because of this, PS Play as a whole is distributed under the
**GPL-3.0-or-later** and its complete corresponding source is published.

| Component in PS Play | Origin | Author(s) | Licence |
|---|---|---|---|
| **Northstar** browser engine | https://github.com/nordstjernen-web/northstar-browser | Andreas Røsdal | GPL-3.0-or-later |
| **Spot5** — Spotify Connect (from **cspot**) | https://github.com/feelfreelinux/cspot · fork https://github.com/philippe44/cspot · PS5 port **Spot5** by https://github.com/abhi245y | feelfreelinux & alufers; philippe44; abhi245y | GPL-3.0 |
| **OpenNOW** — GeForce NOW client | https://github.com/OpenCloudGaming/OpenNOW · https://github.com/Portablelle/OpenNOW-PS5 | OpenCloudGaming; Portablelle | GPL-3.0 |
| **PSBox** — Xbox Cloud Gaming stream | https://github.com/RafaelNGP/xbox-cloud-gaming-ps5 | RafaelNGP | GPL-3.0-or-later |
| **NetSurf** and its libraries (libcss, libdom, libhubbub, libnsfb, libnsgif, libnsbmp, libnsutils, libnspsl, libwapcaplet) | https://www.netsurf-browser.org/ | NetSurf developers | GPL-2.0 (libraries MIT — see below) |
| **FFmpeg** — audio/video decoding | https://ffmpeg.org/ | FFmpeg developers | GPL/LGPL (as built) |
| **FCEUmm** — NES emulator core | https://github.com/libretro/libretro-fceumm | FCEU / FCEUmm and libretro contributors | GPL-2.0 |
| **Gambatte** — Game Boy / Color core | https://github.com/libretro/gambatte-libretro | sinamas and contributors | GPL-2.0 |
| **Genesis Plus GX** — Master System / Mega Drive core | https://github.com/ekeeke/Genesis-Plus-GX | Eke-Eke and contributors | custom (non-commercial) / GPL-compatible |
| **ProSystem** — Atari 7800 core | https://github.com/libretro/prosystem-libretro | Greg Stanton and contributors | GPL-2.0 |
| **PCSX ReARMed** — PlayStation core | https://github.com/libretro/pcsx_rearmed | PCSX / PCSX ReARMed contributors | GPL-2.0+ |
| **PS5SX2** — PlayStation 2 (installed from PS Play), built on **PCSX2** | https://github.com/Swordpdf/PS5SX2 · https://github.com/PCSX2/pcsx2 | Swordpdf; PCSX2 team | GPL-3.0 |

> Full licence texts for these components are included with their source in the corresponding-source repository.

## LGPL

| Component | Origin | Author(s) | Licence |
|---|---|---|---|
| **whisper.cpp** — on-device speech recognition for voice commands (runs OpenAI's Whisper model) | https://github.com/ggml-org/whisper.cpp | Georgi Gerganov and contributors; OpenAI (Whisper model, MIT) | MIT (whisper.cpp) |
| Any LGPL decoder used by the download/extraction tools (e.g. archive decoders) | respective projects | respective authors | LGPL (notices shipped with the source) |

## MIT / BSD / zlib (permissive)

| Component | Origin | Author(s) | Licence |
|---|---|---|---|
| **ps5-homebrew-ui** — PS Play's native UI base | https://github.com/blackbearreloaded | BlackBearReloaded | MIT/permissive |
| **ps5-opengl** — OpenGL runtime | https://github.com/blackbearreloaded/ps5-opengl | BlackBearReloaded | permissive |
| **PS5 Native App Boilerplate** | https://github.com/blackbearreloaded/ps5-native-app-boilerplate | BlackBearReloaded | permissive |
| **ps5-at9-converter** — presentation audio | https://github.com/blackbearreloaded/ps5-at9-converter | BlackBearReloaded | permissive |
| **PS5 Payload SDK** | https://github.com/ps5-payload-dev/sdk | John Törnblom and contributors | BSD/ISC |
| **PacBrew packages** | https://github.com/ps5-payload-dev/pacbrew-repo | ps5-payload-dev | various permissive |
| **stb** (stb_truetype, stb_vorbis, stb_image) — font baking, audio and image decoding | https://github.com/nothings/stb | Sean Barrett | MIT / public domain |
| **QuickJS** — JavaScript engine (browser) | https://bellard.org/quickjs/ | Fabrice Bellard, Charlie Gordon | MIT |
| **lexbor** — HTML parser (browser) | https://github.com/lexbor/lexbor | lexbor contributors | Apache-2.0 |
| **libcurl** — networking | https://curl.se/ | Daniel Stenberg and contributors | curl (MIT-like) |
| **OpenSSL** — TLS | https://www.openssl.org/ | OpenSSL project | Apache-2.0 |
| **mdnsd / mdnssvc** — Spotify Connect discovery (mDNS) | https://github.com/troglobit/mdnsd | Tobias Blomberg and contributors | ISC/MIT |
| **QR Code generator** — basis of PS Play's minimal QR encoder | https://www.nayuki.io/page/qr-code-generator-library | Project Nayuki | MIT |
| **NetSurf support libraries** (libnsfb, libnsgif, libnsbmp, libwapcaplet, etc.) | https://www.netsurf-browser.org/ | NetSurf developers | MIT |
| **SharpProspero**, **UFS2Tool** | https://github.com/SvenGDK/SharpProspero · https://github.com/SvenGDK/UFS2Tool | SvenGDK | permissive |
| **MkPFS** | https://github.com/PSBrew/MkPFS | PSBrew | permissive |
| **GoogleTest** (host tests only) | https://github.com/google/googletest | Google | BSD-3-Clause |
| **zlib** | https://zlib.net/ | Jean-loup Gailly, Mark Adler | zlib |

## Fonts (OFL / licensed)

| Typeface | Origin | Author | Licence |
|---|---|---|---|
| **Inter** | https://github.com/rsms/inter | Rasmus Andersson | SIL OFL 1.1 |
| **Montserrat** | https://github.com/JulietaUla/Montserrat | Julieta Ulanovsky | SIL OFL 1.1 |

## Catalogues and content lists (used by permission / their own terms)

| Component | Origin | Author |
|---|---|---|
| Shop **homebrew** catalogue | https://github.com/nexgen999/PS5-Repository-List | nexgen999 |
| Shop **payload** catalogue | https://github.com/nexgen999/evoX-CoreOS | nexgen999 |
| **Nuvio Portable** (basis of PS Play's Stremio/Nuvio support) | https://github.com/Stuey-81/Nuvio-Portable | Stuey-81 |

## Project this is based on

PS Play was originally based on **ProsperoPlayer** by **KINGDKAK** (https://github.com/KINGDKAK/ProsperoPlayer),
and **SwordPDF** suggested BlackBearReloaded's project as the base of PS Play Native GL.

## Online services

PS Play communicates with the public APIs of many services (YouTube, Twitch, Kick, Dailymotion, Odysee, Jellyfin,
Plex, Emby, Kodi, Trakt, Simkl, AniList, MDBList, Real-Debrid, AllDebrid, TorBox, Premiumize, Last.fm, ListenBrainz,
Jamendo, Radio Browser, Podcast Index, gPodder, MangaDex, Project Gutenberg, OneDrive, Google Drive, Dropbox, MEGA,
WebDAV, Synology, Steam, Xbox, NVIDIA GeForce NOW, Spotify). All trademarks and service names are the property of
their respective owners. PS Play is not affiliated with, authorised by or endorsed by any of them, and includes no
content from these services.

---

## Licence of PS Play

Because PS Play links against GPL components (above), PS Play is distributed under the **GNU General Public License,
version 3 or later (GPL-3.0-or-later)**. Its complete corresponding source code is published so that anyone can study,
modify and rebuild it under the same terms.

"PS Play" is just the name this project uses and is not claimed as a trademark. If you publish a fork, please give it
a different name so users are not led to believe it is this project. This request does not restrict any GPL right.

If any component is listed with the wrong licence or author, please open an issue so it can be corrected.
