# TopVideos.com

**TopVideos.com** is a (currently in-development) destination for **creating, selling, and viewing AI-assisted / AI-generated videos and characters**.

This repository contains the static website pages for TopVideos.com.

## What’s in this repo

- `index.html` — main landing page
- Other pages (if present): `about.html`, `join.html`, `reviews.html`, `watch.html`

## Local development / preview

Because this is a static site, you can open `index.html` directly in a browser, or run a small local web server.

### Option A: Open the file directly
- Open `index.html` in your browser (double-click, or right-click → Open With)

### Option B: Python
From the repo root:

```bash
python3 -m http.server 8080
```

Then visit:

```text
http://localhost:8080/
```

### Option C: Node.js
If you have Node installed:

```bash
npx serve .
```

## Deployment

This repo can be deployed to any static host, including GitHub Pages (if enabled).

## Privacy

TopVideos.com is intended to respect user privacy and not violate it.

## License

MIT