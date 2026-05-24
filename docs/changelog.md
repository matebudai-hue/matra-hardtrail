# Changelog

## 2026-05-21 – külön repo létrehozása

- Létrejött a `matra-hardtrail` repo.
- Bekerült az első önálló `index.html`.
- Bekerült a dokumentációs struktúra.
- A Mátra leválasztásra került a Halastó repóról.

## 2026-05-22 – béta döntési index

- Online döntési index felület készült.
- Bekerült az első 6 tárgy kiválasztása kattintási sorrend alapján.
- Bekerült a stratégiai döntés blokk.
- Bekerült a megbeszélési minőség blokk.
- Bekerültek az önreflexiós kérdések.
- Kikerült a fordított pontozás.
- Bekerült a másolható összegzés.
- Bekerült a PDF / nyomtatás gomb.
- Bekerült a `localStorage` mentés.

## 2026-05-23 – stabil v2 meetingfelület

- Az aktuális stabil felület a `matra-v2.html` lett.
- Az `index.html` a v2-es felületre irányít.
- A hivatalos mutató neve: **Kockázatmérlegelési index**.
- A pontozás frissült: 10 pont stratégia, 10 pont közös top 6, 70 pont kockázatmérlegelés, 10 pont saját–közös egyezés.
- A 3 opciós válaszlogikát 1–6-os skála váltotta fel.
- A kérdések száma 12 lett.
- Bekerült a saját első stratégiai döntés rögzítése.
- Bekerült a saját top 6 és a közös top 6 egyezésének visszajelzése.
- Bekerült a vendégházas Mátra-sztori erősebb kockázati helyzettel: január vége, extrém hideg, esteledés, nincs térerő, 9–10 km, hóban 2–3 óra.
- A tárgylista kevert sorrendben jelenik meg, nem szakértői sorrendben.
- A felület mobilos használatra lett optimalizálva: koppintásos választás, nagy kártyák, drag and drop nélkül.
- A PDF továbbra is 1 oldalas összegzésként működik.

## 2026-05-24 – repo takarítás és dokumentációfrissítés

- Törölve lett a véletlenül bent maradt `notes/test-write.md` tesztfájl.
- Frissült a `docs/decision-index-spec.md`, hogy a valós v2 logikát írja le.
- Frissült ez a changelog.

## Fő szakmai változás

A felület nem túlélési játékot támogat, hanem döntési laborlogikát.

A kérdés nem az, hogy ki választotta ki a legtöbb szakértői tárgyat, hanem az, hogy milyen döntési folyamaton ment át a résztvevő és a csoport.

A legerősebb tanulási fókusz:

```text
Nem a hó volt az igazi veszély.
```
