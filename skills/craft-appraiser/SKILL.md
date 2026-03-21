# Craft Appraiser Skill

name: craft-appraiser
description: Appraise handmade items for fair market pricing — wreaths, resin art, wood carvings, furniture, paintings, figurines, and more. Researches Etsy, craft fair, and local market comps. Returns material cost estimate, labor, and recommended sell price by channel (Etsy, craft fair, Facebook Marketplace). Ideal for artisans, makers, and small sellers.

## Usage

/appraise <item description> [--location <city/region>] [--channel etsy|fair|local|all]

## Examples

/appraise "grapevine wreath with natural feathers and bird nest, 18 inch" --location "Emerald Isle NC" --channel all

/appraise "resin ocean wave tray, 12x8 inch, teal and white" --channel etsy

/appraise "hand carved wooden bear, 14 inch tall, pine" --location "Asheville NC"

## What it does

1. Analyzes the item description (type, size, materials, complexity, finish)
2. Estimates material costs based on known supply prices
3. Applies industry-standard pricing formulas:
   - Materials × 2 + labor (1hr @ $15) = floor price
   - Materials × 3 = Etsy/retail price
   - Southern Charm method: (materials × 2) × 1.20 = profit price
4. Adjusts for regional market (coastal NC, mountain craft markets, urban vs rural)
5. Returns price range by channel: Etsy, craft fair, Facebook/local
6. Notes what would push the price higher (photography tips, listing copy, seasonality)

## Pricing channels

- **Etsy**: highest price, add shipping note, no Etsy fees baked in (add ~6.5% mentally)
- **Craft fair**: 15-25% lower than Etsy, cash in hand, impulse buy pricing
- **Local/FB Marketplace**: 20-30% lower, fast turnover pricing

## Item types supported

- Wreaths (grapevine, wire, foam, floral, seasonal, natural materials)
- Resin art (trays, coasters, ocean waves, geodes, jewelry)
- Wood carvings & signs
- Painted furniture & home décor
- Macramé & fiber art
- Pottery & ceramics
- Paintings & prints
- Seasonal/holiday décor
- Farm & cottage items (jams, preserved goods — pricing only, not food safety)
- Figurines & sculptures

## Limitations

- Estimates are based on typical material costs and market research, not appraisals for insurance or legal purposes
- Highly custom or one-of-a-kind pieces may warrant higher prices than estimated
- Regional craft market demand varies — treat as a floor, not a ceiling
- Food/consumable items: pricing guidance only, not regulatory advice

## Author

ClawFactory — clawfactory.net
Built for Trish at MaddHatchery 🌿
