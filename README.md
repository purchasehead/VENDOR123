# Alcove Vendor Register

Vendor list portal for the Alcove Realty purchase department: suppliers and contractors with category, contact details, GSTIN/PAN, approval status, rating, payment terms and last PO date.

## Use

Open `index.html` in a browser, or enable GitHub Pages (Settings → Pages → Deploy from branch `main`, folder `/`).

- Add, edit and delete vendors; search and filter by category, status and city.
- GSTIN format check, duplicate-GSTIN check, PAN auto-filled from GSTIN.
- Export CSV of the filtered list (opens in Excel).

In standalone mode the list is stored in each browser's local storage, so it is not shared between people or devices. Use Export CSV to back it up. The shared, multi-user version runs as a claude.ai artifact.

## Files

- `index.html` – standalone page
- `vendor-portal.html` – same page, artifact source (no document skeleton)
