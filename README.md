# Dannes Bas & Gitarrservice

Hemsida för Dannes Bas & Gitarrservice i Västerås – en statisk sida i ren HTML/CSS, utan WordPress eller byggsteg.

## Struktur

- `index.html` – hela sidan (innehåll, stil och script)
- `images/` – bilder i WebP-format
  - `images/galleri/` – fullstora galleribilder
  - `images/galleri/thumbs/` – miniatyrer som visas i galleriets rutnät

## Ändra innehåll

Allt innehåll ligger i `index.html`. Texter och priser redigeras direkt i HTML:en.
Galleriets bilder listas i `instruments`-listan längst ner i filen – lägg till en rad med filnamn och bildtext,
och lägg bilden i `images/galleri/` samt en 600 px bred version i `images/galleri/thumbs/`.

## Kontaktformulär

Formuläret skickas via [Web3Forms](https://web3forms.com). Access-nyckeln i `index.html` är avsedd att vara publik.
