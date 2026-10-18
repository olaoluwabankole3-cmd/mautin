# Mautin Atelier

A black-and-white, phone-first fashion atelier website with dedicated service pages and a custom rotating 3D bridal gown.

## Pages
- `index.html` — homepage and collection overview.
- `bridal.html` — bridal couture information and a preselected bridal enquiry.
- `occasion-wear.html` — occasion wear service page.
- `custom-design.html` — made-to-measure/custom design page.
- `contact.html` — enquiry form which prepares a message for Instagram; it does not claim to submit an order or confirm a booking.
- `atelier-pages.css` — shared responsive styles for service and contact pages.

## Design and interactions
- Monochrome editorial styling and mobile-first layouts.
- Fullscreen-centred Three.js wedding dress, generated in the browser, with a layered skirt, shaped bodice, veil and lace details.
- Swipeable collection cards on smaller screens.
- Category cards and service links open the relevant detail page.
- Enquiry buttons lead to the contact page, where the visitor can prepare a service-specific message and continue to Instagram.
- Instagram profile and DM links are included where they are the appropriate destination.
- No build step or environment variables are required.

## Preview locally
Open `index.html` in a browser. An internet connection is required for Google Fonts, external editorial imagery and Three.js (loaded from jsDelivr).

## Deploy on Vercel
1. Import `olaoluwabankole3-cmd/mautin` as a Vercel project.
2. Keep the root directory at the repository root and choose the **Other** framework preset if asked.
3. Deploy the static site.
4. Verify the deployed URL is publicly accessible before sharing with the client.

## Before final handoff
- Replace temporary editorial imagery with Mautin Atelier's approved photographs.
- Confirm service wording, design timelines, fitting arrangements, prices and appointment availability directly with the designer.
- The website does not take payments, and the enquiry form does not confirm a booking.
