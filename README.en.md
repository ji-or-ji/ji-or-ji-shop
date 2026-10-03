# Ji's Little Shop (是季不是鸡的小店)

## About

This is 是季不是鸡's little shop — come in and take a rest~

## The Shelf

Right, this is just a shelf, holding links to the little things I have made.

Every project is kept in sync on both **GitHub** and **Gitee**: each title links to the
**GitHub primary repository**, and the "Gitee mirror" at the end of the line points to the
matching Gitee repository. This shop's own Gitee mirror is at
[gitee.com/ji-or-ji/ji-or-ji-shop](https://gitee.com/ji-or-ji/ji-or-ji-shop).

## How to use

Simple: click the **text** to jump to the **matching repository**.

## What's here now

### Apps & tools

[Python Rediscovery Path](https://github.com/ji-or-ji/Python-Rediscovery-Path)  ·  [Gitee mirror](https://gitee.com/ji-or-ji/Python-Rediscovery-Path)
A learning log of rediscovering Python from scratch: a study map, notes and exercises. **In progress.**

[A simple random-song picker](https://github.com/ji-or-ji/random_songs)  ·  [Gitee mirror](https://gitee.com/ji-or-ji/random_songs) _(old version, superseded by the remake below — kept for the record)_
A feature-rich Python CLI random-song picker: song / requester / multi-playlist management, automatic web jump, operation history.

[Random Songs system · remake](https://github.com/ji-or-ji/replace_random_songs_system)  ·  [Gitee mirror](https://gitee.com/ji-or-ji/replace_random_songs_system)
A full rewrite of the original: YAML data, offline-friendly install, a headless CLI mode
(convenient for hooking up with ClassIsland) and a native Windows desktop app (.NET 8 + WinUI 3),
both sharing the same data. See the repository for the full feature list.

[desk-ink · desk e-ink info station](https://github.com/ji-or-ji/desk-ink)  ·  [Gitee mirror](https://gitee.com/ji-or-ji/desk-ink)
ESP32-C3 + a 4.2" e-ink display showing timetable / to-dos / a daily quote / news / illustrations,
built around low power (deep sleep + RTC wake, targeting ~18µA and ~32 days on a 1000mAh battery).
The companion PC tool is also .NET 8 + WinUI 3.
**Not yet verified on real hardware**: code and UI are done (the UI was verified state by state in
QEMU), but no real e-ink panel has been lit up, no real hardware has been connected, and the PCB
is not routed yet.

[yufeng-bot](https://github.com/ji-or-ji/yufeng-bot)  ·  [Gitee mirror](https://gitee.com/ji-or-ji/yufeng-bot) _(a cyber group-mate built on NapCat and Python)_ **development stopped** (its capabilities are now covered by MaiBot plus plugins I wrote myself)
A multi-agent group-chat system built from scratch: persona agents, long-term memory, rich-media
understanding and proactive socialising — an experiment trying to put "a soul" into code.

[UndercoverBot](https://github.com/ji-or-ji/Undercover-Bot)  ·  [Gitee mirror](https://gitee.com/ji-or-ji/Undercover-Bot)
A bot framework that lurks in QQ groups to watch for keywords, warn automatically and collect evidence.
**Currently shelved** (technical feasibility confirmed; the original motivation — coping with harmful
content online — no longer applies). The code is kept for reference; feel free to make use of it.

[ZHAO-watchV2 Slim · CLion edition](https://github.com/ji-or-ji/ZHAO-watch-V2_CLion_Edition)  ·  [Gitee mirror](https://gitee.com/ji-or-ji/ZHAO-watch-V2_CLion_Edition)
The original was a Keil (µVision5) project; this is a rework as a CLion + CMake project (slim version)
for modern development.

[SPIKE project version-control toolkit](https://github.com/ji-or-ji/spike-handler)  ·  [Gitee mirror](https://gitee.com/ji-or-ji/spike-handler)
Unpack / repack .llsp3 files and manage them with Git: repo init & config, one-click SPIKE cache
cleanup, and rollback to any previous version.

[flomo integration plugin](https://github.com/ji-or-ji/open-hanako-flomo)  ·  [Gitee mirror](https://gitee.com/ji-or-ji/open-hanako-flomo)
Adds flomo note writing, import, search and management to Hanako (agent-driven). Apache-2.0.

[Endfield-style LAN device monitor](https://github.com/ji-or-ji/endfield-monitor)  ·  [Gitee mirror](https://gitee.com/ji-or-ji/endfield-monitor)
See how a Windows machine is doing without opening a remote desktop: a C# + Avalonia desktop client
plus a read-only Python collector, reading CPU / memory / disks / network / processes, and keeping an
eye on chosen services and ports. UI style pays tribute to zmd-manager. **In progress.**

### MaiBot / Hanako plugins

[Plugin installer](https://github.com/ji-or-ji/maibot-plugin-installer)  ·  [Gitee mirror](https://gitee.com/ji-or-ji/maibot-plugin-installer)
Installs and enables a finished MaiBot plugin after **admin approval**, requesting that approval in the
originating chat stream; the downstream companion of the [MaiBot × dsh bridge](https://github.com/ji-or-ji/maibot-dsh-bridge).

[MaiBot × dsh bridge](https://github.com/ji-or-ji/maibot-dsh-bridge)  ·  [Gitee mirror](https://gitee.com/ji-or-ji/maibot-dsh-bridge)
Brings DeepSeek Harness into MaiBot: dispatch a task in one line, let dsh finish it in the background,
stream progress back as a merged-forward card, bundle the produced files back to the group, and even
self-schedule recurring jobs.

[Hanako2DSH](https://github.com/ji-or-ji/hanako2dsh)  ·  [Gitee mirror](https://gitee.com/ji-or-ji/hanako2dsh)
Connects the local official DeepSeek Harness into Hana: **watch it work in a tab, hand it a task in one line.**

[MaiBot pretends to watch videos](https://github.com/ji-or-ji/mai-video-adaptive)  ·  [Gitee mirror](https://gitee.com/ji-or-ji/mai-video-adaptive)
Video-understanding plugin: how many frames to sample is decided by the content (not a fixed timer),
paired with speech transcription and handed to a vision model; repeated videos are reused in seconds.
**It never comments on videos unprompted.**

[MaiBot stops spamming emoji](https://github.com/ji-or-ji/maimai-no-more-emoji)  ·  [Gitee mirror](https://gitee.com/ji-or-ji/maimai-no-more-emoji)
Detects emoji in MaiBot's outgoing text, lets an LLM decide whether to swap it, and if so picks a fitting
sticker image from the sticker library to append — fixing emoji crammed into messages that feel off-character.

[Guardian alert](https://github.com/ji-or-ji/guardian-alert-plugin)  ·  [Gitee mirror](https://gitee.com/ji-or-ji/guardian-alert-plugin)
Watches private / group chats for risk signals (group-invite bait, emotional dependence, privacy leaks,
money requests, impersonation, manipulation) and pushes hits to the admin, catching a hijacked bot or an
over-dependent member early.

[Group probation](https://github.com/ji-or-ji/group-probation-plugin)  ·  [Gitee mirror](https://gitee.com/ji-or-ji/group-probation-plugin)
Auto-@-welcomes new members to invite them to talk, and removes those who stay silent past the probation
window (48 hours by default).

[Group awareness](https://github.com/ji-or-ji/group-awareness-plugin)  ·  [Gitee mirror](https://gitee.com/ji-or-ji/group-awareness-plugin)
Senses member changes (join / leave / mute / group name / admin changes) with three handling modes
(fixed template / persona LLM / context injection), and offers tools to query group honours, member
titles, avatars, announcements, mute lists and more.

[MaiBot expense summary+](https://github.com/ji-or-ji/maibot-expenses-summary-plus)  ·  [Gitee mirror](https://gitee.com/ji-or-ji/maibot-expenses-summary-plus)
Turns the day's model calls, replies and cost into a report; on top of the original it adds a custom
price engine, subscription / hybrid billing modes and a manual ledger correction. **Mutually exclusive
with the original.**
