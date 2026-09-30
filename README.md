# LUSSI frizerski salon, Trogir

Statična web stranica (HTML + CSS), bez ovisnosti i bez build koraka.

## Struktura
- `index.html` – stranica
- `style.css` – stilovi
- `images/` – logo i fotografije radova

## Objava na GitHub Pages
1. Napravi repozitorij i uploadaj sve datoteke (index.html mora biti u korijenu).
2. Settings > Pages > Source: Deploy from a branch > `main` / `(root)` > Save.
3. Stranica je dostupna na `https://KORISNIK.github.io/NAZIV-REPOZITORIJA/`.

## Objava na Netlifyju
Povuci cijeli folder na app.netlify.com/drop ili poveži GitHub repozitorij.

## Što ažurirati
- Radno vrijeme: tablica u `#kontakt` i `openingHoursSpecification` u JSON-LD bloku u `<head>`.
- Ocjena "5,0 (41 recenzija)": ručno u `index.html` (klasa `rating`) kad se promijeni.
- Fotografije: zamijeni datoteke u `images/` istim nazivima.
