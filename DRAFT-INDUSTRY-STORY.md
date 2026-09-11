# INCHY industry-story draft

Approved combined homepage. Keep `draft/industry-story` for review; `main` is the live Shopify integration.

The alternative homepage follows the latest supplied screenshots (IMG_3727 to
IMG_3735), including the founder-series link in the green industry section.
Order: essence, pouch, signed founder conviction, hunger loop, formulation, industry, research, routine, FAQ,
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
- Both email forms use Shopify's native customer/newsletter form, with
  unique IDs, launch tags, consent text, error and success states. Confirm actual
  subscription and double-opt-in behaviour in the Shopify preview.
- Pouch values reproduce the supplied mock-up; this is not a nutrition review.
- The history, lack-of-industry/national-body/market, supplier-refusal and small
  first-run statements are supplied draft copy. Substantiate the scope of these
  statements before publishing; this implementation has not fact-checked them.
- Research limitations remain adjacent to each research claim.
- Instrument Serif is bundled with its SIL Open Font License in assets.

## Editorial commitments

Keep these approved lines:
- “No shared standard for what good looks like, no dependable purchasing a farmer could plan around.”
- “The method stays ours; the difference belongs in your bowl.”

The refusal paragraph ends at “We refused all of it.” The process explanation belongs above it.

Association registration has not been confirmed. The public homepage caption identifies Emilio without printing the proposed full association name. The supplied spelling to verify is “Asociación de Sacha Incheros del Nororiente Colombiano”. Restore the name only after confirmation.

Future industry-section enhancement: show **families under signed contract** after the first contracts are signed. Use documented contracts, count unique families, and record the verification date. No placeholder or estimated count should be displayed now.

The signed injection-versus-seed quote is founder-approved copy. Attribution does not remove the need to substantiate any implied product claims; it is not a legal safe harbour.
