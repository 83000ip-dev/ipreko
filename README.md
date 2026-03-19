# Discover Middle East - Tourism Website

A modern, multilingual tourism website targeting Middle East and Arabic countries.

## Features

- **4 Languages**: English, Arabic (RTL), Hindi, Chinese
- **Mobile-First**: Fully responsive design
- **SEO Optimized**: 
  - Dynamic sitemap.xml
  - robots.txt
  - JSON-LD structured data
  - Open Graph & Twitter cards
  - Hreflang tags for international SEO
- **Modern Stack**: Next.js 14 with App Router
- **Beautiful UI**: Tailwind CSS with custom design system

## Getting Started

```bash
# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build

# Start production server
npm start
```

## Project Structure

```
├── app/
│   ├── [locale]/           # Language-specific routes
│   │   ├── destinations/   # Destination pages
│   │   ├── experiences/    # Experience pages
│   │   └── about/          # About page
│   ├── api/                # API routes
│   └── dictionaries/       # Translation files
├── components/             # Reusable components
├── public/
│   ├── sitemap*.xml       # Language-specific sitemaps
│   └── robots.txt
└── lib/                   # Utilities
```

## SEO Strategy

### Sitemap
- Main sitemap: `/sitemap.xml`
- Language-specific sitemaps: `/sitemap-en.xml`, `/sitemap-ar.xml`, etc.
- API sitemap: `/api/sitemap`

### Structured Data
- WebSite schema with SearchAction
- TravelAgency schema
- TouristDestination schema for each location

### International SEO
- Hreflang tags on all pages
- Alternate URLs in Open Graph
- Language-specific URLs for all content

## Deployment

This site is optimized for Vercel deployment. Simply connect your GitHub repository.

## License

MIT
