# Mátra Hard Trail

Online résztvevői és tréneri felület a Mátra Hard Trail döntési szimulációhoz.

A gyakorlat lényege: egy téli, bizonytalan, nyomás alatti helyzetben a csoportnak döntést kell hoznia. Maradnak az autónál, elindulnak, kettéválnak vagy más megoldást választanak. A felület nem túlélési esélyt számol, hanem döntési biztonsági indexet ad.

## Élő oldal

GitHub Pages bekapcsolása után:

```text
https://matebudai-hue.github.io/matra-hardtrail/
```

## Jelenlegi állapot

Béta, de tréningben már használható verzió.

A felület rögzíti:

- csoport neve,
- első stratégiai döntés,
- első 6 kiválasztott tárgy,
- csoportos megbeszélés minősége,
- két önreflexiós kérdés,
- rövid indoklás,
- döntési biztonsági index.

## Döntési biztonsági index

A mutató 100 pontos.

```text
Stratégiai döntés: 20 pont
Tárgyválasztás: 20 pont
Megbeszélés és önreflexió: 60 pont
```

A gyakorlat fókusza nem az, hogy ki választotta ki a „jó” tárgyakat. A lényeg az, hogyan jutott el a csoport a döntésig.

## Fő tanulási üzenet

```text
Nem a hó volt az igazi veszély.
```

A hó, a hideg, a sötétedés és a felszerelés csak díszlet. A gyakorlat azt teszi láthatóvá, hogyan működik a csoport bizonytalanságban, időnyomás alatt, korlátozott információval.

## Dokumentáció

- `docs/trainer-guide.md` — tréneri útmutató
- `docs/decision-index-spec.md` — indexlogika és pontozás
- `docs/design-log.md` — fejlesztési napló
- `docs/changelog.md` — változások
- `docs/roadmap.md` — későbbi fejlesztési irányok

## Technikai állapot

A jelenlegi verzió egyetlen statikus `index.html` fájl. Nincs Firebase, nincs adatbázis, nincs szerveroldali adattárolás. A kitöltés böngészőben fut, az aktuális állapot localStorage-ba mentődik.

Későbbi irány lehet Firebase-alapú központi dashboard, egyéni és csoportos beküldéssel.