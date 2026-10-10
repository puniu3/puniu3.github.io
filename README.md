# puniu3 portfolio

One image gallery at `/`: four pinned projects, nine more digital projects, and six board game editions in newest-first order. The old `/more/` URL redirects to the digital section.

The NC2000 card links to its English overview and technology notes at `/nc2000/`. Its image and title open the playable bot.

The `/jade/` case study presents the BGA Studio adaptation of Jade Stone Merchants, a downloadable gameplay recording, and the separate public browser edition. The BGA implementation is awaiting private-alpha deployment.

Serve `site/` with any static HTTP server. All local links are relative, so the same files work at a domain root or under a GitHub Pages project path. No build step, dependencies, JavaScript, analytics, or external fonts are required.

The GitHub Pages workflow runs only through `workflow_dispatch`; pushes do not deploy. Set Pages to use GitHub Actions before running it.

Project images are screenshots of the linked games and box artwork from BoardGameGeek. Sources for the added gallery images are recorded in `ASSET-SOURCES.json`. The MIT license covers this portfolio's HTML, CSS, favicon, and workflow; screenshots, box artwork and gameplay recordings retain the rights of their respective game and asset owners. Jade Stone Merchants artwork and recordings are copyright Curiosity Inc., all rights reserved.

Flyer Dungeon supports English through its in-game language menu. Its current published build does not support an English-language URL parameter.
