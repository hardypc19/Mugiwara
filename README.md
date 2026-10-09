# Mugiwara storefront
A responsive, dark/pink streetwear storefront inspired by the screenshots you supplied.

## Run locally
1. Install Node.js (18+).
2. In this folder run `npm install` then `npm run dev`.
3. Open the local URL Vite prints.

## Add your logo
Put your logo image at `public/logo.png`. The centre logo rotates continuously. A GC fallback appears until you add your own logo.

## Edit products
Edit the `products` array in `public/app.js`. Product images live in `public/images/`. Prices are demo values based on the screenshots.

## Edit FAQs
Open `index.html` and change the answer text inside each `<details>` section. The plus icon changes to × when expanded.

## Before selling
This is a front-end demo. Cart interactions work locally, but checkout, real orders, inventory, email collection, customer accounts, shipping calculations and payment processing need a backend / Shopify / payment provider. Product photos are crops from your supplied screenshots and can be replaced with clean original product photos.


## Theme
The accent color is purple. Edit the `--pink` and `--pink2` CSS variables in `style.css` to change the accent palette.


## Opening locally
Use `npm install` then `npm run dev` for the full experience. Asset paths are relative so the preview also works better when opened from a local folder.


## New interactions and logo animation
- Product title/details open a quick-view modal with size selector and Add to bag.
- Header controls have glassmorphism styling; search and bag work as demo interactions.
- The logo image itself rotates around its Y-axis (front-facing 3D flip), while its circular halo stays still.
- Put the actual logo at `logo.png` in the project root.
