# Pravegaa Education — GitHub Pages SEO Authority Site

## Files in this repository

| File | Purpose |
|------|---------|
| `index.html` | Main hub page — full SEO optimization for CSIR NET & IIT JAM Physics |
| `csir-net-physics-strategy.html` | Long-form content page targeting "CSIR NET Physics strategy/preparation" |
| `iit-jam-physics.html` | Dedicated IIT JAM Physics page with full syllabus and FAQ |
| `sitemap.xml` | XML sitemap for search engine crawling |
| `robots.txt` | Crawl directives for search engines |

## Deployment Steps

1. Upload all files to the `pravegaa-education/pravegaa-education.github.io` repository (root directory)
2. In GitHub repository Settings → Pages → set Source to `main` branch, root `/`
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
- All internal links point back to pravegaa.com with `rel="nofollow"` (passes brand signals without leaking PageRank)
- External links to social profiles establish entity connections

## Link Building Usage
This GitHub Pages site serves as a **high-authority referring domain** to pravegaa.com:
- GitHub.io domains have high Domain Authority (DA ~90+)
- Every page links to pravegaa.com — builds backlink profile
- Anchor text is varied and natural across pages
- `rel="nofollow"` on internal links is intentional — Google still uses nofollow links as hints and for entity association

## Content to Add Next (Recommended)
- `/gate-physics.html` — GATE Physics syllabus and strategy page
- `/jest-tifr-physics.html` — JEST and TIFR preparation guide
- `/csir-net-pyq/` — folder with individual PYQ discussion pages (high long-tail traffic)
- `/physics-formula-sheets.html` — free resource page (link magnet)
