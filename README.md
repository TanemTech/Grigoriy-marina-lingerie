# EVA — Lingerie Storefront

Independent design and functional prototype for a mobile-first Russian lingerie store. Not connected to TANEM or its templates or deployment processes.

## Run

Open `index.html` with a local HTTP server (for example `python3 -m http.server 8080`) or deploy as static assets. No build, package manager, external registration, or backend required.

## Available features

- Home page: five distinct, mobile-viewport-size sections (hero, categories, products, collection, buyer guidance)
- Fully responsive desktop/mobile catalog with category, size, colour, and sort filters
- Product details with size and color selection
- Favorites and cart saved in the browser
- Cart with quantity adjustment and subtotal
- Request form UI with name, phone, optional comment, and an order summary (Telegram delivery is not connected yet)
- Lightweight preset help panel for sizing, sets, and ordering (no AI or live chat)
- Compact mobile navigation, accessible search/filter drawers, reduced-motion support

## Content and launch restrictions

All products, prices, images, service details and the EVA name are **design placeholders**. Photos currently reference free-to-use Pexels imagery via external image URLs; replace with original licensed client product photos before a commercial launch. Image subjects do not represent the exact products offered for sale. Do not imply endorsements. Telegram notifications, payments, shipping integrations, tax rules, privacy policy, inventory, backend and real order processing are **not implemented**. The request form is currently a front-end prototype and does not transmit customer data.

No automatic production deployment is configured. Publishing or accepting real orders requires a separate decision and configuration.