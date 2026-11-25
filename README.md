# S & T (Slice and Topping) 🍕

A single-page pizza shop website with a menu, combos, gallery and a working order cart. Built with plain HTML, CSS and JavaScript, so there is nothing to install.

## Features

- Menu with Veg / Non-Veg filters
- Combos & deals
- Gallery section
- Order drawer with quantity controls, promo codes and a running total
- Responsive layout for mobile and desktop

## Run it

Download or clone the repo and open `index.html` in any browser.

> If your file is named `index1.html`, rename it to `index.html` so GitHub Pages can serve it.

## Customize

All content lives in the `<script>` block at the bottom of the file:

| What | Where |
| --- | --- |
| Menu items | `MENU` array |
| Combos | `COMBOS` array |
| Promo codes | `PROMOS` object |
| Gallery pictures | `GALLERY` array (add `img: 'photos/file.jpg'` to use a real photo) |

Shop name, address, phone and timings are in the HTML under the **Visit Us** section.

## Deploy on GitHub Pages

1. Go to **Settings → Pages**
2. Under **Source**, choose the `main` branch and `/ (root)`
3. Save, and your site goes live at `https://<your-username>.github.io/<repo-name>/`

## Promo codes

| Code | Offer |
| --- | --- |
| `WEEKEND25` | 25% off orders of ₹699+ |
| `BDAYTREAT` | 20% off |
| `LUNCH150` | ₹150 off orders of ₹449+ |

## Note

The "Place Order" button is a demo only. It shows a confirmation message and does not send orders anywhere.
