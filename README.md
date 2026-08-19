# English Speaking Coach

A daily 30-minute English speaking practice dashboard, focused on speaking in work meetings.

Live page: https://momo-zhan.github.io/english-speaking-coach/

## Structure

- `index.html` — dashboard shell; renders everything and fetches lessons at runtime
- `lessons/index.json` — list of lesson dates, newest last
- `lessons/<YYYY-MM-DD>.json` — one lesson per file

To add a lesson: write a new `lessons/<date>.json` and append its date to `lessons/index.json`.

All scenarios are synthetic practice material written for language training.
