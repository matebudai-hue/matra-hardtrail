# Stabil v3 visszatérési pont

Ez a dokumentum rögzíti, hogy a `matra-v3.html` az élesben kipróbált, tiszta alapverzió.

## Miért fontos?

A Mátra Hard Trail könnyen továbbfejleszthető, de a játék értéke pont abban van, hogy gyors, mobilon is használható és nem nő Halastó-méretű rendszerré. Ez a verzió már tréningtermi visszajelzés alapján működött:

- a résztvevők értették a kitöltést,
- a 9–10 km-es távolság és a hideg erősebb kockázati keretet ad,
- a 1–6-os skála középérték nélkül működik,
- a 12 kérdés a döntési folyamatra, a bevonásra, az érvekre és az önreflexióra fókuszál,
- a szakértői tárgyértékelés visszakerült a mutató mellé,
- a személyre szabott visszajelzés és a páros kérdések a feldolgozást segítik,
- a PDF / nyomtatás és az e-mail előkészítés opcionális segédfunkció.

## Stabil alapverzió

```text
matra-v3.html
```

Közvetlen élő link:

```text
https://matebudai-hue.github.io/matra-hardtrail/matra-v3.html
```

## Vezetői alternatíva

A vezetői változat külön fájlban fut, hogy az alapverziót ne piszkálja:

```text
matra-leader.html
```

Közvetlen élő link:

```text
https://matebudai-hue.github.io/matra-hardtrail/matra-leader.html
```

Ez a verzió nem az alapjáték cseréje, hanem alternatív tréninghelyzet: a vezető az elején térerőt keres, majd visszatér a már alakuló csoportbeszélgetésbe.

## Fejlesztési szabály

Ha később új ötlet jön, először külön fájlban vagy külön branchben kell kipróbálni. A `matra-v3.html` csak tudatos döntéssel változzon.

## Tilos elrontani

A következő elemek maradjanak meg minden további fejlesztésnél:

- három részre bontás: Meeting előtt / Meeting után / Mutató,
- 1–6 skálamagyarázat,
- nincs fordított pontozás,
- saját top 6 és közös top 6,
- saját–közös egyezés,
- szakértői tárgyértékelés,
- személyre szabott visszajelzés,
- páros feldolgozó kérdések,
- „Nem a hó volt az igazi veszély.”
