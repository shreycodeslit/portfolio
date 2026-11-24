# Shrey Gupta — portfolio

My personal site: a 3D, light/dark portfolio built as one static page (HTML, CSS, vanilla JS and Three.js).

**Live:** https://shreygupta-three.vercel.app

## Projects on the site

| Project | What it is | Live | Code |
| --- | --- | --- | --- |
| SayDo | Voice to-do list for English, Hindi and Hinglish, with a tested on-device parser | [saydo-psi.vercel.app](https://saydo-psi.vercel.app) | [saydo](https://github.com/shreycodeslit/saydo) |
| ShaadiOS | Indian wedding planner with an AI agent that answers from your own numbers | [shaadios-xi.vercel.app](https://shaadios-xi.vercel.app) | [shaadios](https://github.com/shreycodeslit/shaadios) |
| Nagrik | Photo to civic complaint for Gurugram, routed to the right department | [nagrik-jet.vercel.app](https://nagrik-jet.vercel.app) | [nagrik](https://github.com/shreycodeslit/nagrik) |
| Atlas | One map for many interests, with links found by embeddings | [atlas-smoky-mu.vercel.app](https://atlas-smoky-mu.vercel.app) | [atlas](https://github.com/shreycodeslit/atlas) |
| HungerBridge | Connects surplus food with nearby NGOs | [hungerbridge.vercel.app](https://hungerbridge.vercel.app) | [frontend](https://github.com/shreycodeslit/hungerbridge-frontend) · [backend](https://github.com/shreycodeslit/hungerbridge-backend) |
| ToneTuner | AI writing assistant on the Claude API | [tonetuner-shrey.vercel.app](https://tonetuner-shrey.vercel.app) | [tonetuner](https://github.com/shreycodeslit/tonetuner) |
| That's How Presidents Kill Time | Jokes, trivia and mini games on public APIs | [presidents-kill-time.vercel.app](https://presidents-kill-time.vercel.app) | [thatshowpresidentskilltime](https://github.com/shreycodeslit/thatshowpresidentskilltime) |

## Editing

Everything you'd normally change lives in the `SITE` block near the top of the main `<script>` in `index.html`:

| Setting | What it does |
| --- | --- |
| `linkedin`, `leetcode` | Shows the matching button in the contact section |
| `web3formsKey` | Turns on the contact form; messages arrive by email ([web3forms.com](https://web3forms.com)) |
| `resume` | Set to `resume.pdf` and add that file here to show a Résumé button |
| `live` | Live links for each project |

Project screenshots are in `assets/projects/`. The "Where it started" section shows the early projects (2022–2023), each live on Vercel with its code on this GitHub account.

## Deploying

Import this repo on Vercel as a static site: no build command, output directory is the repo root. `vercel.json` sets clean URLs, caching and security headers; `404.html` is the not-found page.
