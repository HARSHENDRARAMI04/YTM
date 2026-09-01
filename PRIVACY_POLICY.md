# Privacy Policy — YTM but Better

**Last updated:** September 1, 2026

YTM but Better ("the extension") is a Chrome extension that displays synchronized, line-by-line lyrics for songs playing on YouTube Music, along with an immersive full-screen player experience. This policy explains what data the extension accesses, why, and what happens to it.

## Summary

- The extension does **not** collect, sell, or share any personally identifiable information.
- The extension does **not** track your browsing history, location, or activity on other websites.
- The only data sent off your device is the **song metadata** (title, artist, album) needed to look up lyrics, and — only if you choose to use it — an **optional feedback/report form**.
- Your display preferences (background mode, romanization toggle, etc.) are stored **locally in your browser only** and are never transmitted anywhere.

## What data the extension accesses

### 1. Song metadata (title, artist, album, video ID)

While you use YouTube Music, the extension reads the title, artist, album, and video ID of the track currently playing directly from the YouTube Music page. This is used **only** to:

- Query lyrics-provider services to find and display synced lyrics for that track.

This data is sent to the following third-party lyrics providers as part of that lookup:

- `lrclib.net`
- `lyricsplus.prjktla.workers.dev`
- `lyricsplus.atomix.one`
- `lyricsplus.binimum.org`
- `lyricsplus-seven.vercel.app`
- `lyrics-plus-backend.vercel.app`

Multiple provider endpoints are queried as fallbacks so lyrics can still be found if one provider is temporarily unavailable. These requests contain only the track title/artist/album being looked up — no information that identifies you personally.

These are independent, third-party services not operated by the developer of this extension. Their own privacy practices apply to how they handle the request once it reaches their servers; this extension does not control those services.

### 2. Optional feedback / lyric-report submissions

The extension includes an optional "report an issue" feature (for example, reporting missing or incorrect lyrics). If you choose to submit a report, the following is sent to a form-processing service (`formspree.io`), which forwards it to the developer's email inbox:

- The track title, artist, album, and video ID of the song you're reporting on
- The issue type you selected
- Any free-text note you choose to type in the report form

This is only sent if you actively open the report form and press submit. It is never sent automatically or in the background.

If you type personal information into the free-text note field yourself, that text will be included in the report you send. We recommend not including personal information in that field.

### 3. Locally stored preferences

The extension saves your display preferences — such as your selected background/visual mode (Light, Dark, Dynamic, Rain), romanization toggle, and center-view toggle — using your browser's local storage (`localStorage`). This data:

- Stays on your device
- Is never transmitted to the developer or any third party
- Is only used to restore your preferences the next time you open YouTube Music

## What the extension does NOT do

- It does not collect your name, email address, physical address, or any account credentials.
- It does not track or store your web browsing history.
- It does not access your location.
- It does not monitor your clicks, keystrokes, or activity outside of the YouTube Music page.
- It does not sell or transfer your data to third parties for advertising or any other unrelated purpose.
- It does not use any data to determine creditworthiness or for lending purposes.

## Third-party services used

| Service | Purpose | Data sent |
|---|---|---|
| lrclib.net | Lyrics lookup | Track title, artist, album |
| lyricsplus.* (multiple mirrors) | Lyrics lookup (fallback providers) | Track title, artist, album |
| formspree.io | Optional feedback/report submission | Track metadata, issue type, optional note text (only if you submit a report) |

## Permissions

The extension requests access to `music.youtube.com` in order to inject the redesigned player interface and lyrics display directly into the page. No other websites are accessed or modified.

## Changes to this policy

If this policy changes, the "Last updated" date above will be revised. Continued use of the extension after changes constitutes acceptance of the updated policy.

## Contact

Questions about this policy or the extension's data practices can be sent to: **harshendrapr@gmail.com**
