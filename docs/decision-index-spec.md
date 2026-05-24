# Kockázatmérlegelési index – v3 specifikáció

## Cél

A mutató nem túlélési esélyt számol. Azt teszi láthatóvá, hogy a résztvevő és a csoport mennyire mérlegelte tudatosan a kockázatokat, az információkat, a döntési alternatívákat és a megbeszélés minőségét.

## Aktuális éles verzió

- `index.html` automatikusan a `matra-v3.html` felületre irányít.
- A `matra-v3.html` az aktuális éles résztvevői felület.
- A `matra-v2.html` tiszta, stabil visszatérési pontként marad a repóban.

## Kitöltési logika

A v3 három fázisra bontja a folyamatot:

1. **Meeting előtt**: saját stratégia és saját top 6 tárgy.
2. **Meeting után**: közös stratégia, közös top 6, 12 skálakérdés és rövid indoklás.
3. **Mutató**: index, bontás, személyes visszajelzés, páros beszélgetéshez két kérdés.

A mutató csak teljes kitöltés után nyitható meg. Szükséges hozzá:

- saját első döntés,
- saját top 6 tárgy,
- közös stratégia,
- közös top 6 tárgy,
- mind a 12 skálakérdés.

## Pontozási szerkezet

Összesen: **100 pont**.

### 1. Stratégia – 10 pont

- Az autónál maradunk: 10 pont
- Más megoldást választunk: 6 pont
- Elindulunk a turistaház felé: 4 pont
- Kettéválik a csoport: 0 pont

### 2. Közös top 6 – 10 pont

A rendszer azt nézi, hogy a közös top 6-ban hány tárgy szerepel a szakértői top 6-ból. Ez kiegészítő mutató, nem a gyakorlat fő tanulsága.

### 3. Mérlegelés – 70 pont

A 12 skálakérdés adja a mutató fő súlyát. A skála 1–6 között működik, középérték nélkül.

### 4. Saját–közös egyezés – 10 pont

A rendszer azt számolja, hány tárgy egyezik a résztvevő saját top 6-ja és a közös top 6 között.

## Visszajelzési logika

A v3 személyre szabott visszajelzést ad három rövid blokkban:

- **A csoport működéséből ez látszik**
- **Te így működtél a csoportban**
- **Ebből most ez vihető tovább**

A csoportműködési visszajelzésben a bevonás gyenge jele elsőbbséget kap a magas kockázatmérlegelési pontokkal szemben. Ennek oka: tréneri szempontból a csendesebb, halkabb vagy óvatosabb vélemények háttérbe szorulása fontosabb tanulási jel, mint az önmagában magas pontszám.

## Páros beszélgetés kérdései

A „Gondold végig páros beszélgetésben” blokk két kérdése személyre szabott. A rendszer a résztvevő válaszai alapján választ kérdést például ezekből a mintákból:

- kimaradt saját szempont,
- alacsony azonosulás a közös döntéssel,
- eltérés a saját és közös top 6 között,
- korai döntéshez igazított érvelés,
- halkabb vélemények háttérbe szorulása.

## Fontos szakmai keret

A mutató nem objektív diagnózis. Tréningtermi tükör. A cél az, hogy a résztvevő ne csak azt lássa, milyen pontszám jött ki, hanem azt is, hogyan volt benne a közös döntésben.
