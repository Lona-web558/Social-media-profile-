# Social-media-profile-


# Presence Scanner

A single-file HTML app that cycles your name or username across social platforms — X, YouTube, TikTok, Instagram, and Facebook — opening each one until you press Stop.

## Running it

Open `presence-scanner.html` in any browser. No install, no server, no dependencies.

## Using it

1. Type your name or username into the field.
2. Choose a **mode**:
   - **Search results** — runs the text through each platform's search page. Works well with a full name.
   - **Jump to profile page** — goes straight to `platform.com/username`. Use a bare handle here (no spaces), with or without `@`.
3. Tick the platforms you want included.
4. Pick how long to spend on each platform before moving to the next (3–12s).
5. Press **Start scanning**. Press **Stop** any time to end it.

The radar animation and log on the right show what's currently being scanned and keep a running history for the session.

## Known limitation: pop-ups

Browsers only allow a page to open a new tab automatically in direct response to a click. That means the first search opens on its own, but every scan after that gets blocked as a pop-up — so instead of a silent tab, the log shows an **Open now** link you click manually. This is a browser security rule, not something the app can bypass, but nothing is ever lost: every scan is logged with its link whether or not the tab opened.

## What it doesn't do

This app doesn't scrape or read results from these platforms — it only builds and opens the correct search or profile URL for each one. There's no account access, no API keys, and nothing is stored or sent anywhere; everything runs locally in your browser tab.
