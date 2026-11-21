# che. — Custom Knotted Bag Charm Website

Starter frontend built with Next.js App Router, TypeScript, and Tailwind CSS.

## Run locally
1. Install Node.js (LTS).
2. Run `npm install`.
3. Run `npm run dev`.
4. Open http://localhost:3000.

## Before launch
Edit `src/data/customization.ts`:
- Add confirmed cord length options.
- Remove any customization choices that are not part of the final product menu.
- Add product photo paths under `public/images/`.
- Add real prices in `src/data/pricing.ts`.
- Add the business WhatsApp number in `src/lib/whatsapp.ts`.

Prices are intentionally unset (null) so the site does not invent or display misleading estimates.
WhatsApp is also intentionally unconfigured until the business number is supplied.

## Images
Put product photos in `public/images/` and update the `image` paths in the customization data.
The current preview is a layout placeholder, not a photorealistic composite renderer.


## Korean-style visual guide
The customization page includes `public/images/customization-guide.png` as an illustrated visual reference. The interactive controls below it remain the source of the customer’s actual selections. Replace the guide image with updated artwork whenever the final product options are confirmed.
