<div align="center">

<img src="assets/logo.jpg" alt="PS Play" width="520">

**An all-in-one mediahub, cloud gaming and homebrew hub for the PS5**

</div>

<div align="left">
  
> PS Play is a native PS5 homebrew application (OpenGL, payload SDK) for jailbroken consoles. It brings streaming,
> music, cloud gaming, a homebrew shop, emulators, a web browser and file tools together in one app with one design,
> one controller layout and one place for every account.
  
![Version](https://img.shields.io/badge/version-1.005%20RC%20(build%20101)-2f6fed) ![Firmware](https://img.shields.io/badge/PS5%20firmware-4.00%20%E2%80%93%2013.60-0070d1) ![Platform](https://img.shields.io/badge/platform-PS5%20(jailbroken)-111111) ![Licence](https://img.shields.io/badge/licence-GPL--3.0-green)

[![Discord](https://img.shields.io/badge/Discord-join-5865F2?logo=discord&logoColor=white)](https://discord.gg/3Ce2jft2H) [![X](https://img.shields.io/badge/X-@InsideMatrixDEV-000000?logo=x&logoColor=white)](https://x.com/InsideMatrixDEV)

[![Ko-fi](https://img.shields.io/badge/support-Ko--fi-ff5e5b)](https://ko-fi.com/insidematrixdev)

[![Downloads](https://img.shields.io/github/downloads/MounirHero/PS-PLAY-App/total)](https://github.com/MounirHero/PS-PLAY-App/releases)

By **InsideMatrixDev**

</div>

---

## Contents
- [Highlights](#highlights)
- [What's new in 1.005](#whats-new-in-1005)
- [Features](#features)
- [Helpers](#helpers-the-small-programs-ps-play-runs-for-you)
- [Requirements](#requirements)
- [Installation](#installation)
- [FAQ](#faq)
- [Reporting a bug](#reporting-a-bug)
- [Privacy and security](#privacy-and-security)
- [Credits and origins](#credits-and-origins)

## Highlights
- **One app instead of twenty**: video, music, cloud gaming, games and homebrew tools, a social space, files and
  downloads share one interface, one controller layout and one place for every account.
- **Built for the controller and the TV**: every page works with the pad; text can also be typed from the phone.
- **Your phone as a companion**: a web panel on your network (and a QR code wherever you would type or sign in).
- **PS Play Social**: friends, private chats, groups and what your friends are playing - on the console and on the
  web at social.insidematrixdev.com.
- **Five home themes plus the PS5 one**, icon packs, live wallpapers and per-theme options.
- **Games and homebrew tools in one place**: PKG Matrix *(beta)*, a cheat engine, save backups, emulators and a homebrew
  shop that reads third-party catalogues.
- **Background playback and picture-in-picture**: music, radio and Spotify keep playing while you use the rest of
  PS Play; any video can keep playing in a corner. Music after you leave PS Play (the background music helper) is
  *work in progress*.

> **Labels used below** - *beta*: it works, but it may not work yet on every console, network or setup;
> *work in progress*: partly there, not finished; *coming soon*: planned, not in the app yet.

## What's new in 1.005
- **Spotify Connect**: the PS5 shows up as "PS Play" in the Spotify app on your phone; the music plays on the
  console, with what is playing, play / pause / next and your Home and Library on the TV (Spotify Premium).
- **PS Play Social**: friends, private chats, groups and a global chat, reactions, replies, read receipts, sharing
  saves, cheats and themes, a lobby showing what your friends are doing, and the web version at social.insidematrixdev.com.
- **Redesigned settings**: nine clear sections (General, Appearance, Playback, Audio, Devices, Accounts, Content,
  System, Storage), a search, and an Accounts section where every service shows its sign-in state.
- **PKG Matrix** *(beta)*: every app folder, image and PKG on every drive, with the tools to build images and packages.
- **Cheats**: a cheat engine for the game you are playing, with the GoldHEN and etaHEN PS5 databases.
- **New web panel**: a control panel for the phone with your games, media, files, downloads and tools.
- **Receivers** *(beta)*: DLNA, AirPlay, Miracast, YouTube Cast and FCast, with the console's own name on your network.
- **Home themes**: Nintendo Switch (dark / light), PS4 and Inferno themes, plus wallpaper dimming, an
  accent tint and dark edges for every theme.

## Features

### Video and streaming
- YouTube with its own TV sign-in (QR) and your library; Twitch, Kick, Vimeo, Dailymotion and PeerTube links.
- Movies and series through **Stremio and Nuvio add-ons** and their catalogues, with **Real-Debrid, AllDebrid,
  TorBox and Premiumize** (sign-in with a code or QR), Trakt, Simkl, AniList and MDBList.
- Media servers: **Plex, Jellyfin, Emby, Kodi**; IPTV with **Xtream Codes**, **Tvheadend** and free TV channels.
- Playback with FFmpeg (software decoding), HDR tone mapping, upscaling, subtitles (with automatic translation and subtitles from
  the audio), skip intro, resume, next episode and a daily limit for children.
- **Hardware video decoding** *(beta, off by default)*: 8-bit H.264 and HEVC through the console's video decoder, turned
  on in Settings > Playback; everything else (VP9, AV1, 10-bit) stays on FFmpeg.
- **Recents** with a frame or cover for everything you played.

### Music and audio
- **Spotify Connect** (see above) and **YouTube Music** with its own account: your library, playlists and liked songs.
- Radio stations, podcasts (Podcast Index, gpodder / Nextcloud), Jamendo, **Navidrome / Subsonic** and
  **Audiobookshelf**; scrobbling to Last.fm and ListenBrainz; song recognition with AcoustID.
- Equaliser, night mode, Bluetooth audio devices, controller audio and a sleep timer.
- **Background music helper** *(work in progress)*: the music keeps playing when you leave PS Play, but its sound
  does not come out of the console yet.

### Cloud gaming and remote play
- **Xbox Cloud Gaming** and **GeForce NOW**; **Moonlight** for the games on your PC; a remote desktop (VNC).
- Picture-in-picture: keep a video playing (muted) while you play in the cloud.

### Games and homebrew
- **Game library** with covers and a page for every game: launch, cheats, saves and information; "return to PS Play
  after a game".
- **PKG Matrix** *(beta)*: app folders, game images and PKG files on every drive (internal and USB). Build a **.ffpkg** image
  (UFS2, for ShadowMountPlus), **backport** an image to your console's firmware, and build a **PS4 game as a .pkg**.
  **PS1 / PS2 Classics**: a guide to build PS4 packages from your PS1 and PS2 games with the PS Classics emulators.
- **Cheat engine**: turn cheats on and off from a game's page while the game runs (the original bytes come back
  when it stops). Databases from **GoldHEN** and **etaHEN PS5**, updated every week, only for your game version if
  you like, and your own cheat files.
- **Saves**: background backups, back up everything now, export and import decrypted saves, edit them with a hex
  editor, backups on USB.
- **Homebrew Shop**: homebrew apps and payloads from the homebrew catalogues (NexGen and others): install, update,
  and keep the payload catalogue up to date.
- **Shop for app catalogues**: PS Play reads the catalogue formats used by other PS5 download apps, such as
  PegasusDL, PS Box, PippoLS, DLPS and Orbit Store. Put the catalogue files (JSON: `PS5.json`, `PS4.json`,
  `PS3.json`, `PS2.json`, `PS1.json`) in `/data/ps_play/catalogs`, or upload them from your
  phone with the web panel (**Altro > Cataloghi dello Shop**): PS Play checks them and reloads the Shop by itself.

  > **Disclaimer**: PS Play does not include, host or link any catalogue or any content, and it does not say where
  > to find them. Some third-party catalogues point to copyrighted games: downloading games you do not own may be
  > illegal where you live. You are responsible for the catalogues you load and for what you download; use them only
  > for content you have the right to use.
- **Payloads**: send ELF payloads to the console's loader, with their own catalogue and updates.
- **Emulators**: installers for **RetroArch** (Mihawk's build, 33+ cores), **PS5SX2** (PlayStation 2) and **PS5SX3**
  (PlayStation 3), the cores of the other retro emulators, and RetroAchievements.
- **File host downloads**: when a file host puts a browser check (Cloudflare) in front of a download, you pass it in
  the PS5 browser and a small scanner payload picks up the session, so the download continues in PS Play.

### PS Play Social
- Friends and friend requests, private chats (from friends, or from nobody), groups (public, private, with an
  invite code) and the global chat.
- Reactions, replies, read receipts (that you can turn off), mute a chat, delete a chat for yourself only.
- **Share** with friends, a group or everyone: **saves, cheats, themes, settings and screenshots** of the console and
  of PS Play. Limits, the same for everyone: **4 MB per file**; per user **10 shares and 20 MB a day**, **30 MB** in
  all and one share every **2 minutes**; **50 MB per room** (5 pinned); **50 downloads a day**; shared files are kept
  **30 days**.
- See what your friends are playing ("what I am playing", optional), notifications.
- The same account on the web at **social.insidematrixdev.com**, with "Your PS5": your console's web panel one tap away.
- Community rules and moderation (reports, bans); the rules state what moderators can read.

### Phone, network and receivers
- **Web panel** on your network: your games and what to continue, media, files (browse, upload, download),
  downloads, payloads, logs, the console's keyboard and pad, and app updates.
- **Receivers** *(beta)*: DLNA renderer, AirPlay, Miracast, YouTube Cast and FCast, each one on or off, with the
  console's name on your network. The AirPlay receiver is forked from
  [MirrorPSX](https://github.com/seregonwar/MirrorPSX) by seregonwar. Chromecast is *coming soon*.
- **Android Link** *(beta)*: your Android phone and the console working together; it may not work with every
  Android phone.
- Network test and the network speed in the top bar.

### Web browser *(work in progress)*
- A web browser inside PS Play, **rebuilt from scratch**, and the PS5's own browser opened from PS Play; pages and compatibility are being
  improved. **Any help is welcome**: issues and pull requests are open.

### Files, cloud storage and downloads
- File manager for the internal storage and USB drives.
- **OneDrive, MEGA, WebDAV / Nextcloud** and **Synology**.
- Downloads with a schedule, a speed limit, a mirror of your choice, simultaneous downloads and rest mode at the
  end; torrents built in, plus **qBittorrent, Transmission, Prowlarr, Jackett, Sonarr and Radarr**.

### Reading and photos
- **MangaDex** (no account), **Komga, Kavita** and **Calibre-Web / OPDS** catalogues; ebooks and comics.
- Photos from **NASA** and **Unsplash** (also for the screensaver and as wallpapers), the gallery of
  your console and USB drives, IP cameras (RTSP and ONVIF).

### Home themes and personalisation
- **Home themes**: PS5 (default), **PS4**, **Xbox Series** (with ConsoleDash wallpapers), **Nintendo Switch** (dark or
  light), **Shelf** and **Inferno** (fire colour and embers).
- **Theme settings** for every theme: background, accent colour, theme sounds, wallpaper dimming, accent tint and
  dark edges, plus each theme's own options (tile size, card count, fire colour...).
- **Icon packs**, icon size and shape, avatars, live wallpapers (particles, Matrix, music and more), ready-made
  themes and "save the look as a theme".

### Settings, accessibility and family
- Settings in nine sections with search; every service's account in one place.
- **Voice commands** (hold L3): open any page or service, search YouTube, YouTube Music, Plex, radio, podcasts and
  manga ("play ... on YouTube Music"), control the music and the volume, plus your own commands.
- Screen reader, high contrast, text size and reduced motion.
- Parental controls (PIN, daily video limit); controller vibration, adaptive triggers and light bar.

### System
- In-app updates from the web panel, and **go back to the previous version** if an update misbehaves.
- Settings backup and restore, storage overview, cache and covers, power saving and a photo screensaver.
- Logs you can send to your phone in one tap, detailed logs, statistics and plugins.

### Helpers: the small programs PS Play runs for you
PS Play starts these helpers on the console through the ELF loader (port 9021), only when a feature needs them; they
run apart from the app, so some of them keep working after PS Play is closed.

| Helper | What it does |
|---|---|
| **ppdl** - background downloader | Downloads and torrents keep going when PS Play is closed (the same download engine as the app). |
| **bckscan** - file host scanner | When a file host puts a browser check (Cloudflare) in front of a download, you pass it in the PS5 browser; the scanner picks up the session so the download starts in PS Play. |
| **ppfs** - file service | Long copies, moves and archives run in the background. |
| **ppd** - background music helper *(work in progress)* | Keeps the music going after PS Play closes; its sound does not come out of the console yet. |
| **pprelaunch** - game watcher | Watches the game you started from PS Play: cheats at launch, play time, and PS Play back when the game closes. |
| **psplay-cheats** - cheat engine | Applies the cheats you turn on to the running game, and restores the original bytes when it stops. |
| **pp-savedata** - save tool | Exports and imports decrypted saves, for backups and the hex editor. |
| **ppweb** - web panel keep-alive | Keeps the web panel reachable while PS Play is closed (when you turn it on in Settings). |
| **ppcast** - receivers bridge *(beta)* | The AirPlay and Miracast receivers, in a separate GPL program. |
| **ppadb** - Android Link *(beta)* | Connects the console to your Android devices. |
| **ppbt** - Bluetooth helper | Bluetooth audio devices (from Ghost-tooth by StonedModder, GPL-3.0). |
| **ppampr** - PKG Matrix back end *(beta)* | LZ4 compression and decompression through the console's AMPR unit, for images and packages. |
| **ps5-backpork** - backport | Used by PKG Matrix to backport an image to your console's firmware. |
| **PSPlay-Helper** - privileges helper | On consoles with kstuff and an ELF loader but without etaHEN, gives PS Play (and the apps PKG Matrix builds) the privileges they need. |
| **mdns-helper** - Spotify pairing | Makes "PS Play" appear among the Spotify devices on your phone (an app on the console cannot answer that discovery itself). |
| **PS5SX3 installer** | Installs the PS5SX3 PlayStation 3 emulator. |
| **psvr2_probe / psvr2_enable** | Early tools of the PSVR2 project *(coming soon)*. |

### Coming soon
- **PSVR2**: a project in the works.

## Requirements
- A PS5 with jailbreak and an **ELF loader** on port 9021 (needed by payloads, the cheat engine, saves and Spotify's
  pairing).
- **ShadowMountPlus** for .ffpkg images and game images; an internet connection for online services.
- **Spotify Premium** for Spotify Connect.
- **Tested firmware: 4.00 to 13.60.**

## Installation
- **As an image**: copy `PSPL47000.ffpkg` (from the release) into `/data/homebrew/`; ShadowMountPlus mounts it.
- **As a folder**: copy the `PSPL47000` folder (from the release, or from this repository) to the console.
- **Updates**: upload the new image from the web panel (Update), then exit PS Play from its Home (Circle, Exit) and
  open it again, so the new image is mounted.
- Your data lives in `/data/ps_play` (settings, accounts, caches and logs).

### The app folder in this repository (`PSPL47000/`)
The folder is the app as it goes on the console. `eboot.bin` is stored with Git LFS: clone with git-lfs, or download
it from its own page.
`sce_module/libc.prx` is **not included**: it is a Sony system module and cannot be redistributed here. Copy it into
`PSPL47000/sce_module/` from another PS5 homebrew app that ships one, then copy the folder to the console.

## FAQ

**Is PS Play a jailbreak or an exploit?**
No. PS Play is an application for consoles that are already jailbroken. It does not jailbreak anything by itself.

**Which firmware does it work on?**
It has been tested from 4.00 to 13.60. It needs a working jailbreak; some features also need the ELF loader.

**Do I need a PC?**
No. Everything works from the console; the phone is optional (typing, sign-ins, links and logs through QR codes).
A PC is only needed for Moonlight (game streaming from your PC) and Remote Desktop.

**Where does PS Play keep its data?**
In `/data/ps_play` on the console: settings, accounts (encrypted), caches, downloads and logs.

**A service will not sign in. What can I do?**
Check the date and time of the console (a wrong clock breaks secure connections), try the sign-in through the QR code
on the phone, if it doesn't work then send the logs (see [Reporting a bug](#reporting-a-bug)).

**Video stutters or does not start.**
Most often it is the network or the source. Try another source or quality; for IPTV and live streams, wired Ethernet
helps. If it keeps happening, send the logs right after it happens.

**Why is the browser slow on some sites?**
The browser is **work in progress**: it is being rebuilt from scratch inside PS Play. Many modern sites are heavy;
the mobile versions of sites (the default) and reader mode help.

**Can I add my own games and apps to the Shop?**
Yes: add your own catalogues in the Shop, or catalogues published by other PS5 projects.

**Does PS Play include games, BIOS or copyrighted content?**
No. PS Play does not include or host any games, BIOS files, firmware or keys.

**How do I update?**
Open **Settings → App info** and press **X** on the **Update** row: PS Play checks its official
[GitHub releases](https://github.com/MounirHero/PS-PLAY-App/releases), and downloads and installs the newest version.

## Reporting a bug
A good report gets fixed much faster. Please open an issue with:
1. **Your PS Play version** (Settings, top of the list) and **firmware**.
2. **What you did, what you expected, what happened** — step by step.
3. **The logs**: Settings › System › Logs, or scan the QR code there to **download them on your phone** (`psplay-logs.tar`).
   Send them right after the problem happens.
4. A **photo or screenshot** if something looks wrong.

Logs never contain your passwords, tokens or keys (see below), so they are safe to share.

You can also ask for help on the **[Discord server](https://discord.gg/3Ce2jft2H)**.

## Privacy and security
- **Your accounts stay on your console.** Passwords, tokens and keys are stored only in `/data/ps_play`, **encrypted**
  (AES-256) with a key created on and kept by your console.
- **Never in the logs.** Credentials are masked in every log and report.
- **No analytics, no tracking.** PS Play does not collect or send any data about you. It only talks to the services
  you choose to use, and to the catalogues you add.
- **The phone panel stays at home.** The web panel and the QR pages work only on your local network.
- **Sign out anytime**: every service has *Options › Sign out*, which deletes its saved credentials.

## Roadmap
Planned (order may change):
- [x] **Built-in updater**: download and install new versions from the app.
- [ ] **Shop**: automatic fallback to another source when a link is dead, and link checking before downloading.

- [ ] **Browser**: faster pages and better compatibility.
- [ ] **Background music helper**: the music's sound out of the console while PS Play is closed.
- [ ] **PSVR2**: a project in the works.
- [x] **OneDrive**: sign-in with PS Play's own Microsoft app.
- [x] **Crash recovery**: reopen PS Play where you were after a crash, with a one-press log report.
- [x] **First-start detection** of the console's tools (loader, ShadowMount, storage, network); the first-start setup that uses it is being finished.

Being researched:
- [ ] **Steam Remote Play** without a PC-side streaming server.

## Credits and origins

PS Play stands on the work of many people. Thank you to all of them.

### The people behind PS Play
| Who | Contribution |
|---|---|
| **[InsideMatrixDev](https://ko-fi.com/insidematrixdev)** | **PS Play**: design, development and integration of the whole app; every feature not listed below, and the clients of the other services rebuilt and adapted for PS Play |
| **[KINGDKAK](https://github.com/KINGDKAK)** | **[ProsperoPlayer](https://github.com/KINGDKAK/ProsperoPlayer)**, the media player PS Play was originally based on |
| **[Swordpdf](https://github.com/Swordpdf)** | **[PS5SX2](https://github.com/Swordpdf/PS5SX2)** (PlayStation 2 on the PS5), installed from PS Play; suggested BlackBearReloaded's project as the base of PS Play Native GL |
| **[BlackBearReloaded](https://github.com/blackbearreloaded)** | ps5-homebrew-ui (the native UI base of PS Play), [ps5-opengl](https://github.com/blackbearreloaded/ps5-opengl), [PS5 Native App Boilerplate](https://github.com/blackbearreloaded/ps5-native-app-boilerplate), [ps5-at9-converter](https://github.com/blackbearreloaded/ps5-at9-converter) |
| **[Stuey-81](https://github.com/Stuey-81)** | **[Nuvio Portable](https://github.com/Stuey-81/Nuvio-Portable)**, from which PS Play's Stremio and Nuvio support were derived |
| **[nexgen999](https://github.com/nexgen999)** | The Shop's **PS5 payload catalogue** ([evoX-CoreOS](https://github.com/nexgen999/evoX-CoreOS)) and **homebrew app catalogue** ([PS5-Repository-List](https://github.com/nexgen999/PS5-Repository-List)) |

### Cloud gaming
| Component in PS Play | Origin | Author |
|---|---|---|
| Xbox Cloud Gaming stream (WebRTC session, input, audio/video) | [PSBox Cloud Gaming — xbox-cloud-gaming-ps5](https://github.com/RafaelNGP/xbox-cloud-gaming-ps5) | RafaelNGP |
| GeForce NOW client | [OpenNOW](https://github.com/OpenCloudGaming/OpenNOW), [OpenNOW-PS5](https://github.com/OpenCloudGaming/OpenNOW-PS5) / [Portablelle/OpenNOW-PS5](https://github.com/Portablelle/OpenNOW-PS5) | OpenCloudGaming, Portablelle |
| Moonlight client | The open [Moonlight](https://moonlight-stream.org/) game streaming protocol (works with [Sunshine](https://github.com/LizardByte/Sunshine)) | Moonlight Game Streaming Project; LizardByte |

### Media and music
| Component in PS Play | Origin | Author |
|---|---|---|
| Spotify Connect (Spot5) | [cspot](https://github.com/feelfreelinux/cspot), via the fork by [philippe44](https://github.com/philippe44/cspot) | feelfreelinux & alufers; philippe44; PS5 port **Spot5** by [abhi245y](https://github.com/abhi245y) |
| Stremio | [Stremio](https://www.stremio.com/) addon protocol | Stremio team |
| Nuvio | [Nuvio Portable](https://github.com/Stuey-81/Nuvio-Portable) | Stuey-81 |
| Video decoding | [FFmpeg](https://ffmpeg.org/) | FFmpeg developers |
| Hardware video decoding *(beta)* | ProsperoWeb's sceVideodec2 decoder (it credits VLC for PS5, the Stremio PS5 port and OpenNOW-PS5) | ProsperoWeb developers |
| Spotify Connect: session, pairing and browsing | [Spot5](https://github.com/abhi245y/spot5) | abhi245y |
| Bluetooth (Ghost-tooth) |  by StonedModder (https://github.com/StonedModder?tab=repositories)

### Receivers
| Receiver | Origin | Author |
|---|---|---|
| AirPlay | forked from [MirrorPSX](https://github.com/seregonwar/MirrorPSX), built on [UxPlay](https://github.com/FDH2/UxPlay) | seregonwar; UxPlay contributors |
| Miracast | PS Play's own (the ppcast bridge), after the Wi-Fi Display R2 and Microsoft MS-MICE specifications | InsideMatrixDev |
| YouTube Cast | PS Play's own: DIAL discovery and YouTube's Lounge protocol | InsideMatrixDev |
| FCast | PS Play's own receiver of the [FCast](https://fcast.org) protocol (MIT) | FUTO (protocol) |
| DLNA renderer | PS Play's own UPnP AV MediaRenderer | InsideMatrixDev |

### Emulators
| System | Core | Author |
|---|---|---|
| NES | [FCEUmm](https://github.com/libretro/libretro-fceumm) | FCEU / FCEUmm and libretro contributors |
| Game Boy / Color | [Gambatte](https://github.com/libretro/gambatte-libretro) | sinamas and contributors |
| Master System, Mega Drive / Genesis | [Genesis Plus GX](https://github.com/ekeeke/Genesis-Plus-GX) | Eke-Eke and contributors |
| Atari 7800 | [ProSystem](https://github.com/libretro/prosystem-libretro) | Greg Stanton and contributors |
| PlayStation | [PCSX ReARMed](https://github.com/libretro/pcsx_rearmed) | PCSX / PCSX ReARMed contributors |
| PlayStation 2 (installer) | [PS5SX2](https://github.com/Swordpdf/PS5SX2), built on [PCSX2](https://github.com/PCSX2/pcsx2) | Swordpdf; PCSX2 team |
| PlayStation 3 (installer) | PS5SX3 | PS5SX3 developers |
| RetroArch (installer) | Mihawk's RetroArch for the PS5 (33+ cores), built on [RetroArch](https://github.com/libretro/RetroArch) | Mihawk; libretro team |

### Browser
The browser is being rebuilt from scratch for PS Play (*work in progress*); its components will be credited here.

### Platform and tools
| Component | Origin | Author |
|---|---|---|
| PS5 payload SDK | [ps5-payload-dev/sdk](https://github.com/ps5-payload-dev/sdk) | John Törnblom and contributors |
| PacBrew packages | [ps5-payload-dev/pacbrew-repo](https://github.com/ps5-payload-dev/pacbrew-repo) | ps5-payload-dev |
| SharpProspero, UFS2Tool | [SharpProspero](https://github.com/SvenGDK/SharpProspero), [UFS2Tool](https://github.com/SvenGDK/UFS2Tool) | SvenGDK |
| MkPFS | [MkPFS](https://github.com/PSBrew/MkPFS) | PSBrew |
| **Voice commands (speech recognition)** | [whisper.cpp](https://github.com/ggml-org/whisper.cpp) (OpenAI Whisper, on-device) | Georgi Gerganov and contributors; OpenAI (Whisper model) |
| Spotify discovery (mDNS) | [mdnsd / mdnssvc](https://github.com/troglobit/mdnsd) | Tobias Blomberg and contributors |
| QR codes | Minimal QR encoder, based on [QR Code generator](https://www.nayuki.io/page/qr-code-generator-library) | Project Nayuki |
| Fonts | [Inter](https://github.com/rsms/inter), [Montserrat](https://github.com/JulietaUla/Montserrat) | Rasmus Andersson; Julieta Ulanovsky |
| Font baking, audio decoding | [stb](https://github.com/nothings/stb) | Sean Barrett |

### Online services
PS Play talks to the public APIs of many services (YouTube, Twitch, Kick, Dailymotion, Odysee, Jellyfin, Plex, Emby,
Trakt, Simkl, AniList, MDBList, Real-Debrid, AllDebrid, TorBox, Premiumize, Last.fm, ListenBrainz, Jamendo, Radio
Browser, Podcast Index, gPodder, MangaDex, Project Gutenberg, OneDrive, MEGA, Steam, Xbox,
NVIDIA). All trademarks belong to their owners; PS Play is not affiliated with or endorsed by any of them.

> The full list of components, versions and licence texts is in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

## Support the project
If PS Play is useful to you, you can support its development:
- **Ko-fi**: [ko-fi.com/insidematrixdev](https://ko-fi.com/insidematrixdev)
- **Solana (SOL)**: `Esd5LdC6HjvHYWJrufrH2FessgLRyupHVSKbHdLC3Bna`

## Licences
PS Play includes components under different licences, among them **GPL-3.0** (cspot / Spot5, OpenNOW, PSBox Cloud
Gaming, UxPlay in the ppcast receiver bridge, ProsperoWeb's hardware video decoder), MIT, BSD and OFL (fonts). Where GPL code is included, PS Play's corresponding source code is
published under the same terms. <!-- TODO: PS Play's own licence -->

## Disclaimer
PS Play is an independent homebrew project, not affiliated with Sony Interactive Entertainment, Microsoft, NVIDIA,
Valve, Spotify, Google or any other company named here. Use it only with content you have the right to access.
