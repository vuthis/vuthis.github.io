# V U This publishing hub

Public articles, business use cases, comparisons and resources for V U This.

Live hub: https://vuthis.github.io/
Walkthrough library: https://vuthis.github.io/vuthis-screen-guides/
Submit this sitemap index once: https://vuthis.github.io/sitemap.xml
RSS: https://vuthis.github.io/feed.xml

This repository contains publishing assets only. It does not contain the V U This application source or private user/session information.

## Publish another article

Copy an existing article HTML file, choose a unique filename, change its YAML title, description, label, summary, category and dates, and write the new body. Keep hub_page: true. Categories: use-cases, comparisons, resources. Change order to position it on the home page. Keep layout: null and the shared metadata/navigation wrapper.

Commit to main. GitHub Pages builds the page. The home page, related links and RSS pick up its front matter automatically; The sitemap.xml template automatically lists hub pages and PDF/PowerPoint downloads, adds video metadata to watch pages, and directly includes all seven existing guide-library URLs. The root Search Console URL-prefix property covers both locations. Search engines decide when to crawl/index updates.

Do not add a .nojekyll file: automatic navigation, RSS and the sitemap template depend on Jekyll. Watch pages use category videos and video_page metadata; the video directory discovers them automatically. Keep verification files when adding Google/Bing ownership verification.

Pages setup: main branch, root folder. No paid dependencies or custom domain required. Core site styles and an existing public product image are reused.
