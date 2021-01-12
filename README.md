# C++ beadandó feladat.
## Gépjármű nyilvántartó

Írjon gépnyilvántartó programot, mely egy munkagépeket, teherautókat és autóbuszokat üzemeltető cég heti járműigénybevételét tárolja!

A cég három különböző kategóriában üzemeltet gépeket:

1. Munkagép
Tárolandó adatok:
* rendszám
* típus
* gyártási év
* kapacitás (teljesítmény kW-ban)
* igénybevétel (heti összesített munkaóra).

2. Teherautó
Tárolandó adatok:
* rendszám
* típus
* gyártási év
* kapacitás (teherbírás tonnában)
* igénybevétel (heti futott km).

3. Autóbusz:
* rendszám
* típus
* gyártási év
* kapacitás (férőhelyek száma).
* igénybevétel (heti futott km).

A programot konzol alkalmazásban, ciklusban futó, választható menüvel valósítsa meg!
Egy lehetséges megoldásként a következő menüpontokkal:
* Újabb autó adatainak tárolása
* Gépek adatainak teljes listázása
* Gép adatainak kiíratása billentyűzetről bekért rendszám alapján
* Igénybevétel összesítése kategóriánként
* Kategóriánként szervíz igénybevételi határ beállítása
* Azoknak a járműveknek a listázása, melyek a szervíz igénybevételi határt túllépték.
* Kilépés

A menüpontok összeállítása csak egy javaslat, legyenek kreatívak! Részmegoldást is elfogadok. 

Tájékoztatásul, az értékeléskor a felhasznált eszközkészlet az elsődleges szempont. A következő szinteket várom el:
(vagy kapcsolat esetén elég valamelyik, de természetesen mindkettő még jobb)
2: A program lefordul és fut. Menüt, egy alap osztályt és származtatott osztályokat tartalmaz.
3: Konstruktor és inicializálási lista használata. Tárolás C típusú tömbben.
4: Modulokra bontott program, vagy template használata vagy operátor túlterhelés (újradefiniálás). Tárolás valamilyen STL aggregát osztályban.
5: Virtuális metódus alkalmazása, vagy lemezre mentés-visszatöltés.
