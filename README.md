# Personal Portfolio — Static Website

A minimal, responsive personal portfolio built with plain HTML and CSS to showcase projects and contact information.

What’s in this repo
- index.html — Main page with sections for introduction, projects, and contact.
- about.html — Additional about / biography page.
- style.css — Styling (layout, colors, responsive rules).
- Images and assets — profile and social icons (im.jpeg, facebook.png, instagram.png, twitter.png, notebook.png, etc.).

What I implemented
- Semantic HTML structure (header, nav, main, footer) for accessibility and SEO.
- Responsive layout using CSS Flexbox / Grid with media queries so content adapts to mobile and desktop.
- Clean visual styling: consistent spacing, typography, and iconography.
- Static contact link (mailto:) and social links for quick outreach.
- All pages are static — no JavaScript required to use the site.

How the code is organized (what each file does)
- index.html
  - Header and navigation linking to page sections.
  - Hero/introduction section, project tiles, and contact area.
  - Uses relative image paths from the repository.
- about.html
  - Longer biography and additional info.
- style.css
  - Global typography and color variables.
  - Layout rules for header, hero, project cards, and footer.
  - Media queries that adjust navigation and stack content on small screens.
- assets/images
  - Local images referenced by the HTML for thumbnails and icons.

How to run locally
- Open index.html directly in a browser (quick preview).
- Or run a simple static server to avoid relative path issues:
  - Python 3: python -m http.server 8000
  - Then open http://localhost:8000

How to deploy
- GitHub Pages: enable Pages in repository settings (serve from main branch / root).
- Or any static host (Netlify, Vercel) by pointing the host to this repository.

Quick editing guide
- Change content: edit index.html and about.html.
- Update styles: edit style.css (colors, fonts, spacing).
- Replace images: overwrite files in the repo and update src attributes if filenames change.

Accessibility & best practices included
- Semantic tags (header, nav, main, footer).
- Alt attributes for images (please review and update alt text to match your content).
- Responsive design for mobile-first viewing.

Next steps I can help with
- Commit this README.md to the repository.
- Add a minimal .gitignore and a requirements/deploy note.
- Create a GitHub Pages workflow (GitHub Actions) to publish automatically.

If you want, I’ll commit this README to the repo now — tell me to proceed and I’ll prepare the commit.
