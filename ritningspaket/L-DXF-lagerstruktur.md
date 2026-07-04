# L. DXF-LIKNANDE LAGERSTRUKTUR

**Status:** Preliminär handling  
**Datum:** 2026-07-04

---

Denna fil beskriver en DXF-kompatibel lagerstruktur för CAD-produktion av ritningspaketet.
Strukturen kan användas för att sätta upp en DWG/DXF-mall.

---

## LAGERSTRUKTUR (LAYER TABLE)

| Lager-ID | Lagernamn          | Färg (ACI) | Linjetyp       | Linjebredd mm | Synlighet | Beskrivning                           |
|----------|--------------------|------------|----------------|---------------|-----------|---------------------------------------|
| 1        | A-WALL-EXT         | 7 (vit)    | CONTINUOUS     | 0.50          | ON        | Ytterväggar, stomkontur               |
| 2        | A-WALL-EXT-FILL    | 8 (grå)    | CONTINUOUS     | 0.00          | ON        | Ytterväggar, fyllning/skraffering     |
| 3        | A-WALL-INT         | 4 (cyan)   | CONTINUOUS     | 0.35          | ON        | Innerväggar                           |
| 4        | A-WALL-ANSL        | 2 (gul)    | CONTINUOUS     | 0.35          | ON        | Anslutning 45 mm mot befintligt hus   |
| 5        | A-WALL-BEF         | 9 (grå)    | DASHED         | 0.25          | ON        | Befintlig husvägg (referens)          |
| 10       | A-DOOR             | 3 (grön)   | CONTINUOUS     | 0.25          | ON        | Dörrar med slagning                  |
| 11       | A-WINDOW           | 5 (blå)    | CONTINUOUS     | 0.25          | ON        | Fönster                              |
| 12       | A-OPENING          | 1 (röd)    | DASHED         | 0.35          | ON        | Förstorad öppning Ö1                 |
| 20       | A-DIM              | 8 (grå)    | CONTINUOUS     | 0.18          | ON        | Måttkedjor, måttlinjer               |
| 21       | A-DIM-TEXT         | 7 (vit)    | –              | –             | ON        | Måtttext                             |
| 25       | A-TEXT             | 7 (vit)    | –              | –             | ON        | Generella texter och beteckningar    |
| 26       | A-TEXT-ROOM        | 7 (vit)    | –              | –             | ON        | Rumsnamn                             |
| 27       | A-TEXT-NOTE        | 1 (röd)    | –              | –             | ON        | Varningstexter, noteringar           |
| 30       | A-SECTION          | 6 (mag.)   | DASHDOT        | 0.25          | ON        | Sektionslinjer                       |
| 31       | A-SECTION-MARKER   | 6 (mag.)   | CONTINUOUS     | 0.35          | ON        | Sektionsmarkeringar (cirklar/pilar)  |
| 35       | A-LEVEL            | 3 (grön)   | –              | –             | ON        | Nivåangivelser (FG etc.)             |
| 36       | A-NORTH            | 7 (vit)    | CONTINUOUS     | 0.25          | ON        | Norrpil                              |
| 40       | A-GRID             | 8 (grå)    | DOT            | 0.13          | ON        | Modullinjer, axellinjer              |
| 41       | A-GRID-TEXT        | 8 (grå)    | –              | –             | ON        | Axelbeteckningar                     |
| 50       | A-FURNITURE        | 8 (grå)    | CONTINUOUS     | 0.13          | OFF       | Möblering (ej i denna handling)      |
| 60       | A-HATCH            | 252        | CONTINUOUS     | 0.00          | ON        | Skraffering väggar/material          |
| 70       | A-TITLEBLOCK       | 7 (vit)    | CONTINUOUS     | 0.35          | ON        | Ritningshuvud/ram                    |
| 71       | A-TITLEBLOCK-TEXT   | 7 (vit)    | –              | –             | ON        | Text i ritningshuvud                 |

---

## KONSTRUKTIONSLAGER (för K-ritningar)

| Lager-ID | Lagernamn          | Färg (ACI) | Linjetyp       | Linjebredd mm | Beskrivning                           |
|----------|--------------------|------------|----------------|---------------|---------------------------------------|
| 100      | K-STUDS            | 7 (vit)    | CONTINUOUS     | 0.35          | Väggreglar                            |
| 101      | K-STUDS-TRIM       | 1 (röd)    | CONTINUOUS     | 0.50          | Sidoreglar/trimmer vid öppningar     |
| 102      | K-HEADER           | 1 (röd)    | CONTINUOUS     | 0.50          | Överstycken                          |
| 103      | K-SILL             | 3 (grön)   | CONTINUOUS     | 0.35          | Syll                                  |
| 104      | K-TOPPLATE         | 4 (cyan)   | CONTINUOUS     | 0.35          | Hammarband                           |
| 105      | K-CORNER           | 6 (mag.)   | CONTINUOUS     | 0.35          | Hörnreglar                           |
| 106      | K-CRIPPLE          | 8 (grå)    | CONTINUOUS     | 0.25          | Kortlingar                           |
| 107      | K-ANSL             | 2 (gul)    | CONTINUOUS     | 0.50          | Anslutningsregel 45 mm               |
| 110      | K-RAFTER           | 5 (blå)    | CONTINUOUS     | 0.35          | Takreglar                            |
| 111      | K-RAFTER-RIM       | 5 (blå)    | CONTINUOUS     | 0.50          | Kantbalk tak                         |
| 120      | K-DIM              | 8 (grå)    | CONTINUOUS     | 0.18          | Konstruktionsmått                    |
| 121      | K-TEXT             | 7 (vit)    | –              | –             | Konstruktionstexter                  |
| 122      | K-NOTE             | 1 (röd)    | –              | –             | Konstruktionsnoteringar              |

