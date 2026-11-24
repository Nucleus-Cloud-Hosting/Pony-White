# Pony White Cafe — Square Online SEO & Schema Launch Kit

Complete SEO metadata, canonical URLs, Square Online navigation slugs, and JSON-LD `CafeOrCoffeeShop` structured data ready to paste into **Square Online → Website → Edit Site → Page Settings / Site Header Code**.

> **Note:** Keep `/smoothies-juices` hidden from navigation (the 6 active superfood smoothies are showcased directly on `/` and linked to `/shop/smoothies/3HB3TPEQK5JGTB4WMLLVYMNG`).

---

## 1. Per-Page Titles, Meta Descriptions & Canonicals

| Square Route | Embed File | SEO Title (`50–60 chars`) | Meta Description (`120–160 chars`) | Canonical URL |
| :--- | :--- | :--- | :--- | :--- |
| `/` (`/home`) | `home.html` | `Pony White Cafe Fitzroy \| Artisanal Brunch & Coffee` | `Specialty coffee, signature matcha and hojicha drinks, superfood smoothies, and all-day brunch in Fitzroy. Visit 379 George St or order online today.` | `https://www.ponywhite.com.au/` |
| `/signature-drinks` | `signature-drinks.html` | `Signature Drinks \| Pony White Cafe Fitzroy` | `Explore Pony White's signature Blush Rose, Coconut Cloud, Banoffee, Pistachio Crème Brûlée, ceremonial matcha, and roasted hojicha pours in Fitzroy.` | `https://www.ponywhite.com.au/signature-drinks` |
| `/reservations` | `book-table.html` | `Book a Table \| Pony White Cafe Fitzroy` | `Reserve your table at Pony White Cafe on George St, Fitzroy for artisanal brunch, specialty coffee, group celebrations, or private cafe events.` | `https://www.ponywhite.com.au/reservations` |
| `/contact-us` | `contact.html` | `Contact Us & Opening Hours \| Pony White Fitzroy` | `Get in touch with Pony White Cafe at 379 George St, Fitzroy. Check daily opening hours, send an inquiry, or share feedback with our hospitality team.` | `https://www.ponywhite.com.au/contact-us` |
| `/hiring` | `careers.html` | `Now Hiring Baristas & Kitchen Staff \| Pony White` | `Apply to join the Pony White Cafe team in Fitzroy. Submit your availability, hospitality skills, and resume online for barista, chef, and FOH roles.` | `https://www.ponywhite.com.au/hiring` |
| `/loyalty` | `loyalty.html` | `Pony White Beans Loyalty \| Free Coffee Rewards` | `Earn 1 Bean per dollar spent at Pony White Fitzroy and redeem 50 Beans for a free barista-made coffee or signature drink. Check your Bean balance online.` | `https://www.ponywhite.com.au/loyalty` |
| `/retail` | `retail-top.html` + `retail-bottom.html` | `Pony White Boutique \| San Pedro Beans & Chai` | `Shop freshly roasted San Pedro coffee beans, Mörk specialty hot chocolate powders, and artisanal chai blends for pickup at Pony White Cafe in Fitzroy.` | `https://www.ponywhite.com.au/retail` |
| `/gift-card` | `gift-cards.html` | `Digital E-Gift Cards \| Pony White Cafe Fitzroy` | `Give an instant or scheduled Pony White Cafe E-Gift Card with zero expiry dates, redeemable online and in-store at 379 George St, Fitzroy.` | `https://www.ponywhite.com.au/gift-card` |

---

## 2. Global Header JSON-LD Schema (`CafeOrCoffeeShop`)

Paste into **Square Online → Settings → Tracking Tools → Header Code**:

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "CafeOrCoffeeShop",
  "@id": "https://www.ponywhite.com.au/#cafe",
  "name": "Pony White Cafe",
  "url": "https://www.ponywhite.com.au/",
  "image": "https://storage.googleapis.com/nucleus-file-hosting/Pony_White/website_assets/hero-home.jpg",
  "logo": "https://storage.googleapis.com/nucleus-file-hosting/Pony_White/1772198572891-pg.png",
  "telephone": "+61393147273",
  "email": "info@ponywhite.com.au",
  "priceRange": "$$",
  "servesCuisine": ["Cafe", "Australian Brunch", "Specialty Coffee", "Matcha", "Smoothies"],
  "acceptsReservations": true,
  "hasMenu": "https://www.ponywhite.com.au/s/order",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "379-381 George St",
    "addressLocality": "Fitzroy",
    "addressRegion": "VIC",
    "postalCode": "3065",
    "addressCountry": "AU"
  },
  "geo": {
    "@type": "GeoCoordinates",
    "latitude": -37.802288,
    "longitude": 144.9782523
  },
  "openingHoursSpecification": [
    {
      "@type": "OpeningHoursSpecification",
      "dayOfWeek": ["Monday", "Tuesday", "Wednesday", "Thursday"],
      "opens": "07:00",
      "closes": "15:00"
    },
    {
      "@type": "OpeningHoursSpecification",
      "dayOfWeek": "Friday",
      "opens": "07:00",
      "closes": "15:30"
    },
    {
      "@type": "OpeningHoursSpecification",
      "dayOfWeek": "Saturday",
      "opens": "07:30",
      "closes": "15:30"
    },
    {
      "@type": "OpeningHoursSpecification",
      "dayOfWeek": "Sunday",
      "opens": "08:00",
      "closes": "15:30"
    }
  ],
  "sameAs": [
    "https://www.instagram.com/ponywhite.fitzroy"
  ]
}
</script>
```
