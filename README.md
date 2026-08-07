# anyamount

> [!IMPORTANT]
> **This repository has moved.** `anyamount` now lives in the
> [**anyfamily**](https://github.com/kirilinsky/anyfamily) monorepo alongside the
> rest of the `any*` family. This copy is archived and frozen at v1 — anything
> below is kept for history only.

Numbers, currency, and units into localized, human-readable strings. One function, three modes, any locale.

|  |  |
| --- | --- |
| **Source** | [kirilinsky/anyfamily → packages/anyamount](https://github.com/kirilinsky/anyfamily/tree/main/packages/anyamount) |
| **Docs** | [anyfamily.site/docs/anyamount](https://anyfamily.site/docs/anyamount) |
| **Demo** | [anyfamily.site/anyamount](https://anyfamily.site/anyamount) |
| **npm** | [npmjs.com/package/anyamount](https://www.npmjs.com/package/anyamount) |

The package is still published and maintained — only the repository moved.
`npm install anyamount` works exactly as before.

## v2 changed the API

Every `any*` package now exports **exactly one name**, with the extras hanging
off it:

```diff
- anyamountSymbol('USD')
+ anyamount.symbol('USD')
```

Full notes: [migrating to v2](https://anyfamily.site/docs/anyamount#migrating).

## the rest of the family

Eight micro, zero-dependency Intl tools — one function each, zero data files,
200+ locales via native `Intl`. `anywhen` · `anyamount` · `anymany` ·
`anyaround` · `anylong` · `anyplural` · `anyword` · `anylocale`, or all eight
at once via [`anyfamily`](https://www.npmjs.com/package/anyfamily).

**[anyfamily.site](https://anyfamily.site)** · ⭐ [star the monorepo](https://github.com/kirilinsky/anyfamily)

MIT © [kirilinsky](https://github.com/kirilinsky)
