# lernex

gamified linux / os / networking / bash learning. dark, brutalist, terminal-flavored. built for ppl who are tired of dry tutorials.

by **Prashant Kumar**. progress lives in your browser — no login, no tracking.

## what's inside

- **flashcards** — ~150 cards across filesystem, commands, permissions, processes, OS internals, networking, package managers, bash scripting, text processing, security
- **quiz** — multiple choice with instant feedback
- **terminal** — fake shell where you type real commands against task prompts
- **bash gym** — write actual bash one-liners + scripts (loops, conditionals, sed/awk, parameter expansion, traps, arrays). regex-graded
- **port match** — drag/tap to match common ports to services
- **filesystem explorer** — click-thru directory tree with explanations
- **xp + levels + daily streak** — progress persisted in localStorage

## run locally

just open `index.html` in a browser. no build step. no `npm install`. react + babel load from a CDN, jsx is compiled in-browser.

```bash
open index.html
# or:
python3 -m http.server 8000
# then visit http://localhost:8000
```

## deploy

### vercel (one command)

```bash
npm i -g vercel
vercel
```

answer the prompts (it auto-detects static). that's it.

### vercel via github

1. push this repo to github
2. go to vercel.com/new
3. import the repo
4. framework preset: **Other** (static)
5. build command: leave empty
6. output directory: `./`
7. deploy

## tech

- vanilla html + css + react (cdn) + jsx-via-babel-standalone
- single `data.js` content file (~120kb of curated linux content)
- single `app.jsx` inlined in `index.html`

## author

**Prashant Kumar**

## license

mit. learn freely.
