# v1.0.11 - UTF-8 player title fix

## Changes

- Fix mojibake in PotPlayer window titles for Twitch streams with emoji or non-ASCII characters.
- Decode Twitch title metadata from the raw web response stream as UTF-8.
- Keep the v1.0.10 playback stability options and player title support.

## Notes

- This release fixes cases such as `⭐` appearing as `â­` in the player title.
- If PotPlayer's separate yt-dlp extension shows unrelated warning dialogs, check its own `yt-dlp.ini` settings. That extension is separate from this launcher.
