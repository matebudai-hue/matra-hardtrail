# Kockázatmérlegelési index – specifikáció

## Cél

A mutató nem túlélési esélyt számol. Azt teszi láthatóvá, hogy a résztvevő és a csoport mennyire mérlegelte tudatosan a kockázatokat, az információkat, a döntési alternatívákat és a megbeszélés minőségét.

A hivatalos név: **Kockázatmérlegelési index**.

Korábbi munkanév: Döntési biztonsági index. Ezt a dokumentációban már nem használjuk hivatalos névként, mert túl objektív biztonsági minősítést sugallna.

## Aktuális stabil verzió

Az éles felület: `matra-v2.html`.

Az oldal statikus GitHub Pages felületként működik. Nincs Firebase, nincs szerveroldali adatbázis, nincs központi adatgyűjtés. A kitöltés a böngészőben fut, az állapot `localStorage`-ban tárolódik.

## Felhasználói flow

```text
1. Helyzet megismerése
2. Saját első stratégiai döntés
3. Saját tárgysorrend
4. Meeting / közös döntés
5. Közös top 6 tárgy
6. Kockázatmérlegelési kérdések
7. Index, egyezés, erősségek, kockázati jelek
8. Másolás / PDF / megosztás
```

## Pontozási logika

Összesen 100 pont.

```text
Stratégiai döntés: 10 pont
Közös top 6 minősége: 10 pont
Kockázatmérlegelés és megbeszélés: 70 pont
Saját–közös top 6 egyezés: 10 pont
```

## Stratégiai döntés

A közös végső stratégiai döntés pontozása:

```text
Az autónál maradunk: 10 pont
Más megoldást választunk: 6 pont
Elindulunk a turistaház felé: 4 pont
Kettéválik a csoport: 0 pont
```

A saját első stratégiai döntés önreflexiós adat. Jelenleg nem ad külön pontot, de megjelenhet a kockázati jelek között, ha eltér a közös végső döntéstől.

## Közös top 6 minősége

A közös top 6 tárgyból a szakértői top 6-ba eső tárgyak aránya adja a pontot.

```text
szakértői top tárgyak száma / 6 × 10
```

A tárgylista a felületen szándékosan kevert sorrendben jelenik meg. A szakértői sorrend csak a háttérben számol, illetve külön lenyitható összevetésben látható.

## Saját–közös top 6 egyezés

A rendszer összeveti a résztvevő saját top 6 tárgyát és a közös top 6 tárgyat.

Csak az számít, hogy egy tárgy benne van-e mindkét top 6-ban. A pontos helyezés ennél a mutatónál nem számít.

```text
egyező tárgyak száma / 6 × 10
```

A visszajelzés megmutatja:

- egyezés: X / 6
- egyező tárgyak
- nálad bent volt, a közösben nem
- a közösben bent volt, nálad nem

Ez nem azt méri, hogy a résztvevőnek „igaza volt-e”. Azt teszi láthatóvá, hogy a saját gondolkodásából mennyi jelent meg a közös döntésben, illetve mennyit változott a meeting során.

## Kockázatmérlegelési kérdések

12 állítás van. Mindegyik 1–6-os skálán működik.

```text
1 = egyáltalán nem
2 = inkább nem
3 = kis részben
4 = részben igen
5 = nagyrészt igen
6 = teljesen
```

Nincs középérték. A 3 inkább gyenge jel, a 4 már inkább megjelent működés.

A 12 kérdés nyers pontszámát a rendszer 70 pontra skálázza.

```text
összes adott pont / 72 × 70
```

## Aktuális állítások

1. A végső döntés előtt mérlegeltük a kockázatokat.
2. A távolságot nem önmagában, hanem a körülményekkel együtt értékeltük.
3. Különbséget tettünk a biztos és feltételezett információk között.
4. Több megoldási irány kockázatát is összehasonlítottuk.
5. Kimondtuk, melyik kockázatot vállaljuk tudatosan.
6. A végső stratégiát az összegyűjtött információk alapján alakítottuk ki.
7. A döntés iránya az információk mérlegelése után alakult ki, nem fordítva.
8. A döntésben az érvek nagyobb szerepet kaptak, mint a hangerő vagy a határozottság.
9. Tudatosan figyeltünk arra, hogy a csendesebbek is megszólaljanak.
10. A halkabb vagy óvatosabb vélemények is hatottak a döntésre.
11. A végső döntéssel tudok azonosulni.
12. A végső döntésben megjelentek az általam fontosnak tartott szempontok.

## Fontos döntés

Nincs fordított pontozás. Minden kérdésnél ugyanaz az irány: a magasabb érték erősebb, tudatosabb, biztonságosabb döntési működést jelez.

## Export

Az oldal az alábbi kimeneteket adja:

- összegzés másolása
- 1 oldalas PDF
- PDF küldése / megosztása a böngésző képességei szerint

Statikus GitHub Pages oldalként automatikus háttérből küldött e-mail nincs. A mobilos megosztás vagy a letöltött PDF kézi csatolása a tiszta, szerver nélküli megoldás.
