# LandCruiser 79 Build Budget

A free, static, phone-friendly, single-page budget planner for a Toyota LandCruiser 79 Series dual-cab expedition build.

## Publish on GitHub Pages

1. Create a **public** GitHub repository, for example `landcruiser-79-budget`.
2. Upload **index.html**, **app.js**, and **manifest.webmanifest** to the repository root (using **Add file → Upload files**). Commit them.
3. Open repository **Settings → Pages**.
4. Set **Build and deployment → Deploy from a branch**, branch **main**, folder **/(root)**, then **Save**.
5. GitHub will show your Pages URL. Open it in Safari on iPhone and choose **Share → Add to Home Screen** if desired.

No dependencies, Node.js, backend or hosting fee required for a public GitHub Pages repository (subject to GitHub availability/terms).

## Using the app

- Every part has an editable AUD price. Enter `0` for anything owned, excluded, or included with another purchase.
- Add additional parts and categories as needed. Search for a part by name.
- Subtotals and the grand total update when price fields are changed (on blur/Return).
- Changes are saved **only in that browser/device** using localStorage, not to GitHub. Different devices don't automatically sync.
- **Export backup** saves all category and item data as JSON. **Import backup** restores it. Use **Export CSV** for spreadsheet analysis.
- Export JSON before clearing Safari site data or switching phones.
- Figures are placeholder estimates, not quotations, and may include overlapping items unless you set included items to zero.

## Safety

Before committing to GVM, 35-inch tyres, brake modifications or structural changes, obtain an engineering plan compatible with the exact model and NSW requirements. DIY installation may still require professional inspection, testing or certification. The app is for budgeting only.
