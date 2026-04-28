# RYTON LIMITED - Wholesale Distribution Website

A premium wholesale distributor website built with Astro and Tailwind CSS v4.

## About the Project

RYTON LIMITED is a UK-based wholesale distributor offering premium personal care products, beverages, household goods, confectionery, health & wellness, and baby care products to businesses across the United Kingdom.

## Tech Stack

- **Framework**: Astro 6.x
- **Styling**: Tailwind CSS v4 with @tailwindcss/vite
- **Icons**: Font Awesome 6.5
- **Hosting**: Netlify-ready (static site generation)

## Project Structure

```
/
├── public/
│   ├── brand/          # Brand logo SVGs
│   ├── *.jpg           # Product images (1-24)
│   ├── dots.svg        # Background pattern
│   ├── favicon.ico     # Favicon
│   ├── favicon.png     # Favicon PNG
│   └── robots.txt      # SEO robots file
├── src/
│   ├── components/
│   │   ├── BackToTop.astro
│   │   ├── Footer.astro
│   │   ├── Header.astro
│   │   └── ProductCard.astro
│   ├── data/
│   │   └── products.js  # Product catalog (24 products)
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   ├── index.astro    # Homepage
│   │   ├── about.astro     # About Us
│   │   ├── contact.astro   # Contact page
│   │   ├── privacy.astro   # Privacy Policy
│   │   ├── products.astro  # Product catalog
│   │   ├── services.astro  # Services page
│   │   └── terms.astro    # Terms of Service
│   └── styles/
│       └── global.css     # Global styles
├── package.json
├── astro.config.mjs
├── tailwind.config.js
└── tsconfig.json
```

## Pages

| Page | Route | Description |
|------|-------|-------------|
| Homepage | `/` | Hero, stats, categories, trust signals, CTA |
| About | `/about` | Company story, values, stats |
| Services | `/services` | Core services, process steps |
| Products | `/products` | Product catalog with filtering & search |
| Contact | `/contact` | Contact form, office location, map |
| Privacy Policy | `/privacy` | GDPR-compliant privacy policy |
| Terms of Service | `/terms` | Legal terms for wholesale services |

## Commands

| Command | Action |
|---------|--------|
| `npm install` | Install dependencies |
| `npm run dev` | Start dev server at localhost:4321 |
| `npm run build` | Build production site to `./dist/` |
| `npm run preview` | Preview production build locally |

## Features

- Mobile-responsive design with Tailwind CSS
- Product filtering and search functionality
- Contact form with Netlify Forms integration
- Animated scroll effects with IntersectionObserver
- SEO-ready with meta tags and robots.txt
- GDPR-compliant privacy policy
- Multi-step service process visualization

## Contact

- **Email**: info@rytonlimited.com
- **Address**: 3rd Floor Belmont Road, Uxbridge, England, UB8 1HE