# Subhavarthini Rajamanickam — Professional Portfolio

Responsive, accessible static portfolio based on the supplied SAP Project Manager resume. Includes project experience, certifications, professional photo, contact links and a downloadable resume.

## Run locally

`python3 -m http.server 8080 --directory dist`

Open http://localhost:8080. No installation or build step is needed.

## Hosting

Deploy the contents of `dist/` to any static web host. For Cloudflare Pages or Hostinger, use `dist` as the public/output directory and leave the build command empty. Paths are relative and support subdirectory hosting.

## Update

Edit `dist/index.html` for content and `dist/style.css` for styling. Assets are in `dist/assets/`. Project dates not supplied in the resume have intentionally been omitted. The LinkedIn address is taken directly from the resume; no external validation was performed.
