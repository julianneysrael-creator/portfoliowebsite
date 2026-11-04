# Jules Ysrael — Portfolio

Static site: plain HTML/CSS with a little JS. It needs no build step, so it deploys as-is to GitHub Pages, Netlify, or Vercel.

```
index.html            Home
marketing.html        Marketing & Growth
work/*.html           Case studies (Vert, Lazada, CollabConnect, P&G Pampers)
media.html            Media & Hosting
leadership.html       Leadership & Impact
about.html            About
assets/styles.css     All styling
assets/main.js        Mobile menu and scroll fade-ins
assets/img/           Put photos and screenshots here
```

## Before launch: fill these in

Search the HTML for `[` to find every placeholder.

- **SheTalksAsia photos (Leadership & Impact → Volunteering, and Media → on screen):** 2–4 photos of you covering the UN Women leadership event and the SheTalksAsia Summit (live-posting, shooting, on site), plus 1–2 screenshots of posts or stories you made.
- **Design work (Australian software company, Nov 2025 – Mar 2026):** wireframes, the brand book, and the website you created. Send 3–5 screenshots (wireframe → final screens, 1–2 brand book spreads) (website is linked: intrinsicerp.com); they go in the design & product area of the toolkit on Marketing & Growth.

- **About photo (optional):** the About page reuses `assets/img/headshot.jpg`; swap in a different shot if you like.
- **Case studies:** role, timeframe, one outcome number, "What I learned", and 2 visuals per study.
  - Vert: installs/views driven, CPI, renewal rate, negotiation savings, Content Hub time saved, or IG growth.
  - Lazada: 3.3 Megasale GMV/orders, or the sign-up lift from the onboarding redesign.
- **Media:** reel embed, brand video embeds with view counts, Spikers' Turf and B.LEAGUE/FIBA U16 details.
- **About:** your story, bookshelf, podcasts, "Currently", and hobby photos.

Videos: upload to YouTube (unlisted is fine), then replace each placeholder with
`<iframe src="https://www.youtube.com/embed/VIDEO_ID" title="..." allowfullscreen></iframe>`.

Per the brief, hide any page or section that isn't ready rather than publishing it empty.

## Deploy on GitHub Pages

Repo → Settings → Pages → Source: *Deploy from a branch* → pick the branch and `/ (root)`.
