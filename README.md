# INCHY Shopify theme

Custom Dawn-based storefront for INCHY. The homepage is built from editable Shopify sections and follows the approved monochrome, clinical editorial direction.

The theme should remain unpublished until product details, nutrition figures, research citations, regulatory copy, policies and checkout settings have been reviewed and completed.

## Preview setup

Connect the main branch as an unpublished Shopify theme. In the theme editor, open the INCHY product section and select the actual store product; prices and availability will then come from Shopify. Products, subscriptions, payments, delivery and taxes are separate Shopify admin setup and are not created by installing this theme.

The homepage nutrition figures and research summary were carried over from design drafts. Verify them against the finished product specification and original paper before publishing. The earlier author/year citation was removed because it has not been verified. Add a verified evidence URL in the INCHY research section settings.

The pouch image is the unmodified original landing-page asset supplied as the packaging reference. Its packaging and label are not independently verified against finished inventory. The routine and botanical images remain AI-generated concept assets, not a verified usage demonstration or an authenticated botanical specimen. Approve assets against real product materials before launch.

## Shared brand assets and direct updates

`assets/inchy-wordmark.svg` preserves the outline of the large wordmark in the supplied September 8 reference screenshot, without depending on a substitute system font. `snippets/inchy-logo.liquid` renders it in the header, hero, footer and visible homepage brand copy. The botanical name “sacha inchi” remains ordinary text.

`assets/inchy-pouch.jpg` is the original 928 × 1152 landing-page pouch image, used unchanged by `snippets/inchy-packaging.liquid` in all three homepage packaging placements. Homepage sections deliberately share this asset rather than using separate image overrides or a different product thumbnail. Shopify catalog media, if added later, is managed separately in Shopify.

Requested changes can be committed directly to `main` through the connected GitHub integration. Shopify syncs that branch to its connected theme; no manual file uploads or GitHub Actions are needed. Theme synchronization is separate from publishing the theme and removing storefront password protection. Preserve Shopify editor commits by reading the latest branch before each update and never force-push.

Based on Shopify Dawn under its included LICENSE.md. No GitHub Actions or automatic import workflow is installed by this transfer.
