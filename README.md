# Mátra Hard Trail

Online résztvevői és tréneri felület a Mátra Hard Trail döntési szimulációhoz.

## Aktuális verzió

**Ez az éles, használandó verzió:**

```text
matra-v3.html
```

Élő oldal:

```text
https://matebudai-hue.github.io/matra-hardtrail/
```

Közvetlen link:

```text
https://matebudai-hue.github.io/matra-hardtrail/matra-v3.html
```

Az `index.html` erre a v3 felületre irányít át.

## Stabil visszatérési pont

A korábbi tiszta, élesben kipróbált verzió megmaradt:

```text
matra-v2.html
```

Ha a v3 visszajelzési logikáját később túlhúznánk, ehhez a v2-höz lehet visszatérni.

## Mi új a v3-ban?

A v3 fő fejlesztése a kitöltés utáni, személyre szabottabb visszajelzés és a hibabiztosabb kitöltési folyamat.

Az index mellett megjelenik a blokk:

```text
Mit mutat a kitöltésed?
```

Három részből áll:

1. **A csoport működéséből ez látszik**
2. **Te így működtél a csoportban**
3. **Ebből most ez vihető tovább**

A visszajelzés nem diagnózis és nem ítélet. A kapott adatokból dolgozik, és a feldolgozást segíti.

A blokk végén két páros beszélgetéshez használható kérdés van. Ezek nem fix kérdések, hanem a válaszok alapján személyre szabottan jelennek meg.

## Rövid működés

1. **Meeting előtt**
   - helyzetleírás
   - saját első döntés
   - a saját stratégiai opcióknál rövid magyarázat
   - saját tárgysorrend
   - más megoldás választásánál rövid szöveges leírás

2. **Meeting után**
   - közös stratégia
   - közös top 6 tárgy
   - más közös megoldás választásánál rövid szöveges leírás
   - 12 kérdéses kockázatmérlegelés
   - rövid indoklás

3. **Mutató**
   - kockázatmérlegelési index
   - pontbontás
   - saját–közös egyezés
   - személyre szabott visszajelzés
   - erősségek
   - kockázati jelek
   - összegzés másolása
   - 1 oldalas PDF / nyomtatás
   - riport előkészítése e-mailben a böngésző levelezőfunkcióján keresztül

## Kitöltési védelem

A közös szakasz csak akkor nyílik meg, ha megvan:

- a saját első döntés,
- a saját top 6 tárgy,
- más megoldás választása esetén annak rövid leírása.

A mutató csak teljes kitöltés után nyílik meg. Ehhez szükséges:

- saját első döntés,
- saját top 6 tárgy,
- közös stratégia,
- közös top 6 tárgy,
- más közös megoldás választása esetén annak rövid leírása,
- mind a 12 skálakérdés.

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

Az automatikus háttérből küldött e-mailhez szerveroldali szolgáltatás kellene. A jelenlegi megoldás a böngésző `mailto:` funkcióját használja, vagyis a riport szövegét előkészíti elküldésre.

## Fejlesztési elv

A Mátra maradjon gyors, tiszta, tréningtermi eszköz. Ne nőjön Halastó-méretű rendszerré külön döntés nélkül.
