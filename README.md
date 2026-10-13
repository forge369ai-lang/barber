# Tidewater Barber Co. website

A one-page barbershop website: price list, barbers, opening hours with a live "open now" note, map, and WhatsApp booking.

Plain HTML, CSS and JavaScript. No build step, no dependencies.

## Deploy on Vercel

1. In Vercel, click **Add New > Project** and import this repo.
2. Leave the framework preset as **Other**. No build command, no output folder.
3. Click **Deploy**.

Every push to `main` redeploys automatically.

## Things to replace before going live

All of these are placeholders:

| What | Where |
| --- | --- |
| Shop name | `index.html` (title, header, footer), `README.md` |
| WhatsApp number (`27000000000`) | `index.html`, three booking links. Use the full number with country code, no `+` or spaces |
| Phone number | `index.html`, the `tel:` link in "Come in" |
| Address and map | `index.html`, the `<address>` and the map `src` (`q=` your street address) |
| Prices and services | `index.html`, the "Price list" section |
| Barbers, bios and photos | `index.html`, "Who's cutting". Swap each `.chair-photo` div for an `<img>` (4:5 portrait works best) |
| Review quote | `index.html`, the quote section. Use a real Google review |
| Opening hours | `index.html` hours table **and** the `HOURS` object at the top of `script.js` |
| Instagram / Facebook links | `index.html` footer |

## Run it locally

Open `index.html` in a browser, or run `npx serve .` in this folder.
