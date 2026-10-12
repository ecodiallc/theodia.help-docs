# Theodia Help Docs

Downloadable localized help bundles for the Theodia app. Each locale is packaged as `<locale>.help.zip` and listed in [`index.json`](index.json).

## Bundled locale

The English help docs ship inside the app binary. They are not downloaded from this repo.

| Locale | Native name | Source |
| ------ | ----------- | ------ |
| `en` | English | Bundled in the app |

## Downloadable locales

| Locale | Native name | File |
| ------ | ----------- | ---- |
| `zh-Hans` | 简体中文 | [`zh-Hans.help.zip`](zh-Hans.help.zip) |
| `zh-Hant` | 繁體中文 | [`zh-Hant.help.zip`](zh-Hant.help.zip) |
| `es` | Español | [`es.help.zip`](es.help.zip) |
| `fr` | Français | [`fr.help.zip`](fr.help.zip) |
| `de` | Deutsch | [`de.help.zip`](de.help.zip) |
| `it` | Italiano | [`it.help.zip`](it.help.zip) |
| `pt` | Português | [`pt.help.zip`](pt.help.zip) |
| `pl` | Polski | [`pl.help.zip`](pl.help.zip) |
| `ro` | Română | [`ro.help.zip`](ro.help.zip) |
| `ru` | Русский | [`ru.help.zip`](ru.help.zip) |
| `uk` | Українська | [`uk.help.zip`](uk.help.zip) |
| `hi` | हिन्दी | [`hi.help.zip`](hi.help.zip) |
| `ar` | العربية | [`ar.help.zip`](ar.help.zip) |

---

To add or update a bundle, run `npm run upload:help` from the main Theodia app repo. This copies the generated `*.help.zip` files and `index.json` into this repo, commits them, and pushes to `ecodiallc/theodia.help-docs`.
