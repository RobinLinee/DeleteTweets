
# DeleteTweets — Bulk Delete Tweets, Retweets, Replies & Likes on X

[![Chrome Web Store](https://img.shields.io/chrome-web-store/v/plolbhegbeapkdmpnbabilmfnknlfbpa?label=Chrome%20Web%20Store)](https://chromewebstore.google.com/detail/plolbhegbeapkdmpnbabilmfnknlfbpa)
[![Users](https://img.shields.io/chrome-web-store/users/plolbhegbeapkdmpnbabilmfnknlfbpa?label=users)](https://chromewebstore.google.com/detail/plolbhegbeapkdmpnbabilmfnknlfbpa)


**Website → [deletetweets.net](https://deletetweets.net)**

DeleteTweets is a Chrome and Edge extension that bulk-deletes your X (Twitter) history — tweets, retweets, replies and likes — with precise filters, backups and archive import. Everything runs in your own browser session. You never hand over a password, and nothing is uploaded to a server just so it can be deleted.

---

## Install

| Browser | Link |
|---|---|
| Chrome | [Chrome Web Store](https://chromewebstore.google.com/detail/plolbhegbeapkdmpnbabilmfnknlfbpa) |
| Edge | [Edge Add-ons](https://microsoftedge.microsoft.com/addons/detail/eppcomaofppllfbbnfibdmodgpjdjlpl) |

---

## What it does

- **Bulk delete tweets** — remove thousands of old posts in one controlled run
- **Delete retweets and replies** — clear reposts and reply chains separately or together
- **Unlike in bulk** — clean out an entire like history
- **Filter before you delete** — by keyword, date range, media type, or engagement threshold
- **Whitelist what you keep** — pin exceptions so a bulk run never touches them
- **Import your X archive** — reach posts far older than the recent timeline window
- **Back up first** — save copies of items and timeline snapshots before a large cleanup
- **Paced deletion** — requests are spaced to mimic normal activity, which lowers the chance X throttles or flags the account mid-run

## How it works

1. Install the extension, open `x.com`, and stay signed in to the account you want to clean.
2. Choose what to remove — tweets, retweets, replies or likes — then add keyword, date and engagement filters, and set your exceptions.
3. Run a controlled deletion. For history beyond the recent timeline window, import your official X data archive (`.zip`) first.

## Privacy

- Runs entirely in your browser using your existing signed-in session
- **No password.** DeleteTweets never asks for your X credentials
- Your posts are not uploaded to any server in order to be deleted
- Manifest V3, no remote code execution

Full policy: [deletetweets.net/privacy](https://deletetweets.net/privacy)

## Pricing

Free tier covers ordinary cleanups. Pro unlocks unlimited runs, archive import, exports and scheduled tasks. Current pricing is on the [website](https://deletetweets.net).

## Languages

English · 中文 · 日本語 · Español · Deutsch · Português · العربية

---

## FAQ

**How do I delete all my tweets at once?**
Install the extension, select "Tweets", leave the filters empty to match everything, and start the run. For an account older than the timeline window X exposes, import your X archive first — otherwise the oldest posts are unreachable from any browser tool.

**Can I delete only tweets from a specific year?**
Yes. Set a date range in the filters. Keyword and engagement filters can be combined with it — for example, everything before 2020 with fewer than 5 likes.

**Will deleting in bulk get my account limited?**
X rate-limits rapid write operations. DeleteTweets paces requests and pauses automatically to stay inside normal-usage patterns, which is why a large cleanup takes time rather than seconds. Running several deletion tools at once defeats this.

**Do I need to give you my password?**
No. The extension acts inside the session you're already signed into. There is no login screen and no credential field anywhere in the product.

**What's the difference between this and a web app?**
A web app needs an OAuth token or your credentials, and your data passes through its servers. An extension works locally on the page you already have open. If a service shuts down, an extension leaves nothing behind on someone else's infrastructure.

**Can I get my tweets back after deleting?**
No — deletion on X is permanent. Use the backup and export features before a large run.

---

## Support

- **Bug reports and feature requests →** [open an issue](../../issues)
- **Email →** help@deletetweets.net

Please include your browser, extension version, and what you were trying to delete. Screenshots help.

## Changelog

Release notes live in [CHANGELOG.md](CHANGELOG.md).

---

## More tools

| Tool | What it does |
|---|---|
| [BskyDelete](https://bskydelete.com) | Bulk delete Bluesky posts, reposts and likes |
| [DeleteTik](https://deletetik.com) | Bulk delete TikTok reposts, likes and videos |
| [DeleteThreads](https://deletethreads.net) | Bulk delete Threads posts and replies |
| [DeleteActivity](https://deleteactivity.com) | Bulk delete Facebook posts, comments and messages |
| [PageVeil](https://pageveil.net) | Blur sensitive data before screen sharing |

---

## Notes

This repository hosts documentation, release notes and the public issue tracker for DeleteTweets. The extension itself is closed source.

DeleteTweets is an independent project and is not affiliated with, endorsed by, or sponsored by X Corp.
