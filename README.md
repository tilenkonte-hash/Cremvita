# GRETA — dve različici spletne strani

Dve ločeni, samostojni statični spletni strani. Prva ohranja izvirno podobo GRETA; druga predstavi lik Greta von Soyer. Vsaka mapa vsebuje lasten HTML, CSS, vse štiri fotografije in navodila. Za delovanje ne potrebujeta druga druge, zunanjih storitev ali namestitve odvisnosti.

| Različica | Mapa | Vstopna datoteka |
| --- | --- | --- |
| GRETA — Kremšnita, po svoje. | [greta](greta/) | [index.html](greta/index.html) |
| Greta von Soyer — Njena kremna visokost | [greta-von-soyer](greta-von-soyer/) | [index.html](greta-von-soyer/index.html) |

## Najlažji ogled na računalniku

Izberite **Code → Download ZIP**, razširite arhiv in odprite korenski `index.html` v brskalniku. Izberite želeno različico. Lahko odprete tudi `index.html` neposredno v posamezni mapi.

## Lokalni razvoj

Potrebujete Python 3. V korenu prenesenega repozitorija zaženite:

```sh
python3 -m http.server 3000
```

V brskalniku odprite `http://localhost:3000`, nato izberite različico. Posamezni poti sta `/greta/` in `/greta-von-soyer/`. Ustavite s Ctrl+C. Vsako mapo lahko tudi ločeno kopirate in strežete po njenih navodilih.

## Datoteke in objava

`public/images/` hrani izvirne naložene fotografije. Obe različici uporabljata svoje kopije v `images/`, da sta prenosljivi. Fotografije imajo presledke v imenih, zato HTML uporablja kodirane povezave `%20`.

Korenski `index.html` je le izbor različice. Prenos v GitHub sam po sebi ne omogoči javne spletne strani. Statične mape so primerne za gostovanje, npr. GitHub Pages; javna objava v tem koraku ni nastavljena.

Navodila za vsebino in zagon so tudi v vsaki mapi. Kontakti uporabljajo `mailto:` in `tel:` povezave.
