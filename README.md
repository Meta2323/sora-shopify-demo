# Sora Gift Studio — Shopify portfolio practice project

Prepared for Jacky Felix Lee on 18 November 2026 with AI assistance.
This is ONE new theme concept, not 2–3 completed client stores. No commercial results, past Shopify employment, or real customers are claimed.

## What is included
- `sora-theme.zip`: theme-only ZIP with Shopify directory structure at the ZIP root.
- `theme/`: editable Liquid source, JSON templates and schemas, CSS, vanilla JS, and original SVG illustration.
- `OPEN_PREVIEW.html`: self-contained version for easy offline review.
- `preview/index.html`: standalone local preview. Double-click to open; no install needed. Keep its companion files in the same folder.
- `sample-products.json`: reference data to enter manually in Shopify; NOT a Shopify import file.
- `QA.md`: checks performed and what still needs testing.
- `PANDUAN.md`: setup instructions in Indonesian.

## Shopify implementation
Custom homepage hero and featured collection sections; merchant-editable headings and collection; collection sorting and pagination; product variant selection with price and availability updates; quantity; gift-message line item property; Shopify-native product/cart forms; cart quantity updates, removal and note; page and 404 templates; responsive styles and keyboard focus/skip link.

The local preview deliberately uses a separate, simulated in-memory bag. It does not run Liquid, persist orders, process payments, or prove Shopify checkout works. It shares theme styles and original artwork, but product data is mocked.

## Install and test
1. Use a Shopify development/test store you control. This package does not create an account, choose a paid plan, or publish a store.
2. In the store theme library, upload `sora-theme.zip` as an unpublished theme. Keep any existing live theme unchanged.
3. Add the three sample products manually, with Signature box / Grande box / Seasonal edition variants. Give the first two variants inventory and mark the seasonal variant out of stock without permitting overselling.
4. Put products in a collection. In the theme editor, select that collection in the Featured section. If using dollar sample prices, first verify store currency is USD; otherwise use your chosen currency and adapt sample prices.
5. Add product images you own. The theme uses Shopify placeholders when no product image exists. `gift.svg` is an original illustration used in the hero, not product photography.
6. Test homepage, collection sort/pagination, product variants, sold-out state, quantities, gift-message properties, cart updates/removal, order note and test checkout in Shopify. Use Shopify test payments only; do not place a real order for portfolio QA.
7. Check theme editor changes, mobile and desktop, keyboard focus, screen reader names and store password page before sharing. Configure policies/shipping separately if ever turning this into a real shop.
8. Capture real Shopify screenshots or copy a preview link and confirm a reviewer can access it. A private source repository is not an accessible portfolio link.

## GitHub
Source is published in the separate `Meta2323/sora-shopify-demo` portfolio repository. Algo Cuan is a separate project. This repository is source code, not a hosted Shopify store. Never upload store passwords, API tokens, customer records or Shopify credentials.

## Honest portfolio description
“Sora Gift Studio — an independent Shopify theme practice project prepared with AI assistance. Includes custom Liquid sections, product variants, gift messaging, collection sorting and cart templates. Shopify installation and testing status: [replace with the actual status].”

Only claim work you can personally explain and demonstrate. Read the files, change a section yourself, and run the Shopify checklist before describing this as a tested Shopify build. There are no installed third-party apps or verified external integrations.

## References
https://shopify.dev/docs/storefronts/themes/architecture
https://shopify.dev/docs/storefronts/themes/architecture/templates/product/overview
https://shopify.dev/docs/storefronts/themes/architecture/templates/cart
