# FMFahrdienst

Bilingual static website concept for FM Fahrdienst UG, a Cologne-based transport and logistics company active across the EU with transport capacity up to 3.5 tonnes.

## Preview locally

Because the site is static, it can be opened directly through `index.html`. For a more accurate local preview, use any static file server from this folder.

## Pages

- `index.html` - German-first homepage with English language toggle and quote request form
- `impressum.html` - legal notice with supplied company registration details
- `datenschutz.html` - preliminary privacy notice requiring review before launch
- `styles.css` - responsive layout and visual system
- `script.js` - navigation, language switching, validation, and `mailto` handoff

## Before launch

1. Replace `PLACEHOLDER_EMAIL@example.com` in `index.html` and `script.js` with the real public email address.
2. Add the public phone number and any WhatsApp contact option.
3. Use `FMFahrdienst` as the public brand and `FM Fahrdienst UG` as the registered legal entity.
4. Review and complete `impressum.html` and `datenschutz.html` with legal counsel.
5. Replace remote image URLs with approved, locally hosted company or vehicle photography if possible.
6. Decide whether a hosted form service is needed for reliable delivery, attachments, and server-side validation.

## GitHub Pages

Commit the project to a GitHub repository, then enable **Settings → Pages → Deploy from a branch** and select the main branch root. The site uses relative page and asset paths, so it is suitable for a repository subpath.

## Current limitations

The quote form opens the visitor's email client using `mailto:`. It does not upload files or guarantee delivery. The current contact details are placeholders and must be replaced before publication.