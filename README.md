# ALAWONISKY / FUNGI — Streetwear Website

A responsive, dark-themed storefront prototype for the ALAWONISKY / FUNGI clothing brand.

## Project contents

```text
.
├── index.html              # Main website (HTML, CSS and JavaScript)
├── assets/
│   ├── fungi-logo.webp     # Brand logo
│   ├── hero-model.webp     # Homepage hero image
│   ├── gallery-lookbook.webp
│   ├── collection-1.webp
│   ├── collection-2.webp
│   ├── collection-3.webp
│   └── collection-4.webp
├── .gitignore
└── README.md
```

## Run it locally

No build tools or package installation are required.

1. Download or clone this repository.
2. Keep the `assets/` directory beside `index.html`.
3. Open `index.html` in a browser.

## Publish with Render

This is a static HTML/CSS/JavaScript website.

1. Push this repository to GitHub.
2. In Render, select **New → Static Site** and connect this repository.
3. Set the branch to `main`.
4. Leave **Build Command** blank.
5. Set **Publish Directory** to `.` (the repository root).
6. Create the Static Site. Render will provide a public `onrender.com` URL after deployment.

## Before launching for customers

- In `index.html`, replace `2340000000000` in `WHATSAPP_NUMBER` with the business WhatsApp number in international format, digits only.
- Replace `add-your-email@example.com` with the business email.
- Confirm product names, prices, product photos, delivery details, and social links.
- The cart and WhatsApp checkout are front-end demo features. The project does not process card payments or save orders to a database.

## Updating the site

Edit `index.html` or files in `assets/`, commit the changes, and push them to the `main` branch. If Render is connected to this repository with auto-deploy enabled, it will publish the update automatically.
