# Brew & Beans - Coffee Shop Website

This is a complete, production-ready coffee shop website generated from a simple single-category prompt. It includes four pages with Tailwind CSS utility classes and category-appropriate content.

Project structure:

- public/ – client-side files (HTML, JS, CSS via Tailwind classes)
  - public/index.html – Home / Hero, signature beverages, visit info
  - public/about.html – Our story and team
  - public/menu.html – Coffee and pastries menu
  - public/contact.html – Contact form
- server/ – (not used in this static site generation, included for structure compatibility)
- .env – environment variables
- package.json – basic project file
- vercel.json – deployment configuration for Vercel
- README.md – this file

How to run:

1) Open the generated files in the public/ directory in your browser. They are production-ready with semantic HTML, responsive Tailwind utility classes, and accessible content.
2) If you deploy to Vercel, ensure vercel.json references the public folder as the static root.

Note: All pages are linked via relative paths (index.html, about.html, menu.html, contact.html) to maintain simple navigation without a router.