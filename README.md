# OpenMinetopia wiki

De bron van [wiki.openminetopia.nl](https://wiki.openminetopia.nl): de documentatie van de [OpenMinetopia-plugin](https://github.com/OpenMinetopia/openminetopia) en het [portaal](https://github.com/OpenMinetopia/portal). De wiki draait op [Mintlify](https://mintlify.com).

## Lokaal bekijken

```bash
npx mint dev
```

Controleer links voordat je een pull request opent:

```bash
npx mint broken-links
```

## Structuur

- `docs.json`: navigatie, kleuren, logo en links.
- `index.mdx` en `plugin/`: de plugin (installatie, configuratie, modules, commando's, placeholders, REST API).
- `portaal/`: het portaal.
- `community/`: bijdragen, Discord en veelgestelde vragen.
- `images/brand/`: het logo.

Wijzigingen op `main` gaan automatisch live. Lees [CONTRIBUTING.md](CONTRIBUTING.md) voordat je iets aanpast.
