# Optjen – træn for at tjene skærmtid

En lille webapp, hvor du tjener skærmtid ved at træne. Kameraet tæller dine gentagelser, og skridt tælles via telefonens bevægelsessensor.

- Egne satser for hver øvelse (fx 5 armbøjninger = 1 min)
- Kameratælling af armbøjninger, squats, jumping jacks og planke
- Skridttæller til løb og gå
- Lyst og mørkt tema i cream og espresso
- Ingen server og ingen afhængigheder: alt kører i browseren, og data gemmes lokalt på enheden

## Brug

Åbn siden på din telefon i Safari eller Chrome. Kamera og bevægelsessensor kræver HTTPS, hvilket GitHub Pages giver dig automatisk.

## Udgiv på GitHub Pages

1. Opret et nyt repository på GitHub.
2. Upload `index.html` og `README.md`.
3. Gå til **Settings → Pages**.
4. Under **Build and deployment** vælg **Deploy from a branch**, branch `main` og mappe `/ (root)`.
5. Efter et minut er siden live på `https://DIT-BRUGERNAVN.github.io/REPO-NAVN/`.

## Bemærk

Kameraet analyserer bevægelse op og ned i billedet og genkender ikke kroppen, så det kan snydes. Videoen forlader aldrig enheden.
