# E-Commerce Shoe Store — Olla Shoe

A responsive e-commerce showcase interface for a shoe store, with product listings, product detail, about, contact and profile pages, built with modern layout techniques (Flexbox/Grid).

## Live Demo
https://ollashoe.netlify.app/

## Screenshot
![ecommerce-shoe-store screenshot](https://image.thum.io/get/width/1200/https://ollashoe.netlify.app/)

## Tech Stack
- HTML5
- CSS3
- JavaScript (ES6+)
- Bootstrap 5
- Google Fonts

## Pages
- `index.html` — home / showcase, with a navbar cart badge reading the shared localStorage cart count (`olla_cart_count`), with a newsletter signup in the footer that validates the email and shows a success or error message without reloading
- `prod.html` — products, with a working cart counter (Buy Now adds items; the count persists in localStorage and shows in the navbar), plus a running cart total next to the cart badge (item prices persist in localStorage), plus a live search that filters product cards by name, plus a wishlist toggle on each product card (heart button; saved in localStorage with a count in the navbar), plus sort by price (Featured / Price low-to-high / Price high-to-low) that reorders the product cards
- `prof.html` — profile
- `about.html` — about
- `cont.html` — contact

## Run Locally
Open `index.html` in a browser, or serve with any static server (e.g. VS Code Live Server).
