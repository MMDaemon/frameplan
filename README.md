# Frameplan — Farm planner for Warframe

Frameplan reads your Warframe inventory and shows what to farm next: which
items, parts, Arcanes, mods and resources you still miss, where each of them
drops, the quickest way to get them, and what you can already build.

It runs on your Windows PC, sits in the taskbar's notification area and keeps
a page in your browser up to date while you play.

> **Not affiliated with Digital Extremes.** Warframe and its content are
> trademarks and property of Digital Extremes Ltd. Frameplan is a free,
> non-commercial fan tool. See [NOTICE.md](NOTICE.md).

## What you need

- Windows 10 or 11
- [AlecaFrame](https://alecaframe.com/) installed and signed in: Frameplan reads
  the inventory AlecaFrame keeps on your PC (read-only — it never changes
  anything there and never starts AlecaFrame)

## Install

1. Download `Frameplan-Setup.exe` from the [latest release](../../releases/latest).
2. Run it. It installs for your Windows user only, no administrator rights.
   Windows may warn about an unknown publisher (the setup isn't code-signed):
   choose “More info” → “Run anyway”.
3. Frameplan starts and opens its page at `http://localhost:8765`. Its icon is
   in the taskbar's notification area (right-click it for the menu).

## Updates

Frameplan checks this repository for a new version a minute after it starts, then once a day. In the page's
**Settings** (bottom of the navigation) or the tray menu → **Updates** you
choose: install automatically, tell me when there is one (the default), or off.
Every update is signed; Frameplan only installs one whose signature it can
verify. Your data and settings stay.

## Documentation

- [User guide](docs/user-guide.md): the pages and what they show
- [Settings](docs/settings.md)
- [Privacy](docs/privacy.md): what stays on your PC, what goes online
- [FAQ](docs/faq.md)
- [Changelog](CHANGELOG.md)

## Feedback

Use **Settings → Give feedback** in the app (coming soon). This repository
holds releases and documentation only; its source code isn't public.
