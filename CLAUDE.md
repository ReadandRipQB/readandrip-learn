# readandrip-learn — rules for Claude

This repository is the Read & Rip Football IQ blog: a static Jekyll site published with GitHub Pages. It exists so SEO articles can be published without touching anything else.

## Hard rules

- **Work only in `ReadandRipQB/readandrip-learn`.** Never clone, read, commit to, open pull requests on, or change any other repository — in particular the Read & Rip app repository and `ReadandRipQB/readandripqb`. Never change readripqb.com, the website the app lives on. Linking to it is fine.
- **Every change goes through a pull request. Never push to `main`, never merge, never force-push, never delete branches or files Zach made.** Zach reviews each pull request and merges it himself; merging is what publishes.
- If a task ever seems to need another repository or the app's site, stop and ask Zach.

## How the site works

- Articles live in `_posts/` as `YYYY-MM-DD-slug.md` with front matter: `title` (under 60 characters), `description` (under 155 characters), `category`, `author`.
- The URL is the slug: `https://readandripqb.github.io/readandrip-learn/<slug>/`.
- Layouts are in `_layouts/`, styles in `assets/css/style.css`. Plugins (all GitHub Pages–supported): jekyll-seo-tag, jekyll-sitemap, jekyll-feed.

## Writing rules

- Zach's voice: a coach in a film room. Specific, direct, plain words.
- Accurate football only. If unsure of a scheme detail, leave it out. Diagrams follow Zach's whiteboard convention: guards and tackles as circles, center as a box with an X, everyone else as letters.
- The app runs in any web browser and on Google Play. Never say App Store, iOS or iPhone.
- Never mention QB training, lessons or training prices on this site.
