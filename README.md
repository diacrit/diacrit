# Diacrit

Bookmarks you can talk to.

Diacrit is a shared queue between your phone and your terminal. Share a link from your phone, discuss it with Claude Code on your laptop.

Diacrit has 5 parts:

1. Phone app (iOS / Android) — share links from any app.
2. API - the private bookmark queue between your phone and the terminal.
3. Claude Code plugin - /diacrit:connect, /diacrit:ls, /diacrit:discuss, /diacrit:recall
4. Menu bar app (Waiting) - shows unread counts, one-click into Claude Code.
5. Website (diacrit.com) - landing page + install.

## Install ( Mac and Linux )

You will need to install Claude Code first. Then grab the IOS or Android app.

Then in your terminal:

```bash
curl -fsSL https://diacrit.com/install.sh | bash
```

## On Mac - This installs:

1. **Diacrit menu bar app** — menu bar app showing unread bookmarks waiting per device.

1. **Claude Code plugin** — adds `/diacrit:connect` and `/diacrit:discuss` commands.

## On Linux - This installs:

1. **Claude Code plugin** — adds `/diacrit:connect` and `/diacrit:discuss` commands (macOS + Linux)

## Both Mac and Linux

You will be prompted to enter the code from the Diacrit mobile app. Just tap [Get code] on your mobile. Your claude terminal session and mobile are now paired. No email, no password.

## How it works

1. Download Diacrit on your [iPhone](https://apps.apple.com/us/app/diacrit/id6759536023) or Android
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
- [iPhone](https://apps.apple.com/us/app/diacrit/id6759536023)
