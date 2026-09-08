# INCHY Shopify theme

Custom Dawn-based storefront for INCHY. The homepage is built from editable Shopify sections and follows the approved monochrome, clinical editorial direction.

The connected `main` branch is the live Shopify theme. Requested theme changes can be uploaded through GitHub without manual file uploads. Product facts, policies, payments and shipping settings are managed separately in Shopify.

## Store setup

In Theme settings → INCHY product & directions, select the main product and enter the confirmed serving amount, directions and storage instructions. When exactly one product is published to the Online Store, the homepage and Shop navigation can select it automatically. A product selected in the homepage section takes precedence for that section. Prices, availability, variants and checkout come from Shopify. Products, subscriptions, payments, delivery and taxes are not created by installing the theme.

The product page uses the store product description for confirmed ingredients, label information and other product details. Optional product metafields `custom.pack_size` and `custom.servings_per_pack` appear when populated. No serving amount, price, shipping timeframe or subscription discount is invented by the theme. Add shipping, return, privacy and terms policies in Shopify; their links appear automatically when populated. Confirm the store's sender/contact email before accepting contact enquiries.

## Homepage and guides

The homepage has a compact hero, short product/research/routine/origin introductions, a purchase section and FAQs. Longer explanations are served through Shopify alternate index templates, so no separate admin Page records are required:

- `/?view=research`: original study, plain-language explanation and limitations.
- `/?view=how-to-use`: label-led directions, mixing ideas, storage and suitability information.
- `/?view=support`: policy links and a native Shopify contact form.

Each guide has its own title, description and canonical URL. Homepage metadata has INCHY defaults while preserving a store-provided custom title/description. The contact form uses Shopify's native submission handling and sends enquiries to the store's configured email; it does not use an external form service.

The research source is Zhang et al., 2023, *Isolation and identification of dipeptidyl peptidase-IV inhibitory peptides from Sacha inchi meal*, DOI `10.1002/jsfa.12464`, PubMed `36692392`. Its abstract was checked for the laboratory findings described on the site. This is not a human trial of finished INCHY and does not establish product effects on GLP-1, appetite or weight. Nutrition figures from early design drafts are no longer displayed in the hero; use verified finished-product label information in the product description.

The pouch image is the unmodified original landing-page asset supplied as the packaging reference. Its packaging and label are not independently verified against finished inventory. The routine and botanical images remain AI-generated concept assets, not a verified usage demonstration or an authenticated botanical specimen. Approve assets against real product materials before launch.

## Shared brand assets and direct updates

`assets/inchy-wordmark.svg` preserves the outline of the large wordmark in the supplied September 8 reference screenshot, without depending on a substitute system font. `snippets/inchy-logo.liquid` renders the standalone wordmark in the header, hero and footer. Inline brand mentions use plain uppercase INCHY in the surrounding font, including headings and Shop buttons. The botanical name “sacha inchi” remains ordinary text. GLP-1 stays uppercase. The four numbered homepage headings share `.inchy-section-title`; the origin heading comes first on both desktop and mobile.

`assets/inchy-pouch.jpg` is the original 928 × 1152 landing-page pouch image, used unchanged by `snippets/inchy-packaging.liquid` in the hero and purchase section. The product page also uses it as a fallback until catalog media is supplied. Shopify catalog media is managed separately in Shopify; upload the approved pouch photograph there for consistency.

Requested changes can be committed directly to `main` through the connected GitHub integration. Shopify syncs that branch to its connected theme; no manual file uploads or GitHub Actions are needed. Theme synchronization is separate from publishing the theme and removing storefront password protection. Preserve Shopify editor commits by reading the latest branch before each update and never force-push.

Based on Shopify Dawn under its included LICENSE.md. No GitHub Actions or automatic import workflow is installed by this transfer.
