# Update 30.10.2026 (UK + DE)

Files:
- `GB Category+Listings_UPDATE_2026-10-30.xlsm`, `DE Category+Listings_UPDATE_2026-10-30.xlsm` — upload to Seller Central (Edit / Partial Update rows; existing SKUs and parents use Edit (Partial Update); new parents use Create or Replace (Full Update)).
- `B2B_Pricing_and_Audit_2026-10-30.xlsx` — Business Price, 2 / 4 pcs tiers, full price audit, parent map.

## Parents (13 per market)
| Family | UK | DE | Product type | Theme (UK / DE) | Children |
|---|---|---|---|---|---|
| Soap | UK-Parent-1 | DE-Parent-2 (new) | SKIN_CLEANING_AGENT | SCENT / DUFT | 8 soaps |
| Face + eye | UK-Parent-2 | DE-Parent-1 | SKIN_MOISTURIZER | SCENT / DUFT | 5 creams + eye balm |
| Body | UK-Parent-3 | DE-Parent-3 (new) | SKIN_MOISTURIZER | SCENT / DUFT | 2 lotions + body cream |
| Rosemary hair | UK-Parent-4 | DE-Parent-4 (new) | SHAMPOO | SCENT / DUFT | shampoo, hair oil, conditioner |
| Seed oils | UK-Parent-5 | DE-Parent-5 (new) | EDIBLE_OIL_VEGETABLE | FLAVOUR / AROMA | black seed, rocket seed |
| Shampoo | UK-Parent-6 (new) | DE-Parent-6 (new) | SHAMPOO | SCENT / DUFT | argan, frankincense |
| Conditioner | UK-Parent-7 (new) | DE-Parent-7 (new) | CONDITIONER | SCENT / DUFT | argan, frankincense |
| Eyelash serum | UK-Parent-8 (new) | DE-Parent-8 (new) | MAKE_UP | SIZE / GRÖSSE | 1 |
| Face serum | UK-Parent-9 (new) | DE-Parent-9 (new) | SKIN_SERUM | SCENT / DUFT | 1 |
| Nail oil | UK-Parent-10 (new) | DE-Parent-10 (new) | NAIL_TREATMENT | SIZE / GRÖSSE | 1 |
| Sunscreen | UK-Parent-11 (new) | DE-Parent-11 (new) | SUNSCREEN | SCENT / DUFT | 1 |
| Toner | UK-Parent-12 (new) | DE-Parent-12 (new) | ASTRINGENT_SUBSTANCE | SIZE / GRÖSSE | 1 |
| Bronzing oil | UK-Parent-13 (new) | DE-Parent-13 (new) | SELF_TANNER | SIZE / GRÖSSE | 1 |

A parent must share the product type of its children, so shampoos and conditioners (and the other single products) cannot be merged into one family without changing their product type.

## Prices (all 32 SKUs, both markets)
Sale Price = current price. Your Price = List Price (UVP) = Sale / 0.90. Business Price = Your Price x 0.90. Tiers from Business Price: 2 pcs -5%, 4 pcs -10%. Sale 30.10.2026 -> 01.05.2027. Quantity 10.

## Check before upload
- New parent rows are copied from an existing parent and filled with title, description, 3 bullets, theme, images and compliance fields taken from the first child. If Amazon still reports missing attributes for a new parent, complete them in Seller Central.
- Eight `_mfn` SKUs carry a release date of 02.11.2026 in both markets. They will not be buyable before that date; the files do not change it.
- `2M-RLDD-XQAY` is filed in a Baby Products shampoo browse node in the UK file; DE price 37.88 EUR is about 1.35x the UK price (other SKUs about 1.19x).
- Business Price, tiers and per-quantity prices are not part of the Category+Listings template.
- The "Images" instruction tab of the original template lost its embedded sample pictures; the Template sheet and all dropdowns/validations are intact.
