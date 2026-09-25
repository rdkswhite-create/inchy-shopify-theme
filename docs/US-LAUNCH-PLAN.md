# INCHY US prelaunch plan

Prepared 25 September 2026. Planning horizon: 13–15 weeks, with US availability expected around late December 2026 to January 2027. Public wording: planned for winter 2026–27, with exact timing confirmed by email.

## Objective

Arrive at launch with a reachable US audience, evidence about which proposition attracts interest, a tested explanation of the product, and an explicit record of how interest changes when people see the launch offer. Actual purchase conversion and acquisition cost become measurable when ordering opens.

Run this work directly for INCHY in the United States. Junglcore is optional practice for filming and execution, not a requirement or a proxy for US demand.

## Customer journey

An ad leads to the dedicated US launch page. The page explains INCHY, shows the real existing pack image, describes the natural taste, and invites a free launch-list signup. It does not take payment, reserve inventory, promise an exact date, or imply that a signup is an order.

The visitor supplies an email, explicitly confirms being in the United States and wanting launch emails, and can optionally select the aspect of INCHY that interests them. Shopify handles the native customer form and its configured subscription/confirmation process. The theme does not independently verify email ownership or turn on double opt-in.

When the commercial offer is approved, enter price, pack size and shipping terms in Theme settings > INCHY launch > Planned launch offer. This displays the offer beside every new launch form and adds an offer-shown tag. Until then, the offer stays blank and registrations are tagged offer-not-shown. Even offer-shown registrations remain expressions of interest, not demonstrated willingness to pay.

## Work schedule

| Phase | Work | Decision or evidence |
| --- | --- | --- |
| Weeks 1–2 | Publish the draft; verify a real signup with an authorised test address; confirm sender and double-opt-in settings; approve the opening offer; establish a capped test budget. Prepare six ads and confirm US lead measurement in the ad account. | A functioning, measurable journey and a baseline. |
| Weeks 3–5 | Screen the three concepts below in small batches against the same page and offer. Use interviews with roughly 10–15 relevant US prospects to understand objections and comprehension. | Which concepts bring relevant, reachable subscribers, and why people hesitate. Interviews are qualitative evidence. |
| Weeks 6–9 | Refine promising concepts, test explanations of taste and use, introduce the approved price/pack/shipping offer if ready. Invite subscribers to answer one short follow-up question at a time. | Offer-shown signup behaviour; objections; continued interest by signup cohort. |
| Weeks 10–12 | Repeat the stronger messages with new US audiences and creatives. Increase recruitment only if lead quality holds and launch readiness supports it. | Whether initial findings repeat; how recruitment costs change with more spend. |
| Final 2–3 weeks | Confirm availability/date, reconfirm launch interest, prepare the opening email and purchase journey. Keep timing provisional until fulfilment is reliable. | A recent, engaged audience ready to receive the opening announcement. |
| Launch and following weeks | Open ordering, attribute purchases to the original signup cohort, measure contribution, fulfilment, refunds and later reorder behaviour. | Real purchase conversion, acquisition costs and repeat behaviour. |

Email content is a recommendation for later execution: welcome and product explanation, practical use and taste, answers to objections, a real progress update, and launch announcement. This change does not send campaigns or create an automatic sequence.

## First creative batch

| ID | Concept | Two initial executions | Question |
| --- | --- | --- | --- |
| c01 | A recognisable appetite/craving situation | Short video; image ad | Does recognition bring relevant people to learn about INCHY? Product-outcome connections require appropriate evidence. |
| c02 | How INCHY fits existing meals | Actual preparation video; simple image ad | Does seeing the product used make it understandable and worth considering? |
| c03 | Why this particular product exists | Founder explanation; product/process image ad | Does the development story create useful trust and interest? |

Use AI for concept development, editing, captions and illustrative variations. Use real material for the product, preparation and customer experiences. AI output is creative material, not consumer research. No synthetic testimonials or simulated customer panels count as evidence.

The initial channel is Meta with US targeting. Use a lead-oriented setup for the waitlist after confirming how the native form is measured. A click is a diagnostic metric. Budget allocation and unequal delivery are not a controlled A/B experiment. Compare concepts directionally first; run controlled comparisons where budget and sample size justify them. An underdelivered ad is untested, not a loser.

## Evidence scorecard

