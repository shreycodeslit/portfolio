# Shrey Gupta — portfolio

My personal site: a 3D, light/dark portfolio built as one static page (HTML, CSS, vanilla JS and Three.js).

**Live:** https://shreygupta.vercel.app

## Editing

Everything you'd normally change lives in the `SITE` block near the top of the main `<script>` in `index.html`:

| Setting | What it does |
| --- | --- |
| `linkedin`, `leetcode` | Shows the matching button in the contact section |
| `web3formsKey` | Turns on the contact form; messages arrive by email ([web3forms.com](https://web3forms.com)) |
| `resume` | Set to `resume.pdf` and add that file here to show a Résumé button |
| `live` | Live links for each project |

Project screenshots are in `assets/projects/`.

## Deploying

Import this repo on Vercel as a static site: no build command, output directory is the repo root. `vercel.json` sets clean URLs, caching and security headers; `404.html` is the not-found page.
