# Mautin Atelier

A monochrome, mobile-first fashion-at​​elier website with a continuously rotating procedural 3D bridal gown.

## What's included
- Black-and-white editorial direction.
- Phone-first layout with swipeable collection cards.
- Procedural wedding dress rendered in Three.js, continuously rotating and responding subtly to scroll movement.
- Responsive navigation, gentle section reveals, and reduced-motion support.
- Instagram / direct-message enquiry links.
- No build step or environment variables; the site is a single static `index.html`.

## Preview locally
Open `index.html` in a browser. The 3D dress loads Three.js from jsDelivr, so an internet connection is required for the live 3D effect.

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
- `index.html` — site markup, monochrome responsive styles, motion, Three.js dress model, and enquiry links.
