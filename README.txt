ASCEND FITNESS — NUTRITION LABEL TRACKER UPDATE

New feature: Add from nutrition label
- Optionally photograph/upload a package nutrition label as a visual reference.
- Enter product name, whether the label values are per serving or per 100g/ml, serving size, and amount eaten.
- Enter calories, protein, carbohydrates and fat printed on the package.
- ASCEND calculates the actual macros for the amount consumed and adds it to the daily food journal.
- Save a product label locally for quick reuse; previously saved labels can be selected and serving/amount adjusted.
- Existing smart food search and manual macro entry remain available.

Important:
- The uploaded label photo is a visual reference only in this version. It does not automatically OCR/read the nutrition panel; type the printed values into the fields and verify them.
- Per-serving math: label nutrients × amount eaten ÷ serving size.
- Per-100g/ml math: label nutrients × amount eaten ÷ 100.
- Values are only as accurate as the label transcription and portion measurement.
- Saved labels and food logs are stored locally in the browser/device, not synced to a cloud account.

To update GitHub Pages:
Replace index.html, manifest.webmanifest and sw.js in the repository root, commit to main, and wait for deployment. If the installed app shows an older version, close it fully and reopen after deployment; service worker cache version is incremented.
