# Ross Machinery Sales — Email Signature Generator

A single-page tool for staff to create their Outlook email signature.

## Use
Open `index.html` in a browser, fill in name, title (optional) and mobile (optional), click **Copy signature**, and paste into Outlook's signature settings. Step-by-step Outlook instructions are on the page.

## Host on GitHub Pages
1. Create a new repository and upload `index.html` and this README.
2. Repo **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main`, folder `/ (root)` → Save.
3. After a minute the tool is live at `https://<your-account>.github.io/<repo-name>/`. Share that link.

## Host on Vercel
1. Push this repo to GitHub.
2. In Vercel: **Add New → Project** → import the repo.
3. Framework Preset: **Other**. Leave Build Command and Output Directory empty → **Deploy**.
4. Live at `https://<project-name>.vercel.app`. Add a custom domain (e.g. `signatures.rossmachinery.com`) under **Settings → Domains** if wanted.

## Details
- No build step, no dependencies. One HTML file.
- Logo is served from `https://static-brand.rossmachinery.com/email/logo-800.f1bb4cb8d80c.png`.
- Office, fax, web and address are fixed in `index.html`. Edit there if they change.
- Fonts (Barlow, Saira Condensed) load from Google Fonts for the page. In the copied signature they fall back to Arial / Arial Narrow on computers without them installed.
