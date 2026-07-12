# Rishabh Kumar — Story Portfolio

A single-page scrolling "story in chapters" portfolio — same idea as the
reference site, rebuilt with your own background and the research-note
visual style from your earlier site.

## Chapters
```
Prologue      Hero
01 About      Background, skills, resume download
02 Plot Points Experience timeline (ARI, Student Council, Medical POC)
03 On the Ground   ARI internship deep-dive
04 The Ledger      Projects, certifications, case competitions (flip cards)
05 Fresh Ink       Insights & LinkedIn writing
06 Off the Clock   Hobbies
Epilogue      Contact
```

## File map
```
index.html       everything lives on this one page, linked by #anchors
css/style.css     all styling (colors are in the :root block up top)
js/script.js      scroll progress bar, reveal animations, counters, nav toggle
assets/           put your resume PDF, report PDF, photos here
```

## Deploy on Vercel (like the reference site)
1. Push this folder to a GitHub repo (any name — e.g. `rishabh-story-portfolio`).
2. Go to vercel.com → **Sign up with GitHub** → **Add New Project**.
3. Import that repo. Vercel auto-detects it as a static site — no build
   settings needed, just click **Deploy**.
4. You'll get a live URL like `rishabh-story-portfolio.vercel.app`
   within about a minute. Every future push to GitHub auto-redeploys.
5. Optional: in the Vercel project → **Settings → Domains**, add a custom
   domain if you buy one later.

(You could also deploy this on GitHub Pages exactly like your earlier
site — Vercel isn't required. Vercel is just what the reference site used,
and it's a one-click GitHub import.)

## Editing content
Search each section for `[EDIT ME]` boxes and `[bracketed placeholders]` —
replace with real numbers, links, and write-ups as you have them. To add
more entries to "The Ledger," copy one `.flip` block and edit the front/back
text.
