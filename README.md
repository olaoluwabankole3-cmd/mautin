# Mautin Atelier

A monochrome, mobile-first fashion atelier website with a real rotating 3D wedding-dress model embedded from Sketchfab.

## What's included
- Black-and-white editorial direction.
- Phone-first layout with swipeable collection cards.
- Finished 3D wedding-dress model on a continuously rotating Sketchfab turntable, with subtle page-scroll parallax.
- Responsive navigation, gentle section reveals, and reduced-motion support.
- Instagram / direct-message enquiry links.
- No build step or environment variables; the main website is a single static `index.html`.

## 3D model credit
The embedded wedding-dress model is **Wedding dress** by **Fashion by Stela Yordanova**, hosted on [Sketchfab](https://sketchfab.com/3d-models/wedding-dress-48f95bed136f47c28a87ee276b638095), under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). The website footer includes attribution. The model viewer streams from Sketchfab, so the 3D layer requires an internet connection.

## Preview locally
Open `index.html` in a browser. An internet connection is required for Google Fonts, the editorial imagery, and the embedded 3D model.

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
- `index.html` — site markup, monochrome responsive styles, mobile-first layout, scroll parallax, and the embedded 3D bridal dress.
