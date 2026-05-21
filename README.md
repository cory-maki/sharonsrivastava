# Client Website Template

Reusable static-site template. Fill in the `{{PLACEHOLDER}}` values for each client and deploy.

## Structure

```
├── index.html
├── about.html
├── contact.html
├── privacy.html
├── {{ARTICLE_1_SLUG}}.html   ← rename to actual slug, e.g. smart-city-illusion.html
├── {{ARTICLE_2_SLUG}}.html
├── {{ARTICLE_3_SLUG}}.html
├── sitemap.xml
├── robots.txt
├── assets/
│   └── style.css
└── images/
```

All pages are flat .html files at the root. Internal links use relative
paths like `about.html` and `smart-city-illusion.html`.

## Why .html in URLs

This template uses .html-suffixed URLs because they work on every static
host with zero configuration: Netlify, Vercel, Cloudflare Pages, GitHub
Pages, Bunny CDN, AWS S3, Apache, nginx. No edge rules, rewrite rules,
or .htaccess needed.

## Placeholder reference

(See comments in the HTML files. The master prompt also documents every
placeholder.)
