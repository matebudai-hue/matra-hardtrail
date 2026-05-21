# Fejlesztési napló – Mátra Hard Trail

## 1. Kiinduló helyzet

A Mátra Hard Trail eredetileg nyomtatható gyakorlatként indult: helyzetleírással, tárgylistával, eseménykártyákkal és tréneri feldolgozással.

A fő tanulási irány már az elején erős volt: a csoport nem feltétlenül a legjobb döntést választja, hanem azt, amelyik a leghangosabbnak, leggyorsabbnak vagy legbiztosabbnak tűnik.

## 2. Online irány

Felmerült egy teljes Firebase-alapú rendszer lehetősége, egyéni és csoportos beküldéssel, központi dashboarddal.

A fejlesztés első lépése végül egy egyszerűbb, statikus online felület lett. Ez jelenleg nem gyűjt központi adatot, hanem helyben számolja az indexet.

## 3. UX-fókusz

A cél egy letisztult, résztvevő által is kitölthető felület:

- csoportnév,
- stratégiai döntés,
- első 6 tárgy,
- megbeszélési állítások,
- önreflexiós állítások,
- automatikus index,
- másolható összegzés.

A felület szándékosan nem akar dashboard-monstrum lenni. A Halastó külön projektként marad, ez a Mátra saját, könnyebb felülete.

## 4. Szakmai finomítás

A kérdések fejlesztésekor az volt a cél, hogy ne legyenek félreérthetők. A puha, szándékokra kérdező megfogalmazások helyett megfigyelhető csoportműködések kerültek be.

Kikerült a fordított pontozás, mert résztvevői önkitöltésnél zavaró. Bekerült két önreflexiós kérdés is.

## 5. Jelenlegi elv

A tárgylista fontos, de nem ez viszi a tanulást. A legerősebb súlyt a megbeszélés és az önreflexió kapja.

```text
Nem a lista a lényeg.
Az a lényeg, hogyan jutottatok el a listáig.
```