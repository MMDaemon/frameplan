# Privacy

Frameplan runs on your PC. It has no account, no analytics and no tracking.

## What stays on your PC
- Your inventory: read from the file AlecaFrame keeps, never changed, never sent
  anywhere.
- Your in-game name: read from AlecaFrame (the name it last saw) for the profile
  card; never sent anywhere, and not added to feedback (a screenshot you paste
  into an issue yourself can show it: the profile card is at the top left).
- Your page, settings, history and log: in `%LOCALAPPDATA%\Frameplan`.
- The page itself is served only to this PC — unless you turn on **phone
  access**, then also to devices in your home network that scanned its QR code.

## What Frameplan fetches from the internet
Only public game data, never anything about you:

| From | What |
|---|---|
| content.warframe.com (Digital Extremes) | item pictures and game data (Public Export) |
| warframestat.us, WFCD (via GitHub/jsDelivr) | item and drop data, the world state (Baro, Nightwave, fissures …) |
| warframe.market | item prices for the Trading page |
| api.github.com, github.com and its download servers (githubusercontent.com) | whether a new version is out, and the update; feedback you send (see below) |

## Feedback
Feedback is sent only when you send it, as a **public issue on GitHub** in
[MMDaemon/frameplan](https://github.com/MMDaemon/frameplan/issues), under
your GitHub name:

- what you write (the kind, a title, the text),
- the app's version, the page it's about and, if you pick one, the entry (an
  item, a mod, an island ...),
- unless you untick it: that entry's data as the page shows it (counts, sources,
  places) or the page's warnings and filters -- shown under "Show what's
  attached" before you send, never with your in-game name.

Nothing else of your inventory goes with it. To send, you sign in with GitHub once
on the PC (Settings → Feedback): GitHub shows the code Frameplan displays, you
confirm it there — Frameplan never sees your password. Frameplan may then only
open issues in that one repository. The sign-in is kept in Windows' Credential
Manager for your Windows user; *Sign out* removes it, and you can revoke it on
GitHub (Settings → Applications → Authorized GitHub Apps → Frameplan Feedback).

Screenshots are never sent by the app: you can paste one into the issue on
GitHub yourself. A screenshot can show your in-game name; leave it out if you
prefer. GitHub's own [privacy statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement)
applies to what is on GitHub.
