# Reporting Dashboard

Radius Agent **Client Metrics / MEL Reporting** HTML prototype.

## Preview

Open `index.html` locally, or use GitHub Pages after enablement.

- File: `index.html` (same as `MelMetricsOverview.html`)
- Stack: standalone MagicPath export + Radius UI 3.0 polish (side rail, reporting chrome, cards)

## Local

```bash
# simple static server (file:// also works in some browsers)
python3 -m http.server 8766
# → http://127.0.0.1:8766/
```

## Notes

- Sidebar toggle (Reporting header) collapses the left rail and expands the page.
- Prototype data only; not production API-backed.
