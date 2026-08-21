# Deakin-Unit-Page

### Run locally

The page loads unit data with `fetch`, so it must be opened through a local web server rather than directly as a `file://` page.

From this folder, run:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000 in a browser.

## Unit details

- `index.html` displays the unit list and selected unit summary.
- `unit.html?code=SIT223` displays the full details for one unit.
- `units/` contains one JSON file for each unit.