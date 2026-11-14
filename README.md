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
- `prod.html` — products, with a working cart counter (Buy Now adds items; the count persists in localStorage and shows in the navbar), plus a running cart total next to the cart badge (item prices persist in localStorage), plus a cart panel opened from the navbar cart badge that lists the added items by name and price with a remove button per item (items persist in localStorage; removing one updates the count and total), plus a live search that filters product cards by name, plus a wishlist toggle on each product card (heart button; saved in localStorage with a count in the navbar), plus sort by price or name (Featured / Price low-to-high / Price high-to-low / Name A–Z / Name Z–A) that reorders the product cards, plus a max-price filter (slider, Rs. 3,900–8,200, with Reset) that hides products above the chosen price and works together with the search and sort, plus a back-to-top button that appears on scroll and smooth-scrolls to the top, plus product image zoom on hover (each product image scales up slightly with a smooth transition)
- `prof.html` — profile
- `about.html` — about, with a navbar cart badge reading the shared localStorage cart count (`olla_cart_count`)
- `cont.html` — contact, with a navbar cart badge reading the shared localStorage cart count (`olla_cart_count`)

## Run Locally
Open `index.html` in a browser, or serve with any static server (e.g. VS Code Live Server).
