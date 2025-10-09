# Blue Skippers LLP Website

## Overview

Blue Skippers LLP is a software development company providing custom
software solutions, mobile applications, and employee outsourcing
services.\
This repository contains the source code and structure of the **Blue
Skippers** official website hosted at <https://blueskippers.com>.

------------------------------------------------------------------------

## 🧩 Features

-   Responsive design optimized for all devices\
-   SEO-optimized structure with proper heading hierarchy\
-   Integrated schema.org structured data (JSON-LD) for AI and search
    discoverability\
-   Sitemap and robots.txt for efficient search indexing\
-   Fast-loading static assets and image optimization\
-   Contact form with secure submission handling

------------------------------------------------------------------------

## 🧠 SEO & AI Readiness

The site includes several best practices to ensure visibility to both
search engines and AI crawlers: - Structured data (`Organization`,
`ContactPage`, etc.)\
- `robots.txt` allowing controlled crawling\
- `sitemap.xml` listing all indexed pages\
- Meta tags for title, description, and Open Graph (for LinkedIn,
Twitter)\
- Geo coordinates (`ICBM` and `geo` metadata) for local business
indexing

------------------------------------------------------------------------

## 📄 Schema Example (Home Page)

``` html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Organization",
  "name": "Blue Skippers LLP",
  "url": "https://blueskippers.com",
  "logo": "https://blueskippers.com/img/logo.png",
  "description": "Blue Skippers LLP is a software development company specializing in custom software, mobile apps, and employee outsourcing.",
  "sameAs": [
    "https://www.linkedin.com/company/blue-skippers",
    "https://github.com/blue-skippers"
  ],
  "contactPoint": {
    "@type": "ContactPoint",
    "telephone": "+91-7398242727",
    "contactType": "customer support",
    "areaServed": "IN",
    "availableLanguage": "English"
  },
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "CBD Belapur, Navi Mumbai",
    "addressLocality": "Navi Mumbai",
    "addressRegion": "Maharashtra",
    "postalCode": "400614",
    "addressCountry": "IN"
  },
  "geo": {
    "@type": "GeoCoordinates",
    "latitude": 18.9699374,
    "longitude": 73.0224476
  }
}
</script>
```

------------------------------------------------------------------------

## 🧭 File Structure

    /root
     ├── index.html
     ├── about.html
     ├── services.html
     ├── contact.html
     ├── /img
     ├── /css
     ├── /js
     ├── robots.txt
     ├── sitemap.xml
     └── README.md

------------------------------------------------------------------------

## ⚙️ Deployment

The site is hosted on a cloud-based static hosting environment.\
To deploy updates: 1. Push new commits to the `main` branch. 2. The
CI/CD pipeline automatically deploys changes to production. 3. Verify
the deployment on <https://blueskippers.com>.

------------------------------------------------------------------------

## 📬 Contact

**Blue Skippers LLP**\
CBD Belapur, Navi Mumbai, Maharashtra, India\
📞 +91-7398242727\
🌐 <https://blueskippers.com>\
✉️ info@blueskippers.com

------------------------------------------------------------------------

## 🧾 License

All rights reserved © Blue Skippers LLP.
