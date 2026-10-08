# Tagalog in 4 Hours

A practical, Taglish-first Tagalog crash course as a single static web page. No build step, no backend, no tracking. Progress and your "15 sentences" are saved in your own browser.

## What's inside

- **Plan** — what to learn first, what to ignore, and the one exercise that matters
- **Step 1 · Flip** — description first, person second; pronouns; *po* and *ba*
- **Step 2 · Verbs** — the `mag-` + English verb shortcut for past, present and future
- **Step 3 · Frames** — ten sentence frames that cover most of a day
- **Step 4 · No** — *hindi*, *wala*, *ayaw*
- **Step 5 · Questions** — question words
- **Step 6 · Your 15** — write and rebuild 15 of your own everyday sentences

Every lesson ends with drills that check your typed answer, give a hint on a miss, and reveal the answer after two tries. A 🔊 button reads the answer aloud if your device has a Filipino voice.

## Host it on GitHub Pages

1. Push this repo to GitHub.
2. In the repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, branch `main`, folder `/ (root)`. Save.
3. After a minute it's live at `https://<your-username>.github.io/<repo-name>/`.

## Run it locally

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

## Editing drills

Drills live in the `DRILLS` object near the bottom of `index.html`. Each one has a prompt (`q`), a list of accepted answers (`accept`, compared case- and punctuation-insensitively), the answer to display (`show`) and a `hint`.
