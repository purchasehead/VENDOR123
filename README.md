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

---

# Material Rate Analysis

`rate-analysis/index.html` – month-wise purchase rates of construction materials by vendor.

- Summary of all materials: latest average rate, change vs previous month and vs period start, price range, trend sparkline, L1 (lowest) vendor.
- Key findings: steepest rise, biggest drop, widest vendor price gap.
- Per-material trend chart (one line per vendor, hover for rates) and month × vendor grid; click any cell to add or edit a rate.
- Period filter (from / to month) and Export CSV.
- Opens with sample NCR rates (Apr–Sep 2026), marked as samples; remove them and enter your own.

With GitHub Pages enabled it is served at `/VENDOR123/rate-analysis/`. Standalone mode stores rates in the browser only; `rate-analysis.html` is the claude.ai artifact source.
