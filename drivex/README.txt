DRIVE-X (Phase 1: runs entirely in the browser)

RUN:   python3 -m http.server 8000   then open http://localhost:8000
ADMIN: admin@drive-x.com / Admin@12345  (TEST ONLY. Change before any real use)

FOLDERS
  *.html            12 pages at the root
  css/              style.css (design system), fonts.css (self-hosted @font-face)
  js/               seed.js (data), dx.js (core), extra.js (checkout/invoice/admin), nav.js, theme.js, loader.js
  assets/fonts/     Inter + Poppins (woff2, self-hosted)
  assets/images/cars/   EMPTY: paste the 26 .jpg files here (see CAR IMAGES)

CAR IMAGES: assets/images/cars/ is intentionally EMPTY. Paste your 26 .jpg files there using exactly these names:
  audi-a4.jpg
  audi-q5.jpg
  bmw-series-3.jpg
  bmw-series-5.jpg
  bmw-x1.jpg
  honda-city.jpg
  hyundai-creta.jpg
  hyundai-i20.jpg
  hyundai-verna.jpg
  kia-carens.jpg
  kia-seltos.jpg
  mahindra-thar.jpg
  mahindra-xuv700.jpg
  maruti-suzuki-dzire.jpg
  maruti-suzuki-swift.jpg
  mauti-suzuki-baleno.jpg
  mercedes-benz-e-class.jpg
  mercedes-benz-glc.jpg
  range-rover-evoque.jpg
  skoda-slavia.jpg
  tata-altroz.jpg
  tata-punch.jpg
  tata-tiago.jpg
  toyota-glanza.jpg
  toyota-innova-crysta.jpg
  generic.jpg  (fallback for cars added in Admin without an image)
Note: bmw-series-3.jpg, bmw-series-5.jpg and mauti-suzuki-baleno.jpg keep the spelling of your files. To rename them, edit the
"image" paths in js/seed.js. Browsers that ran an older build refresh their image paths automatically (data version 3).
Hero/About/Login backgrounds in css/style.css are still external stock photos.

SPECS: the 10 added cars (Tata Punch, Maruti Suzuki Dzire, Toyota Glanza, Mahindra Thar, Mahindra XUV700,
Skoda Slavia, Kia Carens, Audi A4, Mercedes-Benz GLC, BMW 3 Series) use indicative mileage/price figures.
Verify against the manufacturer before publishing. Rent prices and deposits are placeholders.

ACCOUNT CENTRE (account.html): Overview, Profile, Preferences (region, time zone, language, theme, text size,
font, reduced motion, notifications), Security (change password, sign out everywhere), Privacy & data
(download my data, data requests, delete account, reset demo data).
