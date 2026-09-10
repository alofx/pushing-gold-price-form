# Pushing Gold product and price form

A phone-friendly, single-file form for Jose to supply Shopify product options and pricing to Adrian at ALO Growth Solutions.

Live form: https://alofx.github.io/pushing-gold-price-form/

## Filling it out

1. Enter your details and currency.
2. Add one product entry per style, metal, and width. Width choices run from 4 through 36 mm, with Other for custom widths.
3. Enter exact size prices, or choose a starting price with a fixed increase if that rule really applies. Add more sizes and products as needed.
4. Describe what the price includes and add optional extra charges with their scope and charging method.
5. Fill in timing and business rules.
6. Download answers and attach the text file in a message to Adrian. Copy and Print / Save as PDF are alternatives.

Every field has a short instruction. Unknown and estimated amounts remain flagged for follow-up. No prices, weights, purities, availability, or policies are supplied as facts by the form.

## Saving and privacy

Answers are stored in localStorage on the same browser when available. The form has no backend and does not submit or upload answers. Download an editable JSON backup to transfer work between devices. Opening a backup requires confirmation before replacing current answers. Downloaded text is a review document, not a Shopify import CSV.

The original PDF is preserved at `Pushing-Gold-Easy-Price-Form.pdf` and linked from the footer. Existing downloaded PDFs remain unchanged.

## Implementation

`index.html` contains the complete UI, styling, and JavaScript. No build, account, third-party scripts, or dependencies are needed. GitHub Pages serves the default branch.

Price-rule calculations require a valid positive size step and aligned endpoints. Skipped sizes must fall on the supplied steps. Invalid rules are reported rather than used to generate a price list. Calculated prices do not imply owner approval.
