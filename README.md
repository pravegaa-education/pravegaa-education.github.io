# Pravegaa Education — GitHub Pages SEO Authority Site

## Files in this repository

| File | Purpose |
|------|---------|
| `index.html` | Main hub page — full SEO optimization for CSIR NET & IIT JAM Physics |
| `csir-net-physics-strategy.html` | Long-form content page targeting "CSIR NET Physics strategy/preparation" |
| `iit-jam-physics.html` | Dedicated IIT JAM Physics page with full syllabus and FAQ |
| `sitemap.xml` | XML sitemap for search engine crawling |
| `robots.txt` | Crawl directives for search engines |
| `404.html` | Custom not-found page |
| `favicon.svg`, `og-image.png` | Site icon and social share image |

## Deployment Steps

1. Upload all files to the `pravegaa-education/pravegaa-education.github.io` repository (root directory)
2. In GitHub repository Settings → Pages → set Source to `pravegaa-education` branch, root `/`
3. The site will be live at `https://pravegaa-education.github.io/`
4. Submit sitemap to Google Search Console: `https://pravegaa-education.github.io/sitemap.xml`

## SEO Architecture — What's Built In

### Schema.org Structured Data (index.html)
- `EducationalOrganization` — full entity markup for Pravegaa with founders, courses, address, phone
- `FAQPage` — 7 FAQs targeting high-intent CSIR NET/IIT JAM queries (eligible for Google FAQ rich results)
- `BreadcrumbList` — navigation signals to Google

### Schema.org Structured Data (csir-net-physics-strategy.html)
- `Article` — for content authority signals
- `HowTo` — "How to crack CSIR NET Physics" step markup (rich result eligible)

### Schema.org Structured Data (iit-jam-physics.html)
- `Course` with `hasCourseInstance` for both online and offline modes
- `FAQPage` — IIT JAM specific queries

### On-page SEO
- Canonical tags on every page
- Open Graph + Twitter Card on every page
- Topic-weightage table for CSIR NET (PYQ analysis content)
- Full IIT JAM syllabus (topic-wise) — high search volume content
- Links to pravegaa.com are standard followed links
- Home page links to both guide pages
- External links to social profiles establish entity connections

## Maintenance Notes

- Re-check exam pattern, marking scheme and syllabus against the official NTA / JAM bulletin each cycle
- Update year references, `dateModified` and the sitemap `lastmod` whenever a page changes
- Verify outbound pravegaa.com links after any URL change on the main site

## Content to Add Next (Recommended)
- `/gate-physics.html` — GATE Physics syllabus and strategy page
- `/jest-tifr-physics.html` — JEST and TIFR preparation guide
- `/csir-net-pyq/` — folder with individual PYQ discussion pages (high long-tail traffic)
- `/physics-formula-sheets.html` — free resource page (link magnet)
