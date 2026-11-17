# NORDA — Well Considered Home

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://mrchandrayee.github.io/norda-furniture-store/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org) [![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

A runnable, responsive furniture and home-decor storefront reconstructed from the uploaded **18.93-second** screen recording (720 × 1280, 30 fps).

## Run locally
1. Extract `norda-furniture-store.zip`.
2. Open `index.html` in Chrome, Edge, Firefox or Safari.
3. Browse the product collection, use Quick Add, open the shopping bag, and try the hero slider.
4. No npm install, build tools, API key or backend are required.

Optional local server:
```bash
python3 -m http.server 8000
```
Open `http://localhost:8000`.

## What the source video shows

The visible storefront brand is **NORDA**. The design is a quiet, premium homeware aesthetic:
- Forest-green and warm-cream palette.
- Editorial condensed headlines, restrained mono labels and serif supporting copy.
- Minimal top navigation and a large split hero.
- Lifestyle furniture photography, spacious sections and understated CTA buttons.

### Visible page sequence
1. **Hero** — “QUIET COMFORT”, with a sculptural cream lounge chair, small product rail and three slide indicators.
2. **Latest arrivals** — “DISCOVER OUR LATEST ARRIVALS TODAY”; four product images including a wooden stool, pendant lamp, green cushion and terracotta bowl.
3. **Collection feature** — “EXPLORE PIECES EVERYONE LOVES MOST”, followed by a three-image furniture/interior grid.
4. **Lifestyle banner** — interior photograph with the headline “MADE TO BE LIVED IN”.
5. **Testimonials** — “LIVED PIECES, TRUSTED BY HAPPY HOMES”, with three review cards.
6. **Editorial / community banner** — two people sitting in a warm living room, overlaid with “OWN LESS. CHOOSE BETTER. LIVE IT LONGER.”
7. **Brand footer** — large NORDA wordmark and compact information columns.

## Source-code extraction note

The uploaded video shows the rendered website in a browser, not an editor or readable source-code pane. There are no original HTML, CSS or JavaScript lines that can be reliably transcribed from the recording. The included files are a complete fresh reconstruction based on the visible layout, labels, imagery and interactions. They are not claimed to be the original NORDA repository.

## Implemented features
- Responsive NORDA storefront layout.
- Three-slide auto-advancing hero carousel with manual indicators.
- Product cards with hover zoom and Quick Add.
- Shopping bag drawer with item removal and subtotal calculation.
- Search drawer shell and account drawer shell.
- Collection and lifestyle sections.
- Three testimonial cards and previous/next controls.
- Newsletter form feedback.
- Mobile navigation menu.
- Responsive desktop/tablet/mobile layouts.
- Reduced-motion preference support.

## Files
- `index.html` — storefront markup.
- `styles.css` — full visual system, layout, responsive rules and transitions.
- `app.js` — products, carousel, cart drawer, interactions and demo feedback.
- `README.md` — source observations and run instructions.

## Limitations
This is a frontend-only demo. Product descriptions, prices and sample reviews are illustrative where the video does not show readable details. Images are loaded from Unsplash and require internet access. There is no live inventory, real checkout, payment gateway, authentication, customer account service, search API, order management or CMS integration. Search and account are interface demos; the cart works locally in the current browser session only.

## 👨‍💻 Author

**mrchandrayee** · [GitHub](https://github.com/mrchandrayee)

## 📄 License

[MIT License](./LICENSE)
