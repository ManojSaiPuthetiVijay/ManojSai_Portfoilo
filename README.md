# Manojsai Putheti Vijay - Portfolio

Static site: `index.html` + `Manojsai_Putheti_Vijay_Resume.pdf` (keep both in the same folder).

## Preview
Open `index.html` in a browser, or run `python3 -m http.server` in this folder.

## Publish
Drag this folder onto Netlify Drop or Cloudflare Pages, or push it to a GitHub repo and enable GitHub Pages (root). If you use Lovable, paste the contents of `index.html` into a new project or ask it to recreate this page.

## Update
- Resume: replace the PDF, keep the file name `Manojsai_Putheti_Vijay_Resume.pdf`.
- Projects/skills/certifications: edit the matching section in `index.html`. Look for the "To add" notes inside the case studies.
- Real repo links: search for `github.com/ManojSaiPuthetiVijay` in the project cards and add the project URLs.
- Screenshots: replace the `.shot` placeholder divs with `<img>` tags.

## Contact form
Create a free form endpoint (for example at formspree.io using manojsaissp@gmail.com), then set `FORM_ENDPOINT` at the top of the script in `index.html`. Until then the form shows that it is not connected and nothing is sent.

## Custom domain
Add the domain in your host's settings and follow its DNS steps. Add a `sitemap.xml` with the final URL after that.

- Photo: `profile.jpg` sits next to `index.html` (hero portrait). Replace the file, keep the name.
