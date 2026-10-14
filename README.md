# Rasta

Help journalists and creators keep their followers if an account gets blocked.

- **End card for reels.** Adds a short "If this account disappears, follow us here" card to the end of a video, with your backup accounts and a QR code. An optional corner label keeps your backup handle visible through the whole reel.
- **Follow posts.** A story image, a pinned-post caption, a WhatsApp forward message and a bio line, all pointing to your backups.
- **Checklist.** What to set up *before* a ban: a backup account, two-factor login, a channel outside Meta, monthly data downloads.
- Hindi and English.

## Privacy

Rasta is one HTML file. It makes **no network requests**: no server, no account, no analytics, no web fonts or CDN scripts. Video processing happens in the browser. Settings are saved only in that browser's local storage, and "Delete my details" removes them.

There is no list of users anywhere, because there is nothing to sign up to.

## Use it

Open `index.html` in Chrome on Android or Safari on iPhone. Host it anywhere that serves static files (GitHub Pages, Netlify, Cloudflare Pages, your own site), or send the file itself and open it from the phone's Files app. Anyone can host a copy, so blocking one address doesn't stop it.

## Limits

- The video is processed in real time, so a 60-second reel takes about 60 seconds. The screen stays on while it works, and if you switch apps it pauses and carries on when you come back.
- Chrome on Android and Safari on iPhone save MP4. Firefox saves WebM, which Instagram may not accept.
- The output is re-encoded at about 8 Mbps, so quality is good but not identical to the original.
- QR codes hold links up to about 200 characters.

## License

MIT
