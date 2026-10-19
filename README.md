# Elite360views website starter

A responsive, static website for GitHub Pages using the supplied Elite360views logo.

## Included
- Premium black, white, and champagne-gold design
- Homepage, services, portfolio, about, contact, privacy, and terms pages
- Responsive mobile navigation
- WhatsApp links for both supplied numbers
- Enquiry form that opens a prefilled WhatsApp message (no fake backend submission)
- English/Hindi homepage text switcher
- Portfolio empty state and starter `data/portfolio.json`
- SEO basics, robots.txt, sitemap.xml (replace placeholder URLs before launch)

## Publish on GitHub Pages
1. Create a new public repository on GitHub, for example `elite360views-website`.
2. Upload all files and folders from this project to the repository root (keep `index.html` at the root).
3. Open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. Wait for GitHub Pages to publish. The site URL will follow `https://YOUR-USERNAME.github.io/REPOSITORY/`.
7. Replace placeholder URLs in `robots.txt` and `sitemap.xml` with the real URL.
8. Test all pages and WhatsApp links on mobile.

## Important setup notes
- The email supplied by the owner (`elite360views@gmil.com`) needs confirmation. It is intentionally not published.
- The language switcher translates the homepage only in this starter version. Other pages currently remain English. Do not advertise this as a fully multilingual site until all page content and metadata are translated and tested.
- The contact form prepares a WhatsApp message; it is not a database-backed web form.
- Portfolio editing in this version is not a dashboard/CMS. The `data/portfolio.json` file is a starter structure. The portfolio page is currently a truthful empty state; project cards are not automatically generated from the JSON yet.
- Privacy and terms pages are drafts and should be reviewed against actual business practices before launch.
- This starter does not claim Google partnership or guarantee Google rankings, verification, publishing, or reinstatement.

## Suggested next improvements
1. Add fully translated Hindi pages and then reviewed translations for the remaining languages.
2. Wire portfolio cards to a project data file.
3. Add a genuine 360° viewer only after the owner supplies a real compatible tour URL.
4. Add a custom domain if desired.
