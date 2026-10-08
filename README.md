# racksbrax-europe-concept

Concept mock-up of a European RacksBrax site (dealer-based), by Dual-Stack Studio. For discussion only; not the official site.

- `index.html`: single-file page (images embedded).
- Hero slider with seven slides. Wide windows: next moves the text right and the photo left, previous does the opposite, each photo zooms slowly. Portrait windows (phones): same system as the Dual-Stack Creative hero, with a tall photo set, an edge-to-edge photo, a crossfade and no sideways movement. Swipe, arrows, dots and autoplay (pauses only when the hero is off screen).
- Product names, descriptions and product photos are taken from racksbrax.com. They belong to RacksBrax and are shown only for this concept.
- Vehicle photos are placeholders: Unsplash (Ömer Haktan Bulut, M G, Grant Ritchie) and the northern lights photo, supplied by Dual-Stack Studio (source and licence to be confirmed before any public use).
- Product detail pages: every "Details" button (the 16 range cards, the featured product and the bundle card) opens `#/product/<handle>` inside the same file; the browser back button returns to the range.
  - Bundle #9018 (XD Hitch (Triple) + XD Wall Mount) has a bespoke page: cinematic hero carousel in the same system as the home hero, photo gallery with thumbnails, in-the-box list, "how it works" and "in the field" carousels, a live features diagram (blinking numbered hotspots, text exactly as on the XD Hitch features sheet), specifications, placeholder reviews, FAQ and a sticky buy bar.
  - The other 16 products share one data-driven page in the same style: the description, version names, product codes and tags are the store's own text; indicative euro prices are shown per version (version chips update the code, price and sticky bar); a few photos per product are stored as JSON blobs and only loaded when that page is opened; related products come from the range cards. The Quick Release Awning Hitch page also shows the XD Hitch features diagram.
  - Texts, codes and photos are from racksbrax.com (product pages and the XD Hitch features sheet).
- The range shows 17 real products (16 parts and the bundle) with a featured product and filters. Prices are indicative "from" prices, roughly converted from the Australian price list (1 AUD = 0.62 EUR on 8 Oct 2026, rounded to 5 EUR); each dealer sets the final price. Reviews, dealer names and social handles are placeholders.
- The RacksBrax Europe logo is a recreation for the concept, not the official asset.
- The "Australian Made" triangle (hero eyebrow, footer, product page trust lists) was cut from the logo supplied by Dual-Stack Studio and made transparent. It is a certification trade mark of Australian Made Campaign Ltd, shown here only for the concept; its use on a live site depends on RacksBrax's own licence.
