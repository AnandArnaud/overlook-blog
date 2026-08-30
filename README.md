# overlook-blog

The Overlook is a tiny reading/blog site — open a post, subscribe, get in touch.

**Stack:** Plain HTML / CSS / JS (no build step)

It is realistic but intentionally small, and ships with **no product analytics, experimentation, or session-replay wired in** — the user-action handlers just log to the console today.

## User actions worth tracking

open post · subscribe · contact

## Running it

```bash
# static site — no build
python3 -m http.server 8000   # then open http://localhost:8000
```
