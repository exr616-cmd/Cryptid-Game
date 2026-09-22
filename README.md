NOCTURNE COUNTY — V28 Ultimate Web Fix

This build fixes the V27/V26 document-shell regression that could cause GitHub Pages to display the JavaScript source as plain text.

The cumulative game code now has a valid <!doctype html>, <html>, <head>, <body>, and initial <script> wrapper before the legacy runtime layers. Existing script boundaries and the final closing body/html tags are preserved.

GitHub Pages:
- Put index.html at the repository root (or configure the Pages source folder that contains it).
- If using a project site, the resulting URL should load the game UI rather than raw source.
- Hard-refresh after deployment (Ctrl+Shift+R on desktop; clear the site cache on mobile if necessary).
