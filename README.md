# PantryPilot

A smart pantry inventory and shopping-list dashboard designed to reduce food waste.

PantryPilot keeps a lightweight record of what is already at home, highlights what should be used next, and turns missing staples into a simple shopping list.

## Highlights
- Pantry inventory grouped by category
- Expiring-soon filter
- Shopping list with bought state
- Add pantry items through an accessible dialog
- Local persistence and responsive UI
- No build step and no external credentials

## Run locally

```bash
python3 -m http.server 4173
```

Open http://localhost:4173.

## License
MIT © 2026 Yuin

## Desktop release

The repository includes a portable Windows desktop build. Every push to `main` runs the Windows packaging workflow and publishes a `.exe` to the repository's **Releases** section. The desktop shell loads the same app locally, so it works without an API key or server.

## Android release

An Android 7.0+ build (API 24+) is scheduled for **September 16, 2026 at 10:00 IST**. The same responsive product is packaged with Capacitor as an installable APK and published to the repository's **Releases** section as `v1.0.0`.
