# Beautello Beauty Parlour — website

Single-page site: open `index.html`, or run `python -m http.server 8080` and visit http://localhost:8080

## Edit content
All prices, services, offers, gallery photos and the phone number are in the **EDIT HERE** block at the top of the `<script>` in `index.html`.
- Hide an offer: set `active: false`
- Change nail art price: `NAIL_ART.price`
- Add gallery photos: put the image in `images/` and add a line to `GALLERY`
- Add Instagram: set `SITE.instagramUrl`
- Change the WhatsApp number for bookings (currently 7510787039): `SITE.whatsapp` (country code, no +)

## Deploy free
Upload this folder to a GitHub repo, then import it on vercel.com (Framework: Other) — or enable GitHub Pages (Settings → Pages → main / root).

## Photos
- `images/` — Beautello's own photos (used in hero, bridal and gallery).
- The "Kerala Bride" section and a few social tiles load free inspiration photos from Unsplash (needs internet).
  Replace them with Beautello's own bridal work when available: save the photo into `images/` and change the `src` in index.html.

## How booking works
- **Book** buttons open a booking panel. The customer fills name, phone, service, date and time, then taps **Send on WhatsApp**.
- WhatsApp opens with the booking details already typed, addressed to WhatsApp 7510787039. The customer taps send, and the parlour receives it in WhatsApp.
- **Call** buttons dial 8714901099 directly. The green floating button opens a WhatsApp chat.
- Nothing is stored on a server; the WhatsApp chat is the record of each booking.
