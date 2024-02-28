# Min Lommbok App

Dette prosjektet er en enkel lommebok-app for å spore inntekter og utgifter. Appen er implementert ved hjelp av HTML, CSS (med Bootstrap) og JavaScript.

## Hvordan bruke

1. Åpne `index.html` i nettleseren din for å starte appen.
2. Fyll ut skjemaet for utgifter for å legge til nye utgifter i tabellen.
3. Bruk inntektsfeltet for å legge til inntekter og se oppdateringen i resultatene.
4. Slett informasjon ved å klikke på "Slette informasjon" -knappen.

## HTML-fil

- `index.html` inneholder strukturen for appens grensesnitt.
- Appen bruker Font Awesome og Bootstrap for ikoner og styling.

## JavaScript-fil

- `app.js` håndterer logikken bak inntekter, utgifter, og oppdatering av grensesnittet.

## Avhengigheter

- Font Awesome: 6.4.0
- Bootstrap: 5.3.0

For å kjøre prosjektet lokalt, kan du inkludere følgende CDN-lenker i `index.html`.

```html
<!-- Font Awesome -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw==" crossorigin="anonymous" referrerpolicy="no-referrer" />

<!-- Bootstrap CSS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-9ndCyUaIbzAi2FUVXJi0CjmCapSmO7SnpJef0486qhLnuZ2cdeRhO02iuK6FUUVM" crossorigin="anonymous" />