# Claude Phone

Two-way chat with a Claude Code session on your Mac, over ntfy.

Messages are signed with HMAC-SHA256 and carry a timestamp and nonce, so a
captured message cannot be replayed. The page holds no secrets: the topics and
signing key live only in your browser's local storage.

## Setup

1. Host these files on any static HTTPS host.
2. On the Mac: `ntfy-phone config`
3. Open the page, tap the gear, paste the JSON, save.
4. Add to Home Screen for a standalone app window.

Background notifications come from the ntfy app subscribed to the same out-topic.
This page only receives while it is open.
