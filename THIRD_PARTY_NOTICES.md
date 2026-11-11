# Third-party notices

PS Play is built on the work of many open-source projects. This file lists the third-party components it includes or
links against, where they come from and their licence. Where a component is under the GPL, PS Play's corresponding
source code is made available under the same terms (see [Licence](#licence-of-ps-play) at the end).

Components are grouped by licence; each appears once. A version is given where PS Play uses a specific one. Everything
listed here is part of the distributed PS Play — the app itself or one of the payloads it ships (`assets/payloads`) —
unless it is marked otherwise. Checked against the source tree, the libraries linked into `eboot.bin` and the shipped
payloads for **v1.005 build 97**. Prebuilt libraries come from **PacBrew v0.40.2**
(https://github.com/ps5-payload-dev/pacbrew-repo, build recipes under GPL-3.0; each library keeps its own licence).

---

## GPL / AGPL (copyleft)

PS Play links against the following components. Because of them, PS Play as a whole is distributed under the
**GPL-3.0-or-later** and its complete corresponding source is published.

| Component | Used for | Origin | Author(s) | Licence |
|---|---|---|---|---|
| **ps5-homebrew-ui** | PS Play's native UI base | BlackBearReloaded (the original repository is no longer online) | BlackBearReloaded | GPL-3.0-or-later (as stated in its source headers) |
| **ProsperoPlayer** | the project PS Play was originally based on | https://github.com/KINGDKAK/ProsperoPlayer | KINGDKAK | GPL-3.0 |
| **PS5 Payload SDK** | CRT and kernel helpers (src/psplay/sdkcrt); **make_fself.py**, ported to C in pp_fakelib.c | https://github.com/ps5-payload-dev/sdk | John Törnblom, flatz and contributors | GPL-3.0-or-later |
| **Northstar** browser engine | web browser (ppweb) | https://github.com/nordstjernen-web/northstar-web-browser | Andreas Røsdal | GPL-3.0-or-later |
| **Spot5**, from **cspot** | Spotify Connect | https://github.com/abhi245y/spot5 · https://github.com/feelfreelinux/cspot · fork https://github.com/philippe44/cspot | abhi245y; feelfreelinux & alufers; philippe44 | GPL-3.0 |
| **OpenNOW-PS5** (from **OpenNOW**, MIT) | GeForce NOW streaming (gfnstream) | https://github.com/OpenCloudGaming/OpenNOW-PS5 (original, archived: https://github.com/Portablelle/OpenNOW-PS5) · https://github.com/OpenCloudGaming/OpenNOW | Portablelle; OpenCloudGaming | GPL-3.0 (OpenNOW: MIT) |
| **PSBox** | Xbox Cloud Gaming streaming (xcstream) | https://github.com/RafaelNGP/xbox-cloud-gaming-ps5 | RafaelNGP | GPL-3.0-or-later |
| **moonlight-common-c** | Moonlight game streaming from a PC | https://github.com/moonlight-stream/moonlight-common-c | Moonlight Game Streaming Project | GPL-3.0 |
| **LibVNCClient** (libvncserver) | VNC remote desktop | https://github.com/LibVNC/libvncserver | LibVNC contributors | GPL-2.0-or-later |
| **eSpeak NG** | text to speech | https://github.com/espeak-ng/espeak-ng | eSpeak NG contributors | GPL-3.0-or-later |
| **FFmpeg** | audio and video decoding, encoding, filters | https://ffmpeg.org · https://github.com/FFmpeg/FFmpeg | FFmpeg developers | GPL-2.0-or-later as built (with x264); its sources are LGPL-2.1-or-later |
| **x264** | H.264 encoding, through FFmpeg | https://code.videolan.org/videolan/x264 | VideoLAN and x264 contributors | GPL-2.0-or-later |
| **libtransmission** 3.00 | torrent downloads (ppdl) | https://github.com/transmission/transmission | Transmission project | GPL-2.0 or GPL-3.0 (some files MIT/BSD) |
| **UxPlay**, from **RPiPlay** | AirPlay receiver (ppcast); includes playfair and llhttp (see below) | https://github.com/FDH2/UxPlay · https://github.com/FD-/RPiPlay | F. Duncanh; Florian Draschbacher | GPL-3.0 |
| **FGG-PlayPods** / **FGG-PlayPods-GUI** | Bluetooth audio helper (ppbt) | https://github.com/FGGstore/FGG-PlayPods · https://github.com/menfis911/FGG-PlayPods-GUI | StonedModder (original project); FGGstore; menfis911 | GPL-3.0 |
| **LZ4 Game Compressor** | AMPR LZ4 packing backend (third_party/src/lz4gc), run as PS Play's own payload (ppampr) | https://github.com/gameboy829/PS5-LZ4-Game-Compressor | gameboy829 | GPL-3.0 |
| **ampr_emu** | AMPR runtime (assets/ampr/ampr-runtime.sprx), pack format and packing | https://github.com/drakmor/ampr_emu | drakmor | GPL-3.0-or-later |
| **BackPork** | fakelib loader payload and BPS patches (ps5-backpork) | https://github.com/BestPig/BackPork | BestPig | GPL-3.0 |
| **ps5-sd-tool** | save data mount, key decryption and re-sign (pp-savedata) | https://github.com/c0w-ar/ps5-sd-tool | c0w-ar | GPL-3.0 |
| **ps5upload** | XML game patch parser (src/ppcore/pp_game_patch.c) and its patch rules | https://github.com/phantomptr/ps5upload | phantomptr | GPL-3.0-or-later |
| **MkPFS** | PS5 PFS images: its pack file ported to C (src/ppcore/pp_pfs_pack.c, byte-identical .ffpfsc) | https://github.com/PSBrew/MkPFS | PSBrew | GPL-3.0 |
| **SharpProspero** | PS5 packaging reference | https://github.com/SvenGDK/SharpProspero | SvenGDK | GPL-3.0 |
| **Nuvio Portable** | basis of PS Play's Stremio / Nuvio support | https://github.com/Stuey-81/Nuvio-Portable | Stuey-81 | GPL-3.0 |
| **FCEUmm** | NES core | https://github.com/libretro/libretro-fceumm | FCEU / FCEUmm and libretro contributors | GPL-2.0 |
| **ProSystem** | Atari 7800 core | https://github.com/libretro/prosystem-libretro | Greg Stanton and contributors | GPL-2.0 |
| **PCSX ReARMed** | PlayStation core (also used for the CHD support of the PS Classics converter) | https://github.com/libretro/pcsx_rearmed | PCSX / PCSX ReARMed contributors | GPL-2.0-or-later |
| **Gearsystem** | Master System / Game Gear / SG-1000 core (src/emu/gearsystem, with its bundled miniz and emu2413) | https://github.com/drhelius/Gearsystem | Ignacio Sanchez and contributors | GPL-3.0-or-later |
| **SMS Plus GX** | Master System / Game Gear core (src/emu/sms) | https://github.com/libretro/smsplus-gx | Charles MacDonald, gameblabla and contributors | GPL-2.0-or-later (its Blargg NTSC filter: LGPL, below) |
| **ClownMDEmu** | Mega Drive / Genesis core (src/emu/md) | https://github.com/Clownacy/clownmdemu-core | Clownacy | AGPL-3.0-or-later |
| **PS5SX2**, built on **PCSX2** | PlayStation 2, installed from PS Play (PS5SX3Installer) | https://github.com/Swordpdf/PS5SX2 · https://github.com/PCSX2/pcsx2 | Swordpdf; PCSX2 team | GPL-3.0 |
| **PS5 RetroArch** | launched from PS Play (Emulators > RetroArch) | https://github.com/mihawk-99/PS5_RetroArch · https://www.retroarch.com | mihawk-99; libretro / RetroArch team | GPL-3.0 |

> Full licence texts for these components are included with their source in the corresponding-source repository.

## LGPL / MPL (weak copyleft)

| Component | Used for | Origin | Author(s) | Licence |
|---|---|---|---|---|
| **shairplay** (inside UxPlay) | AirPlay base code (raop, dnssd, httpd) | https://github.com/juhovh/shairplay | Juho Vähä-Herttua | LGPL-2.1-or-later |
| **libplist** | AirPlay property lists (ppcast) | https://github.com/libimobiledevice/libplist | libimobiledevice contributors | LGPL-2.1-or-later |
| **LibOrbisPkg** | param.sfo layout (pp_sfo_write); PS4 fake package builder ported to C in src/ppcore/pp_pkg_build.c (PkgBuilder, PfsBuilder, entries, fake RIF license, PlayGo data, crypto; keys generated into pp_pkg_keys.h from Util/Keys.cs) | https://github.com/OpenOrbis/LibOrbisPkg | Maxton and contributors | LGPL-3.0 |
| **libsmb2** | SMB network shares | https://github.com/sahlberg/libsmb2 | Ronnie Sahlberg | LGPL-2.1-or-later |
| **libnfs** | NFS network shares | https://github.com/sahlberg/libnfs | Ronnie Sahlberg | LGPL-2.1-or-later |
| **LAME** (libmp3lame) | MP3 encoding | https://lame.sourceforge.io | LAME developers | LGPL-2.0-or-later |
| **GNU libiconv** | character set conversion | https://www.gnu.org/software/libiconv/ | Bruno Haible | LGPL-2.1-or-later |
| **cairo** | 2D drawing | https://www.cairographics.org | cairo authors | LGPL-2.1 or MPL-1.1 |
| **Blargg's NTSC filter** (sms_ntsc) | NTSC video filter of the SMS core | http://slack.net/~ant/ | Shay Green (Blargg) | LGPL-2.1-or-later |
| **libdatachannel**, **libjuice** | WebRTC for the cloud gaming streams | https://github.com/paullouisageneau/libdatachannel · https://github.com/paullouisageneau/libjuice | Paul-Louis Ageneau | MPL-2.0 |
| **Chromaprint** | song recognition (audio fingerprints) | https://github.com/acoustid/chromaprint | Lukáš Lalinský | MIT; includes parts of FFmpeg under LGPL-2.1-or-later |
| Any LGPL decoder used by the download / extraction tools | respective projects | respective projects | respective authors | LGPL (notices shipped with the source) |

## MIT / BSD / Apache / zlib (permissive)

| Component | Used for | Origin | Author(s) | Licence |
|---|---|---|---|---|
| **ps5-opengl** | OpenGL runtime | BlackBearReloaded (the original repository is no longer online) | BlackBearReloaded | permissive |
| **PS5 Native App Boilerplate**, **ps5-at9-converter** | app skeleton; presentation audio | BlackBearReloaded (the original repositories are no longer online) | BlackBearReloaded | permissive |
| **scrcpy** server 5.0.1 | Android Link: the phone's screen, audio and input (shipped as scrcpy-server-v5.0.1 with ppadb) | https://github.com/Genymobile/scrcpy | Genymobile and contributors | Apache-2.0 |
| **adb** (Android Open Source Project) | protocol reference for ppadb's pairing and TLS (pairing_auth, pairing_connection, tls) | https://android.googlesource.com/platform/packages/modules/adb | The Android Open Source Project | Apache-2.0 |
| **Mbed TLS** (3.6.6 in ppadb) | TLS and hashing (ppadb; SHA-256 in the app) | https://github.com/Mbed-TLS/mbedtls | Mbed TLS contributors | Apache-2.0 OR GPL-2.0-or-later |
| **BoringSSL** | SPAKE2 pairing in ppadb | https://github.com/google/boringssl | Google and contributors | Apache-2.0 (some files ISC / OpenSSL) |
| **OpenSSL** | TLS | https://www.openssl.org · https://github.com/openssl/openssl | OpenSSL project | Apache-2.0 |
| **libcurl** | networking | https://curl.se · https://github.com/curl/curl | Daniel Stenberg and contributors | curl (MIT-like) |
| **libssh2** | SFTP | https://github.com/libssh2/libssh2 | libssh2 contributors | BSD-3-Clause |
| **libpsl** | public suffix list (cookies) | https://github.com/rockdaboot/libpsl | Tim Rühsen | MIT |
| **libevent** | event loop (torrent downloads) | https://github.com/libevent/libevent | Niels Provos, Nick Mathewson and contributors | BSD-3-Clause |
| **dht** | torrent DHT | https://github.com/jech/dht | Juliusz Chroboczek | MIT |
| **mdnsd / mdnssvc** | mDNS discovery (Spotify Connect) | https://github.com/troglobit/mdnsd | Joachim Wiberg and contributors | BSD-3-Clause |
| **llhttp** (inside UxPlay) | HTTP parsing (ppcast) | https://github.com/nodejs/llhttp | Fedor Indutny and Node.js contributors | MIT |
| **usrsctp**, **libsrtp**, **plog** | WebRTC stack of the cloud gaming streams | https://github.com/sctplab/usrsctp · https://github.com/cisco/libsrtp · https://github.com/SergiusTheBest/plog | sctplab; Cisco Systems; Sergey Podobry | BSD-3-Clause; BSD-3-Clause; MIT |
| **libarchive** | archive extraction (ppfs and the app) | https://www.libarchive.org · https://github.com/libarchive/libarchive | Tim Kientzle and contributors | BSD-2-Clause |
| **zlib** | compression | https://zlib.net · https://github.com/madler/zlib | Jean-loup Gailly, Mark Adler | zlib |
| **Zstandard** | compression | https://github.com/facebook/zstd | Meta Platforms and contributors | BSD-3-Clause (or GPL-2.0) |
| **XZ Utils** (liblzma) | compression | https://github.com/tukaani-project/xz | Lasse Collin and contributors | 0BSD |
| **bzip2** | compression | https://sourceware.org/bzip2/ | Julian Seward and contributors | bzip2 (BSD-like) |
| **LZ4 / LZ4 HC**, **nlohmann/json**, **toml++**, **PicoSHA2** | the AMPR backend | https://github.com/lz4/lz4 · https://github.com/nlohmann/json · https://github.com/marzer/tomlplusplus · https://github.com/okdshin/PicoSHA2 | Yann Collet; Niels Lohmann; Mark Gillard; okdshin | BSD-2-Clause; MIT; MIT; MIT |
| **Expat** | XML parsing | https://github.com/libexpat/libexpat | Expat maintainers | MIT |
| **Lua** | Lua plugins | https://www.lua.org | Lua.org, PUC-Rio | MIT |
| **cJSON** | JSON parsing | https://github.com/DaveGamble/cJSON | Dave Gamble and contributors | MIT |
| **QuickJS** | JavaScript engine (browser) | https://bellard.org/quickjs/ | Fabrice Bellard, Charlie Gordon | MIT |
| **litehtml** | HTML / CSS layout | https://github.com/litehtml/litehtml | Yuri Kobets and contributors | BSD-3-Clause |
| **Capstone** 5.0.9 | x86 disassembler (backport rules), x86 only, in third_party/src/capstone-5.0.9 | https://www.capstone-engine.org | Nguyen Anh Quynh and contributors | BSD-3-Clause |
| **ps5bp** (PS5 Backport Toolkit) | backport engine ported to C (SDK pairs, param.json rule, x86flow, regflow, memsite scanner, rules: tls-atexit, gamepresets-28, savedata-prepare, savedata-mount, wwise-71, frostbite-8ch, mapflex-flags, import retarget) | https://github.com/cherryduck/ps5-backport-toolkit | cherryduck | MIT |
| **LLVM** libc++, libc++abi, libunwind | C++ runtime | https://github.com/llvm/llvm-project | LLVM contributors | Apache-2.0 WITH LLVM-exception |
| **FreeType** | font rendering | https://freetype.org | The FreeType Project | FreeType License (FTL) or GPL-2.0 |
| **HarfBuzz** | text shaping | https://github.com/harfbuzz/harfbuzz | HarfBuzz contributors | MIT (Old MIT) |
| **fontconfig** | font selection | https://www.freedesktop.org/wiki/Software/fontconfig/ | Keith Packard and contributors | MIT-style (HPND) |
| **pixman** | pixel manipulation (cairo) | https://www.pixman.org | pixman contributors | MIT |
| **libpng** | PNG images | https://github.com/pnggroup/libpng | libpng contributors | libpng License 2.0 |
| **libjpeg-turbo** | JPEG images | https://github.com/libjpeg-turbo/libjpeg-turbo | libjpeg-turbo contributors; Independent JPEG Group | IJG, BSD-3-Clause, zlib |
| **giflib** | GIF images | https://giflib.sourceforge.net | Eric S. Raymond and contributors | MIT |
| **libwebp** | WebP images | https://github.com/webmproject/libwebp | Google and contributors | BSD-3-Clause |
| **Ogg**, **Vorbis**, **Opus**, **Opusfile**, **Theora** | audio and video codecs | https://xiph.org · https://github.com/xiph | Xiph.Org Foundation | BSD-3-Clause |
| **stb** (stb_truetype, stb_vorbis, stb_image) | font baking, audio and image decoding | https://github.com/nothings/stb | Sean Barrett | MIT / public domain |
| **QR Code generator** | basis of PS Play's minimal QR encoder | https://www.nayuki.io/page/qr-code-generator-library | Project Nayuki | MIT |
| **whisper.cpp** | on-device speech recognition for voice commands (runs OpenAI's Whisper model) | https://github.com/ggml-org/whisper.cpp | Georgi Gerganov and contributors; OpenAI (Whisper model) | MIT |
| **rcheevos** | RetroAchievements | https://github.com/RetroAchievements/rcheevos | RetroAchievements | MIT |
| **SameBoy** 1.0.4 | Game Boy / Color core (src/emu/sameboy), with SameBoy's own open-source boot ROMs (from the official 1.0.4 release, embedded by tools/sameboy/gen_boot.py) | https://github.com/LIJI32/SameBoy | Lior Halphon and contributors | Expat (MIT) |
| **fixGB** | Game Boy / Color core "gb" (src/emu/gb), the alternative to SameBoy | https://github.com/FIX94/fixGB | FIX94 | MIT |
| **libchdr** | CHD discs for the PS Classics converter (src/ppcore/pp_chd.c, through the copy built for the PS1 core) | https://github.com/rtissera/libchdr | Romain Tisserand and contributors | BSD-3-Clause |
| **SN76496** sound chip (MAME) | sound of the SMS core | https://github.com/mamedev/mame | Nicola Salmoria and MAME contributors | BSD-3-Clause |
| **UFS2Tool** | ffpkg (UFS2) images | https://github.com/SvenGDK/UFS2Tool | SvenGDK | BSD-2-Clause |
| **PS-Classics-fPKG-Builder** | the process the PS Classics converter follows (app layout, emulator configs, GP4 disc files with pfs_compression, content IDs, package names); no code taken | https://github.com/SvenGDK/PS-Classics-fPKG-Builder | SvenGDK | — |
| **GoogleTest** | host tests only, not shipped | https://github.com/google/googletest | Google | BSD-3-Clause |

### Optional cores — personal builds only (licences not compatible with the GPL-3.0)

| Component | Origin | Author(s) | Licence |
|---|---|---|---|
| **Genesis Plus GX** — Mega Drive / Master System / Game Gear core (src/emu/gpgx) | https://github.com/ekeeke/Genesis-Plus-GX | Eke-Eke and contributors | custom, non-commercial |
| **Gambatte** — Game Boy / Color core (src/emu/gambatte) | https://github.com/libretro/gambatte-libretro | sinamas and contributors | GPL-2.0 only |

Their sources are kept in the tree under their own licences, but they are **not built into distributed PS Play
builds**: a program that combines them with GPL-3.0 code cannot be redistributed. `tools/build.sh` builds them only
with PSPLAY_NONGPL_CORES=1 or a local `.personal_build` marker (never part of the published source); such a build is
for personal use only. Without them, Master System / Game Gear / SG-1000 run on Gearsystem, Mega Drive on ClownMDEmu and
Game Boy on SameBoy; the in-app setting switches back to SMS Plus GX and the MIT `gb` core (fixGB). The SMS core uses
MAME's SN76496 (BSD-3-Clause); the CrabEmu (GPL-2.0 only) and Maxim (no licence statement) SN76489 chips were removed.

## Fonts

| Typeface | Origin | Author | Licence |
|---|---|---|---|
| **Inter** | https://github.com/rsms/inter | Rasmus Andersson | SIL OFL 1.1 |
| **Montserrat** | https://github.com/JulietaUla/Montserrat | Julieta Ulanovsky | SIL OFL 1.1 |
| **Bebas Neue** | https://github.com/dharmatype/Bebas-Neue | Ryoichi Tsunekawa (Dharma Type) | SIL OFL 1.1 |
| **DejaVu Sans Mono** | https://github.com/dejavu-fonts/dejavu-fonts | DejaVu fonts team (from Bitstream Vera) | Bitstream Vera licence and public domain |
| **Patrick Hand** | https://fonts.google.com/specimen/Patrick+Hand | Patrick Wagesreiter | SIL OFL 1.1 |
| **Press Start 2P** | https://fonts.google.com/specimen/Press+Start+2P | CodeMan38 | SIL OFL 1.1 |

## Catalogues and content lists (used by permission / their own terms)

| Component | Origin | Author |
|---|---|---|
| Shop **homebrew** catalogue | https://github.com/nexgen999/PS5-Repository-List | nexgen999 |
| Shop **payload** catalogue | https://github.com/nexgen999/evoX-CoreOS | nexgen999 |

## No longer included

Listed for the older releases that still contain them: **NetSurf** and its libraries (libcss, libdom, libhubbub,
libnsfb, libnsgif, libnsbmp, libnsutils, libnspsl, libwapcaplet; GPL-2.0 / MIT) and **Duktape** (MIT), replaced by
Northstar and litehtml; **lexbor** (Apache-2.0); **GhosttoothAPI** by Red (StonedModder), the Bluetooth audio payload,
replaced by ppbt (FGG-PlayPods).

## Project this is based on

PS Play was originally based on **ProsperoPlayer** by **KINGDKAK** (https://github.com/KINGDKAK/ProsperoPlayer,
GPL-3.0), and **SwordPDF** suggested BlackBearReloaded's project as the base of PS Play Native GL.

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
