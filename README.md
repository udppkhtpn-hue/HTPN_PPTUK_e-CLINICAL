# PPTUK HTPN e-Clinical Portal

Front end for the PPTUK HTPN e-Clinical Portal (Jabatan Kesihatan Negeri Selangor), hosted on GitHub Pages.

- `index.html` — the whole portal (Tailwind via CDN, no build step).
- Backend: a Google Apps Script web app bound to the PPTUK Google Sheet. Its URL is set in `DEFAULT_API_URL` inside `index.html`.

To update the site, edit `index.html` and push to `main`; GitHub Pages republishes within a minute or two.