| Measure | Definition and limit |
| --- | --- |
| Recruitment spend | Record actual media spend separately from production and software costs. |
| Landing visits | Sessions at the defined destination, dates and source. Distinguish visits from unique people. |
| Submitted signups | Deduplicated native Shopify customer records associated with the cohort; exclude internal tests and duplicates. Never count a button click as a saved signup. |
| Subscribed / confirmed | Report Shopify's consent state. Use “confirmed” only when email confirmation was actually required and completed. |
| US interest | Self-reported US location through the required checkbox; not independent residence verification. |
| Cost per subscriber | Media spend divided by the defined deduplicated, eligible subscriber count. This is not customer acquisition cost. |
| Stated motivation | Optional answer; disclose the answer rate and that respondents selected themselves. |
| Offer-shown interest | Registrations after the precise offer was displayed. Preserve the offer and page version used. Not orders or proof of payment intent. |
| Continuing interest | Responses and deliberate return actions at a stated interval, plus unsubscribes. Email opens alone are not sufficient evidence. |
| Launch purchases | Actual paid orders, linked to prior signup cohorts where reliable; exclude cancelled/refunded orders as appropriate. |

For a bank or investor, present the source, dates, spend, audience selection, actual denominators, page/offer version, cohort age, positive and negative results, and limitations. Keep cold paid traffic, existing followers, friends, and any incentivised recruitment separate. The results describe the people reached by these tests, not the entire US market. Do not relabel waitlist members as customers, committed revenue or purchase orders, or imply that a lender will accept this evidence on its own.

## Source tracking contract

The form uses Shopify customer tags. JavaScript enriches tags immediately before native submission. Without JavaScript the base cohort, self-reported US status and placement tags still submit; the optional interest control stays hidden and campaign attribution is unavailable.

- Cohort: `inchy-us-prelaunch-v1` plus existing `inchy-us-launch` and `newsletter` tags.
- Geography: `inchy-market-us`, explicitly selected by the visitor.
- Placement: `inchy-placement-homepage`, `inchy-placement-launch-page` or `inchy-placement-product-guide`.
- Offer exposure: `inchy-offer-shown` or `inchy-offer-not-shown`.
- Optional interest: `inchy-interest-satiety`, `inchy-interest-routine`, `inchy-interest-ingredient`, `inchy-interest-curious`.
- No known campaign: `inchy-source-unattributed`. Do not interpret this as proven direct traffic.
- Allowlisted campaign parameters become `inchy-source-*`, `inchy-medium-*`, `inchy-campaign-*`, and `inchy-content-*` tags.

Example first ad destination after publication:

`https://inchy.co/?view=launch&utm_source=meta&utm_medium=paid_social&utm_campaign=us_launch_01&utm_content=c01_video_v1`

Supported source values: meta, facebook, instagram, tiktok, google, email, founder, partner. Supported media: paid_social, organic_social, cpc, email, referral. Campaign IDs: us_launch_01 through us_launch_19. Creative IDs: c01–c03, video/image, v1–v9.

Only these constrained identifiers are copied to supported same-origin links. No arbitrary query strings, click IDs, free text or email addresses are forwarded. No new cookie store, external pixel or analytics provider is installed by this change. Interest answers are stored in the merchant's customer record; they are not explicitly sent to an advertising platform by this component.

Customer tags can accumulate on repeat interactions and do not establish a unique first-touch journey. Deduplicate customer records, keep campaign dates and page/offer versions, and verify actual server-side retention before paying for traffic. This is not a complete multi-touch attribution system.

## Website status and handoff

- Source baseline: published theme `166413533400`, INCHY — Amazon hero layout.
- New Shopify draft: `166423068888`, INCHY — US prelaunch demand test.
- Launch page: existing `?view=launch` route; homepage and product/guide signup forms share the new component.
- Shopify connector permits theme file writes to unpublished themes and blocks publishing/live-theme writes. Publish the named draft from Shopify Admin > Online Store > Themes.
- The draft was duplicated from the current live theme. Existing product facts, imagery and broader brand copy were preserved.
- The opening price/pack/shipping offer remains unset; no amount was invented.
- No paid ads were launched, no test customer was submitted, and no launch emails were sent.

Validation: Shopify Liquid/theme validator passed all 12 changed theme files using the installed validator's bundled reference data (the online reference refresh timed out). JSON, section schemas, JavaScript syntax, translation keys and patch checks passed. Shopify accepted the files. The actual draft rendered successfully. Browser checks verified interest-tag updates, campaign-tag construction, campaign preservation on product links and native required-email validation. A complete authorised signup, confirmation-email delivery and durable customer-tag readback remain required before paid traffic. Small-screen visual QA remains to be completed before publication.

Remaining decisions: opening offer, first paid-test budget, sender/confirmation settings, ad-account access and the final US fulfilment date.
