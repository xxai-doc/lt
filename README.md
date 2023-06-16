<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

# xxAI.art

Dalis svetainės kodo yra atvirojo kodo, kviečiame padėti optimizuoti vertimą.

## front-end kodas

* [front-end kodas](https://github.com/xxai-art/web)
* [Kalbos paketai visai svetainei](https://github.com/xxai-art/web/tree/main/i18n)
* [Prisijungimo modulių kalbų paketai](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [Svetainės daugiakalbė dokumentacija](https://github.com/xxai-doc)

Prietaiso programavimo kalba yra [@w5/coffee_plus](http://npmjs.com/@w5/coffee_plus) , kuri prideda kai kurių funkcijų, pagrįstų coffeescript sintaksė, žr [. ./coffee_plus.md](./coffee_plus.md) .

## Svetainių ir dokumentų internacionalizavimas

Remkitės šiais 3 projektais

* [@w5/mdt](https://www.npmjs.com/package/@w5/mdt)

  Priesaga yra `.mdt` , galite naudoti sintaksę, panašią į `<+ ./coffee_plus/import.js>` , norėdami nurodyti išorinius failus, ir generuoti žymėjimą su priesaga `.md` .

* [@w5/trmd](https://www.npmjs.com/package/@w5/trmd)

  Markdown vertimas neišvers kodų ir nuorodų, o išverstus sakinius įkels talpykloje. Jei vertimas pakeistas, bet originalus tekstas nepakeistas, jį vykdant dar kartą vertimo modifikacija nebus perrašyta.

* [@w5/i18n](https://www.npmjs.com/package/@w5/i18n)

  Kalbos failai, skirti versti `yaml` sukurtas svetaines.
