Fenrir 0.9.0-beta.1 — first public beta. Windows 10/11, 64-bit.

**Free, every feature unlocked, no card.** In exchange it will have bugs. Some
of this has been proven by running it and some has not; the split is below so
you know which is which before you build a stream around it.

## Install

Unzip anywhere and run `Fenrir.exe`. Your settings, triggers and points live in
`%APPDATA%\Fenrir`, separate from the program, so updating never touches them.

**Windows will warn you.** Fenrir sends synthetic keystrokes and opens network
connections, which is exactly what SmartScreen flags. Until the build is
code-signed you will see that warning.

**You need a free Euler Stream key.** TikTok's live data has to be signed by a
third party. The key is free, takes a minute, and goes in Settings — every
install needs its own.

## Proven by running it

- The live TikTok connection — real viewers, real gifts
- Trigger engine and gift routing: every gift worth 5,000+ coins fires
  something, no redundant overlaps across 752 real gifts
- The gift catalogue — 817 gifts with artwork, and it now refreshes itself
  when it is missing or more than a week old
- Install detection: 17 of 18 folder roots found across three drives
- Overlay builder, live preview, and the local server behind it
- Points, levels, chatbot, TTS, subathon clock, gifter perks
- Event queue — long command chains run whole and in order
- OBS control, dispatched to a real running OBS

## Built, not yet proven in a match

- A long live stream. The connection works; it has not run for hours under
  real gift volume
- Black Ops 1's 55 actions have never fired in a live match
- World at War's points, perks and powerups
- The in-game timer HUD — cause found and fixed, not yet confirmed

## Games

Sixteen games, 329 mapped actions. Black Ops 2 (67) and Infinite Warfare (57)
are tested in a live match. Black Ops 1 (60), Black Ops 3 (49), World at War
(37), Minecraft (20), Valheim (14) and 7 Days to Die (9) are built and deployed
but unproven. Eight more are early.

## Before you install

Game publishers prohibit third-party software that changes how a game behaves,
and that includes this. **Accounts can be banned** — worst in online and
ranked, lowest in offline, solo and private matches. Fenrir also reads TikTok
LIVE by unofficial means, because no official API for it exists, and that may
breach TikTok's terms. It connects as an anonymous viewer: it never asks for
your password and cannot post as you.

The app shows the full list on first run and will not set anything up until it
is accepted.

## Telling us what broke

Open an issue, or use the report form inside the app — it attaches the version
and the last error, which beats a description from memory. Feature requests are
just as welcome; during the beta they are most of how the next thing gets
picked.
