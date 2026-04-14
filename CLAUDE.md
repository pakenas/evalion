# Evalion — Shopify Theme

## Theme
- **Base theme:** Shopify Horizon v2.1.1
- **Font:** Inter across all roles — body (400), subheading (500), heading (700), accent (700)
- **Page width:** narrow (90rem)

## Typography
- H1: 56px, H2: 48px, H3: 32px, H4: 24px, H5: 14px, H6: 12px
- Body: 14px, loose line-height
- Headings use tight line-height, no text-transform

## Color Schemes
- **scheme-1 (primary):** white bg, black text, black buttons
- **scheme-2:** light gray (#f5f5f5) bg
- **scheme-3:** sage green (#eef1ea) bg
- **scheme-4:** light blue (#e1edf5) bg
- **scheme-5:** dark (#333) bg, white text

## Design Tokens
- Button border-radius: 0 (sharp corners on buttons)
- Card corner-radius: 4px
- Popover border-radius: 14px
- Badge corner-radius: 100px (pill)
- Input border-radius: 0
- Cart type: drawer
- No card hover effects

## Custom Templates
- `product.men.json`, `product.woman.json` — gendered product templates
- `page.about-us.json`, `page.contact.json` — custom page templates

## Structure
```
assets/       — JS, CSS, SVG icons
blocks/       — Reusable block components (Liquid)
config/       — settings_schema.json + settings_data.json
layout/       — theme.liquid, password.liquid
locales/      — i18n (30+ languages including lt.json)
sections/     — Page sections
snippets/     — Partials and helpers
templates/    — JSON page templates
```

## Deploy
```bash
shopify theme push          # push to store
shopify theme pull          # pull latest from store
shopify theme dev           # local dev server
```
