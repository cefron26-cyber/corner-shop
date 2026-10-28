# Corner Shop

An English game for Grade 5 (Here We Go Now 5, Unit 7 "Many Food Choices"): countable and uncountable nouns, containers, quantities and a / an / any. Customers say an order, students walk the aisles, drag food into the basket and press **Done!**.

- `www/index.html` - the offline game (the same file as `Corner Shop.html`), used by the Android app.
- `docs/` - installable web app (PWA). To publish it: Settings > Pages > Deploy from branch > `main` / `docs`.
- `.github/workflows/build-apk.yml` - builds a debug APK on every push to `main` and publishes it in the release **apk-latest** as `Corner-Shop.apk`.
