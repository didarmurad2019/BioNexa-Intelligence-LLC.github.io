# BioNexa Intelligence, LLC — GitHub Pages website

A responsive, static landing page for **BioNexa Intelligence, LLC** and **CHI Lab — Healthcare AI**.

## Files

- `index.html` — page content and metadata
- `assets/css/style.css` — responsive styling
- `assets/js/main.js` — mobile navigation and dynamic copyright year
- `assets/images/bionexa-logo.png` — supplied BioNexa logo artwork
- `assets/images/favicon.svg` — lightweight browser icon

## Publish with GitHub Pages

1. Create or open the repository you want to publish.
2. Upload the contents of this folder to the repository root. Ensure `index.html` is at the root, not inside an extra nested folder.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select your branch (usually `main`) and folder `/ (root)`, then save.
6. Wait for GitHub Pages to publish and open the URL shown in the Pages settings.

## Before publishing

- In `index.html`, replace `info@bionexa.com` in the contact link with your verified official email address.
- Update the Open Graph image URL if you later move the logo or change the repository path.
- This is a static website: the contact button opens the visitor's email application. It does not collect or store form submissions, and it does not include account login functionality.
- Google Fonts are loaded from Google Fonts; the rest of the site is local and does not require a build step.

## Local preview

Open `index.html` in a browser, or run a local static server from this folder, for example:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.
