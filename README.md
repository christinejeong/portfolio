# Welcome to Christine Jeong's Portfolio!
This is my personal portfolio website, designed and developed from scratch to showcase a curated selection of my design and engineering projects.


## Trojan Trade

The portfolio card opens `trojan-trade.html`, a self-contained, responsive marketplace demo. Commit that page, the `trojan-trade/` folder, and the updated `portfolio.html` together. It uses the existing local Satoshi fonts and needs no build step or separate deployment.

To preview locally, serve this directory (for example, `python3 -m http.server 8765`) and open `http://localhost:8765/trojan-trade.html`.

- Search, categories, buy/rent filters, price sorting, saved items, and listing details are interactive.
- Demo listings can be created and removed. Saved items and demo listings persist in this browser when local storage is available.
- Listings and student names are illustrative. Messaging is a preview only; there is no backend, authentication, student verification, payment, or real transaction flow.
- Furniture photos were reused from the original Trojan Trade project. The category illustrations are local SVG assets.

The original separately hosted React project is unchanged; the portfolio now serves this refined static demo directly.
