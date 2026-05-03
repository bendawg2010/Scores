# Scores

A free, open-source macOS desktop widget for live sports scores.

> NFL · NBA · MLB · NHL · Premier League — refreshed every 5 minutes when games are live.

**Site:** [scorewidget.pages.dev](https://scorewidget.pages.dev) · **Tip jar:** [Cash App $Dryeetsolutions](https://cash.app/$Dryeetsolutions) · **Sister widgets:** [News](https://github.com/bendawg2010/NewsWidgets) · [F1 Live](https://github.com/bendawg2010/F1Live) · [Sports News](https://github.com/bendawg2010/SportsNews)

## Install

The Scores widget ships inside the same Mac app bundle as my other free widgets — install it once, pick the ones you want from the macOS widget gallery.

```bash
curl -L https://github.com/bendawg2010/NewsWidgets/releases/latest/download/install.sh | bash
```

Then right-click your desktop → Edit Widgets → drag **Scores** onto the desktop.

> **macOS will warn you that the app is from an unidentified developer.** That is normal — I haven't paid Apple's $100/year Developer Program fee. The code is 100% open source, you can audit every line. The `install.sh` script auto-clears the quarantine flag.

## Data source

Pulled from ESPN's public scoreboard API — no auth, no rate limits, refreshed every 5 minutes during live games and every 30 minutes when nothing is on.

## Support

Free forever, MIT-licensed. If you'd like to tip:

- 💸 [Cash App → $Dryeetsolutions](https://cash.app/$Dryeetsolutions)
- ⭐ Star this repo
