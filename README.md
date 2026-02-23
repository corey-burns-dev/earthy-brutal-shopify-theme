# Strata Earth Brutal Theme

## Structure

- `layout/theme.liquid`: global shell + CSS include
- `templates/index.json`: homepage composition
- `templates/collection.json`: collection page composition
- `templates/product.json`: product page composition
- `templates/cart.json`: cart page composition
- `sections/earth-*.liquid`: reusable blocks matching the original layout language
- `assets/earth-brutal.css`: main visual system

## Style Mapping

- Heavy 4px borders and hard drop shadows
- Earth palette (`#f5f1ea`, `#3d2d1f`, `#c67a4a`, `#7a8b5c`, `#c9a87c`)
- Uppercase brutalist typography + monospaced utility text
- Hero split layout, category pills, collection grid, and PDP slab layout

## Included Sections

- `earth-header`
- `earth-hero`
- `earth-categories`
- `earth-featured-collection`
- `earth-main-collection`
- `earth-main-product`
- `earth-main-cart`
- `earth-footer`

## Usage

1. Run `shopify theme dev` in this directory (or upload as a custom theme).
2. In theme editor:
   - Set hero image in **Earth Hero**.
   - Pick collection in **Earth Featured Collection**.
   - Configure footer menus in **Earth Footer**.
   - Tune copy labels/buttons in Header, Collection, Product, Cart, and Footer section settings.
3. Product and collection templates are already wired to the new Earth Brutalist sections.
