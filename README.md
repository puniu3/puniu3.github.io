# puniu3 portfolio

A static portfolio: four selected projects at `/`, eight more at `/more/`, and a BGA case study at `/jade/`.

The `/jade/` case study presents the BGA Studio adaptation of Jade Stone Merchants, a downloadable gameplay recording, and the separate public browser edition. The BGA implementation is awaiting private-alpha deployment.

Serve `site/` with any static HTTP server. All local links are relative, so the same files work at a domain root or under a GitHub Pages project path. No build step, dependencies, JavaScript, analytics, or external fonts are required.

The GitHub Pages workflow runs only through `workflow_dispatch`; pushes do not deploy. Set Pages to use GitHub Actions before running it.

Project images are screenshots of the linked games. The MIT license covers this portfolio's HTML, CSS, favicon, and workflow; screenshots and gameplay recordings retain the rights of their respective game and asset owners. Jade Stone Merchants artwork and recordings are copyright Curiosity Inc., all rights reserved.

Flyer Dungeon supports English through its in-game language menu. Its current published build does not support an English-language URL parameter.
