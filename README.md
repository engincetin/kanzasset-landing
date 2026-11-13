# Kanzasset landing page

Static corporate page for Kanzasset FZCO (pre-licence). One file, `index.html`, plus `assets/`. No build step.

## Run locally

```
python3 -m http.server 8765
```

Then open http://127.0.0.1:8765/.

## Layout

- Desktop (over 900 px wide): the page fits one screen with no scroll, checked from 1920x1080 down to 960x600. Short screens use tighter spacing.
- Tablet and mobile: sections stack and the page scrolls. No horizontal scroll down to 320 px. Safe area insets are respected on phones with a notch.

## Before go live

Compliance approves all content before the page goes live.
