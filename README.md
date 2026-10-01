# Prudent Technologies & Consulting Website

A responsive multi-page corporate website built with **HTML, CSS, and JavaScript**.

## Features

- Responsive design for desktop, tablet, and mobile
- Sticky responsive header/navigation
- Mobile navigation menu
- Search overlay with responsive close button
- Services mega menu
- Company mega menu
- Responsive Careers page and application form
- Responsive Contact/consultation form
- Public Sector navigation and responsive layouts
- Partners and enterprise capability sections
- Global Leadership and Worldwide Reach sections
- CSS animations
- Background particle animation using JavaScript
- Reusable shared CSS for consistent styling

## Technologies

- HTML5
- CSS3
- JavaScript
- SVG icons
- CSS Grid
- CSS Flexbox
- Responsive media queries

No framework or build step is required.

## Project Structure

```text
prudent-fixed-v2/
├── index.html
├── about.html
├── services.html
├── partners.html
├── careers.html
├── contact.html
├── resources.html
├── case-studies.html
├── cybersecurity.html
├── data-ai.html
├── digital-transformation.html
├── enterprise-applications.html
├── executive-search.html
├── workforce-solutions.html
│
├── css/
│   ├── style.css
│   ├── responsive.css
│   └── animations.css
│
│
└── assets/
    └── images, logos and other website assets
```

> Keep the `assets` folder in the same project and preserve the relative folder structure used by the HTML files.

## Running Locally

Because this is a static website, you can open `index.html` directly in a browser.

For a better local development experience, use a local server such as VS Code Live Server.

## Deployment

This project can be deployed without a build process to static hosting services such as:

- GitHub Pages
- Cloudflare Pages
- Vercel

Make sure `index.html` is in the top level of the published website directory.

## Important Before Publishing

### Forms

The Contact and Careers forms are frontend forms. If you want submitted form data to reach an email address, CRM, database, or backend API, connect the form to a form-processing service or your own backend.

### Search

The search overlay is a frontend UI. A real site-wide search requires a search implementation or backend/search service.


## Responsive Testing

Test the website at:

- Desktop: 1440px / 1920px
- Tablet: 768px / 1024px
- Mobile: 320px / 375px / 390px / 430px
---

Built with HTML, CSS.
