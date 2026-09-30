# Privacy Policy — Shorts Blocker

**Effective date:** 2026-09-30
**Contact:** via the Support tab of the extension's Chrome Web Store listing

Shorts Blocker ("the extension") removes YouTube Shorts and can show the dislike count on
YouTube videos. It is built to work with as little data as possible. This policy explains
exactly what the extension stores and what leaves your device.

## Summary

- We do **not** collect, sell, or share personal information.
- We have **no** servers, accounts, analytics, advertising, or tracking of any kind.
- Your settings and statistics stay **on your device**.
- The one network request the extension makes is to look up a video's dislike count (see below).

## What the extension stores on your device

Stored with the browser's local extension storage (`chrome.storage.local`). It never leaves
your device and is removed when you uninstall the extension.

| Data | Purpose |
|---|---|
| Your two settings (Block Shorts, Show dislikes) | Remember your choices |
| Count of Shorts hidden | Shown in the popup |
| The time blocking was last turned on | Shown as "Shorts-free for …" in the popup |
| Recently looked-up dislike counts, keyed by video ID (kept up to 7 days, max 600 videos) | Avoid repeating the same lookup |
| A "pause requests until" timestamp | If the dislike service asks us to slow down, we stop asking for 24 hours |

The dislike cache above is the only record of videos you have opened, it exists only on your
device, and it expires automatically. We do not store the pages you visit, your YouTube account,
your search queries, or anything that identifies you.

## What leaves your device

**Dislike count lookup.** When "Show dislikes" is on and you open a YouTube video, the
extension sends that video's public ID (the `v=` value in the address) to
`https://returnyoutubedislikeapi.com`, a third-party service, and receives the dislike count.
Nothing else is sent: no account information, no cookies, no browsing history, no identifiers
from the extension. As with any web request, that service can see your IP address. Its
handling of data is governed by its own policies; we do not control it. Turning off
"Show dislikes" stops these requests entirely.

**Donation link.** The "Support this project" button opens a PayPal page in a new tab only
when you click it. Any payment is handled entirely by PayPal under PayPal's own privacy
policy. The extension receives no payment or personal information.

The extension makes no other network requests and does not download or run remote code.

## What the extension does on YouTube pages

To hide Shorts, the extension runs on `youtube.com` pages. It reads page elements only to
decide what to hide and to count hidden Shorts. It does not read, record, or transmit page
content, your watch history, or your account details. A network rule redirects Shorts links
(`/shorts/<id>`) to the regular video page; this is evaluated locally by the browser.

## Your choices and control

- Turn either feature off at any time in the popup; the change applies immediately.
- Remove all stored data by uninstalling the extension, or by clearing the extension's data
  in your browser.

## Children's privacy

The extension does not knowingly collect any personal information from anyone, including
children under 13.

## Changes to this policy

If this policy changes, the updated version will be published at the same address with a new
effective date. Any change that would involve collecting new data will be clearly
disclosed in the extension's store listing before it takes effect.

## Not affiliated

Shorts Blocker is an independent project. It is not affiliated with, endorsed by, or
sponsored by YouTube, Google, or Return YouTube Dislike. "YouTube" and "Shorts" are
trademarks of Google LLC.

## Contact

**Contact:** ShortsBlockerEX@gmail.com


