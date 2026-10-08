# Bijdragen aan de wiki

Klopt er iets niet, of mist er iets? Pas de pagina aan en open een pull request naar `main`.

## Regels

- **Alleen wat de code doet.** Elk commando, elke permissie, elke config-key en elke standaardwaarde moet in de broncode staan. Twijfel je? Laat het weg en vraag het op [Discord](https://discord.gg/6E3p8mPSVf).
- **Noteer je bron.** Zet direct onder de frontmatter een `{/* Bron: ... */}`-commentaar met de bestanden uit de broncode die de pagina beschrijft.
- **Nederlands, kort en direct.** Spreek de lezer aan met "je". Eén idee per zin. Koppen in zinsopbouw ("Rekeningen aanmaken").
- **Code-opmaak** voor commando's, permissies, config-keys, bestandsnamen en paden.
- Zet `<` en `>` in proza altijd tussen backticks, anders breekt MDX.

## Lokaal bekijken

```bash
npx mint dev
npx mint broken-links
```
