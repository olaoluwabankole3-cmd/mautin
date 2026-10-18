# Mautin Atelier

A monochrome, mobile-first fashion atelier website with a custom procedural 3D bridal gown built in Three.js.

## What's included
- Black-and-white editorial direction.
- Phone-first layout with swipeable collection cards.
- A large, centred, continuously rotating 3D wedding dress with a shaped sweetheart corset, layered satin skirt, train, subtle lace appliqué, and veil.
- Rotation gently speeds up while the visitor scrolls.
- Responsive navigation, subtle section reveals, and reduced-motion support.
- Instagram / direct-message enquiry links.
- No build step or environment variables; the main website is a single static `index.html`.

## Preview locally
Open `index.html` in a browser. An internet connection is required for Google Fonts, the editorial imagery and Three.js (loaded from jsDelivr). The 3D dress is generated in the browser; no external model viewer is embedded.

## Deploy on Vercel
1. In Vercel, choose **Add New → Project**.
2. Import `olaoluwabankole3-cmd/mautin`.
3. Keep the root directory at the repository root and set the framework preset to **Other** if asked.
4. Deploy the static site.

## Before presenting to the client
- Replace temporary editorial imagery in `index.html` with Mautin Atelier's approved fashion and bridal photographs. Current photographs are editorial stand-ins, not verified pictures of her own work.
- Confirm service wording and any appointment details with the designer.
- Confirm the Vercel deployment is publicly viewable without requiring the client to sign in.

## Main file
- `index.html` — site markup, monochrome responsive styles, the custom 3D dress, motion, and enquiry links.
