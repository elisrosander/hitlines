# Hitlines

Daglig musikutmaning – placera låtarna i rätt kronologisk ordning.

## Utveckla lokalt
Kräver Node.js 24 (LTS), se `.nvmrc`.

    npm install
    npm run build      # skapar dist/output.css
    # öppna index.html i webbläsaren

Under arbete: `npm run watch` bygger om CSS:en vid varje ändring.

## Publicera
GitHub Pages byggs automatiskt av `.github/workflows/deploy.yml` vid push till `main`.
Ställ in en gång: Settings → Pages → Source: **GitHub Actions**.
