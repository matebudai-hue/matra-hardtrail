# Mátra Hard Trail

Online résztvevői és tréneri felület a Mátra Hard Trail döntési szimulációhoz.

## Aktuális stabil verzió

**Ez az éles, használandó verzió:**

```text
matra-v2.html
```

Élő oldal:

```text
https://matebudai-hue.github.io/matra-hardtrail/
```

Közvetlen link:

```text
https://matebudai-hue.github.io/matra-hardtrail/matra-v2.html
```

Az `index.html` erre a stabil v2 felületre irányít át.

## Rövid működés

A felület háromlépcsős:

1. **Meeting előtt**
   - helyzetleírás
   - saját első döntés
   - saját tárgysorrend

2. **Meeting után**
   - közös stratégia
   - közös top 6 tárgy
   - 12 kérdéses kockázatmérlegelés
   - rövid indoklás

3. **Mutató**
   - kockázatmérlegelési index
   - pontbontás
   - saját–közös egyezés
   - erősségek
   - kockázati jelek
   - összegzés másolása
   - 1 oldalas PDF / nyomtatás
   - PDF megosztása vagy elküldése a böngésző lehetőségei szerint

## A gyakorlat lényege

A Mátra Hard Trail egy döntési labor. A csoport egy téli, bizonytalan, nyomás alatti helyzetben dönt arról, hogy marad az autónál, elindul, kettéválik vagy más megoldást választ.

A felület nem túlélési esélyt számol, hanem azt teszi láthatóvá, hogyan mérlegelt a résztvevő és a csoport:

- felmérték-e a kockázatokat,
- különbséget tettek-e biztos és feltételezett információ között,
- meghallották-e a csendesebb véleményeket,
- érvek vagy hangerő alapján született-e döntés,
- az információk vezették-e a stratégiát,
- a résztvevő tud-e azonosulni a közös döntéssel,
- a saját top 6 mennyire találkozik a közös top 6-tal.

## Kockázatmérlegelési index

A hivatalos mutató neve: **Kockázatmérlegelési index**.

Pontozása:

```text
Stratégiai döntés: 10 pont
Közös top 6 minősége: 10 pont
Kockázatmérlegelés és megbeszélés: 70 pont
Saját–közös top 6 egyezés: 10 pont
```

A kérdések 1–6-os skálán működnek. Nincs középérték, nincs fordított pontozás.

## Fő tanulási üzenet

```text
Nem a hó volt az igazi veszély.
```

A hó, a hideg, a sötétedés és a felszerelés csak díszlet. A gyakorlat azt mutatja meg, hogyan működik a csoport bizonytalanságban, időnyomás alatt, korlátozott információval.

## Technikai állapot

Statikus GitHub Pages oldal. Nincs Firebase, nincs adatbázis, nincs szerveroldali adattárolás. A kitöltés böngészőben fut, az aktuális állapot `localStorage`-ba mentődik.

Az automatikus háttérből küldött e-mailhez szerveroldali szolgáltatás kellene, ezért a jelenlegi tiszta verzióban a PDF megosztása vagy kézi csatolása a biztonságos megoldás.

## Stabilitási megjegyzés

Ez a tiszta, működő v2 verzió. Későbbi fejlesztésnél ehhez kell visszatérni kiindulópontként.

A Mátra maradjon gyors, tiszta, tréningtermi eszköz. Ne nőjön Halastó-méretű rendszerré külön döntés nélkül.
