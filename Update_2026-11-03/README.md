# Parents rebuild 03.11.2026 (UK + DE)

Based on the Category Listings Reports of 03.11.2026. Upload in this order, waiting until each upload is processed:

1. `GB STEP1 DELETE old parents...` / `DE STEP1 DELETE old parents...` - deletes the old parents `UK-Parent-1…5` and `DE-Parent-1` (action Delete / Löschen). Children stay as standalone listings.
2. `GB STEP2 CREATE parents+variations (NO prices)...` / `DE STEP2 ...` - creates 13 new parents per market (`ZAP-UK-P01…13`, `ZAP-DE-P01…13`, Create or Replace) and links all 32 child SKUs to them (parent, theme, variation value). Child rows contain only SKU, product type, action, parent link, theme and the variation value; parent rows hold the parent content. No prices, no sale, no quantity. New SKU names are used because deleted SKUs stay reserved for some time.
3. `GB STEP3 PRICE FEED...` / `DE STEP3 PRICE FEED...` - prices, sale price, qty 10 (only file with prices).
- `B2B_Pricing_and_Audit_2026-11-03.xlsx` - Business Price and 2 / 4 pcs tiers (sheets B2B_feed_UK / B2B_feed_DE), audit, parent map, margin check.
- `Margin_Check_vs_Cost.xlsx`.

## Parents (same numbering in both markets)
| # | Family | Product type | Theme UK / DE | Children |
|---|---|---|---|---|
| P01 | Soap | SKIN_CLEANING_AGENT | SCENT / DUFT | 8 |
| P02 | Face + eye | SKIN_MOISTURIZER | SCENT / DUFT | 6 |
| P03 | Body | SKIN_MOISTURIZER | SCENT / DUFT | 3 |
| P04 | Rosemary hair | SHAMPOO | SCENT / DUFT | 3 |
| P05 | Seed oils | EDIBLE_OIL_VEGETABLE | FLAVOUR / AROMA | 2 |
| P06 | Shampoo | SHAMPOO | SCENT / DUFT | 2 |
| P07 | Conditioner | CONDITIONER | SCENT / DUFT | 2 |
| P08 | Eyelash serum | MAKE_UP | SIZE / GRÖSSE | 1 |
| P09 | Face serum | SKIN_SERUM | SCENT / DUFT | 1 |
| P10 | Nail oil | NAIL_TREATMENT | SIZE / GRÖSSE | 1 |
| P11 | Sunscreen | SUNSCREEN | SCENT / DUFT | 1 |
| P12 | Toner | ASTRINGENT_SUBSTANCE | SIZE / GRÖSSE | 1 |
| P13 | Bronzing oil | SELF_TANNER | SIZE / GRÖSSE | 1 |

## Notes
- Parent ASINs change: the old parent pages disappear and the new parents get new ASINs. Reviews belong to child ASINs and stay.
- Eight `_mfn` SKUs have release date 02.11.2026 in the reports (already passed).
- Prices: Sale = current price (16 `_mfn` rows repriced for >=20% margin at the 4 pcs tier), Your Price = List Price = Sale/0.90, Business = Your Price x 0.90, tiers 2 pcs -5% / 4 pcs -10%, sale Friday 06.11.2026 - 01.05.2027, qty 10.
