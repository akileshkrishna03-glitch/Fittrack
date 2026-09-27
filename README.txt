FITTRACK WEB V2 — GITHUB PAGES UPDATE

This is a drop-in replacement for your current FitTrack PWA.

UPDATE FROM IPHONE
1. Unzip FitTrack_Web_V2.zip in Files.
2. Open your existing FitTrack GitHub repository in Safari.
3. Replace/upload index.html, styles.css, app.js, manifest.json and sw.js.
4. Replace the icons folder too if needed.
5. Commit the changes to the same branch GitHub Pages uses (normally main).
6. Wait 1–3 minutes, then open your existing FitTrack website.
7. If the old design remains, close the Home Screen app completely and reopen it. Safari may briefly retain the old service-worker cache.

DATA
Existing routines/workouts/body entries/runs/steps use the same localStorage keys, so the update is designed to preserve the data already stored in that browser/PWA.

PROGRESSION
- All prescribed sets reach the top of the rep range: add the exercise increment next time.
- Most completed sets fall below the minimum: reduce by one increment next time.
- Otherwise: keep the same load and aim for more reps.
- Suggested weights are editable.

APPLE HEALTH
A GitHub Pages PWA cannot directly access iOS HealthKit/Apple Watch health data. Steps and runs therefore remain manual in this web build.