---

## DETALJLAGER (för D-ritningar)

| Lager-ID | Lagernamn          | Färg (ACI) | Linjetyp       | Linjebredd mm | Beskrivning                           |
|----------|--------------------|------------|----------------|---------------|---------------------------------------|
| 200      | D-STRUCT           | 7 (vit)    | CONTINUOUS     | 0.35          | Bärande konstruktion                 |
| 201      | D-INSULATION       | 3 (grön)   | CONTINUOUS     | 0.18          | Isolering (med skraffering)          |
| 202      | D-MEMBRANE         | 1 (röd)    | CONTINUOUS     | 0.25          | Ångspärr, vindskydd, membran         |
| 203      | D-CLADDING         | 4 (cyan)   | CONTINUOUS     | 0.25          | Beklädnad (gips, spånskiva)          |
| 204      | D-FLASHING         | 6 (mag.)   | CONTINUOUS     | 0.35          | Plåtbeslag                          |
| 205      | D-SEALANT          | 2 (gul)    | CONTINUOUS     | 0.25          | Tätning, fogmassa, kompriband       |
| 206      | D-FASTENER         | 1 (röd)    | CONTINUOUS     | 0.13          | Infästningar, ankare, skruv          |
| 210      | D-DIM              | 8 (grå)    | CONTINUOUS     | 0.18          | Detaljmått                           |
| 211      | D-TEXT             | 7 (vit)    | –              | –             | Detaljtexter                         |
| 212      | D-HATCH            | 252        | CONTINUOUS     | 0.00          | Skraffering i detaljer              |

---

## LINJETYPER

| Namn         | Mönster                    | Användning                    |
|--------------|----------------------------|-------------------------------|
| CONTINUOUS   | ————————————               | Synliga kanter, konturer      |
| DASHED       | — — — — —                  | Dolda kanter, befintligt      |
| DASHDOT      | —·—·—·—                    | Sektionslinjer                |
| DOT          | · · · · · ·                | Modullinjer, axlar            |
| CENTER       | ——·——·——                   | Symmetrilinjer                |
| PHANTOM      | ——··——··——                  | Rivning, borttagning          |

---

## TEXTSTILAR

| Stilnamn     | Typsnitt        | Höjd (modell) | Användning                    |
|--------------|-----------------|---------------|-------------------------------|
| STANDARD     | Arial/Helvetica | 2.5 mm        | Generell text                 |
| DIM          | Arial/Helvetica | 2.0 mm        | Måtttext                      |
| TITLE        | Arial/Helvetica | 5.0 mm        | Ritningsnamn                  |
| NOTE         | Arial/Helvetica | 2.5 mm        | Noteringar                    |
| ROOM         | Arial/Helvetica | 3.5 mm        | Rumsnamn                      |

---

## MÅTTSTIL

| Egenskap              | Värde           |
|-----------------------|-----------------|
| Enheter               | mm              |
| Precision             | 0 (heltal)      |
| Piltyp                | Snedstreck (/)  |
| Pitstorlek            | 2.5 mm          |
| Textplacering         | Ovan linje      |
| Texthöjd              | 2.0 mm          |
| Förlängningslinje     | 1.5 mm          |
| Offset                | 1.0 mm          |

---

## BLOCKDEFINITIONER (föreslagna)

| Blocknamn        | Beskrivning                          | Lager          |
|------------------|--------------------------------------|----------------|
| DOOR-SINGLE      | Enkeldörr med slagning               | A-DOOR         |
| DOOR-SLIDING     | Skjutdörr                            | A-DOOR         |
| WINDOW-PLAN      | Fönster i plan                       | A-WINDOW       |
| SECTION-MARKER   | Sektionsmarkering med cirkel         | A-SECTION-MARKER|
| NORTH-ARROW      | Norrpil                              | A-NORTH        |
| LEVEL-MARKER     | Nivåmarkering (triangel + text)      | A-LEVEL        |
| TITLEBLOCK-A3    | Ritningshuvud A3                     | A-TITLEBLOCK   |
| TITLEBLOCK-A2    | Ritningshuvud A2                     | A-TITLEBLOCK   |

---
*Lagerstrukturen är anpassad för professionell svensk byggritningsstandard och kan importeras i AutoCAD, BricsCAD eller likvärdig CAD-programvara.*
