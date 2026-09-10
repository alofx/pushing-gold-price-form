# Pushing Gold pricing sheet

Live: https://alofx.github.io/pushing-gold-price-form/

The sheet collects reusable variation pricing, not a catalog of individual products.

## How to fill it out

- Chains, bracelets and rings each have their own section.
- Choose a metal and name the styles the prices cover.
- Supply the smallest size, largest size and size increase.
- Enter a width range such as 4-36 or a list such as 4, 6, 8. Click Show width rows once. Custom decimal widths and N/A are supported.
- For each width sold, enter the complete smallest-size price and the amount added each size step. Leave other widths blank. Enter 0 only when there is no increase.
- Add another metal rule only when needed. Filled width rows are preserved when changing the width list.
- Use the separate extras table for standard locks, diamonds, rubies, sapphires, emeralds, rush orders and custom options. State the added price, charging method and exact scope. Explain included options and how extras combine so no charge is counted twice.
- Explain exceptional sizes, weight-based pricing and custom products in the notes.
- Download the answers and attach the text file in a message to Adrian. Copy and Print / Save as PDF are also available.

## Behavior

No names, contact fields, currency selector, fulfillment questionnaire or large hero. All input fields have short instructions. The sheet has no backend, third-party scripts or automatic submission. Responses stay in localStorage on the same browser when available.

The text export includes entered pricing rules, extras, scope, missing information and review warnings. Straightforward valid size rules include a derived price list. Rows with exceptions and groups with notes are preserved for review without generating misleading derived prices. Blank prices never become zero. No Shopify data is modified by the form.

Earlier version responses use a separate storage key and remain intact. A download button appears when earlier answers are found. The original PDF is also preserved and linked at the bottom.

`index.html` contains the complete form. No build step or dependencies are required. GitHub Pages serves the main branch.
