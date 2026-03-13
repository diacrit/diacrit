# Diacrit

Bookmarks you can talk to.

Diacrit is a shared queue between your phone and your terminal. Share a link from your phone, discuss it with Claude Code on your laptop.

## Install

```bash
curl -fsSL https://diacrit.com/install.sh | bash
```

This installs:

1. **Claude Code plugin** — adds `/diacrit:connect` and `/diacrit:discuss` commands (macOS + Linux)
2. **Diacrit menu bar app** — menu bar app showing queued link counts per device (macOS only, skipped on Linux)

Then pairs your phone with a one-time code. No email, no password.

## How it works

1. Download Diacrit on your [iPhone](https://apps.apple.com/app/diacrit/id6742044953) or Android
2. Tap **Get Code** to get a pairing code
3. Run `/diacrit:connect YOUR_CODE` in Claude Code
4. Share links from any app on your phone — they land in your queue
5. Run `/diacrit:discuss` — Claude Code reads the pages and you talk about them

## Components

| Component | What |
|-----------|------|
| [Claude Code plugin](https://github.com/diacrit/claude) | `/diacrit:connect` and `/diacrit:discuss` commands |
| iOS app | Share Extension + pairing |
| Android app | Share Intent + pairing |
| Diacrit menu bar app | macOS menu bar app ([releases](https://github.com/diacrit/diacrit/releases)) |

## Links

- [diacrit.com](https://diacrit.com)
- [Claude Code plugin](https://github.com/diacrit/claude)
