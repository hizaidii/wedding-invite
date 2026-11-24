# Mehdi & Sughra · Wedding Invitation

A single-page wedding invitation: tap the wax seal to open the doors, then scroll through the invitation, event timeline with countdown, duas, and a WhatsApp RSVP.

**Live:** https://hizaidii.github.io/wedding-invite/

## Editing

Everything you'd normally change lives in the `WEDDING` settings block near the bottom of [`index.html`](index.html): names, parents, events (dates, times, venues, map links), the RSVP deadline and WhatsApp number, the closing message and the music file.

The link preview text shown in WhatsApp/iMessage is in the `<meta property="og:…">` tags at the top of the file. Those have to be edited by hand.

## Preview locally

```bash
python3 -m http.server 8642 --bind 127.0.0.1
```

Then open http://127.0.0.1:8642/.

## Publishing

GitHub Pages serves the `main` branch from the repository root. Push to `main` and the live link updates within a minute or two.

## Credits

Background music: "Blessed Union" (Islamic wedding instrumental) by Invani Ataya, released as no-copyright music.
