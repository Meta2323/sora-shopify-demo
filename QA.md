# QA record — 18 November 2026

## Completed
- Parsed all 11 Liquid/HTML files using Shopify's Liquid HTML parser.
- Parsed JSON templates, theme settings, locales and embedded section schemas.
- Shopify Theme Check 4.0.2: 0 offenses.
- JavaScript syntax checks passed for theme and local preview.
- DOM interaction checks passed: variant pricing; sold-out button; quantity; text-safe gift message; bag total; remove and empty state; descending price sorting; bag count reset.
- No secrets, API keys, customer data, tracking code or external network requests in the preview.

## Not completed
- Real browser visual/viewport/keyboard QA: Chromium could not start in this execution environment. No browser screenshots supplied or claimed.
- Shopify upload/theme editor/storefront execution; Liquid runtime with real Shopify objects; product images, native add-to-cart, cart updates and checkout.
- No mobile rendering, accessibility audit, Lighthouse score or cross-browser compatibility result is claimed.
- GitHub source publication is tracked by the repository commit history. No Shopify store publication, real orders or recruiter contact performed.

## Required Shopify acceptance checklist
- Upload as unpublished theme; homepage renders; choose collection and edit hero text.
- Product image/description and all variants render; sold-out variant cannot submit.
- Change variant: price and button update; quantity > 0; message preserved in cart.
- Native add to cart succeeds; update quantity; remove; empty bag; note persists.
- Collection sorting and pagination work on real products.
- Desktop/mobile and keyboard checks; no horizontal overflow.
- Confirm test checkout only with approved test payment setup.
- Confirm recruiter preview access before submitting any link.
