# INCHY industry-story draft

Branch: `draft/industry-story`. This branch is not connected to the live theme.

The alternative homepage follows the latest supplied screenshots (IMG_3727 to
IMG_3735), including the founder-series link in the green industry section.
Order: essence, pouch, hunger loop, refusal, industry, research, routine, FAQ,
launch signup. The existing process and research guide pages are retained.

The original homepage sections, styles, product data and settings are unchanged.
`templates/index.original.json` preserves the original homepage, accessible at
`/?view=original` within this theme. The alternative has its own layout and CSS.

## Add to Shopify without publishing

Online Store → Themes → Theme library → Add theme → Connect from GitHub.
Select `rdkswhite-create/inchy-shopify-theme`, then `draft/industry-story`.
Preview this new theme. Do not select `main` or publish until approved.

## Checks before public release

- The founder link defaults to Instagram and is editable in the Industry block.
- All three email forms use Shopify's native customer/newsletter form, with
  unique IDs, launch tags, consent text, error and success states. Confirm actual
  subscription and double-opt-in behaviour in the Shopify preview.
- Pouch values reproduce the supplied mock-up; this is not a nutrition review.
- The history, lack-of-industry/national-body/market, supplier-refusal and small
  first-run statements are supplied draft copy. Substantiate the scope of these
  statements before publishing; this implementation has not fact-checked them.
- Research limitations remain adjacent to each research claim.
- Instrument Serif is bundled with its SIL Open Font License in assets.
