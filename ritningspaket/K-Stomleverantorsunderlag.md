# K. STOMLEVERANTÖRSUNDERLAG

**Status:** Reviderad handling – Rev A  
**Datum:** 2026-07-08

---

**OBS: Detta underlag är REVIDERAT enligt projekteringsspecifikation 2026-07-08. Mått markerade med ★ kräver kontrollmätning på plats. Mått markerade med ▲ kräver konstruktörsverifiering.**

---

## K.1 VÄGGSCHEMA

### Ytterväggar – regelstomme 45×170 mm, c/c 600

| Vägg-ID | Benämning                  | Längd mm | Höjd, låg mm | Höjd, hög mm | Regeltyp    | C/C  | Antal fältreglar* | Öppningar                  | Notering                     |
|---------|----------------------------|----------|-------------|-------------|-------------|------|--------------|-----------------------------|------------------------------|
| V1      | Fasad 2, låg sida          | 10 500   | **2 621**   | **2 621**   | **45×170 C24** | **600** | 17        | D1 (1000×2100), F1 (1200×1200) | Alla reglar samma höjd    |
| V2      | Fasad 4, nedre höger       | 3 240    | **2 621**   | **2 777** ★ | **45×170 C24** | **600** | 5         | Inga                        | Lutande hammarband (**8,6°**) |
| V3      | Fasad 4, utskjut. horis.   | 3 740    | **2 777** ★ | **2 777** ★ | **45×170 C24** | **600** | 6         | Inga                        | ★ Höjd beror på taklutning |
| V4      | Fasad 4, utskjut. vert.    | 6 480    | **2 777** ★ | **3 300**   | **45×170 C24** | **600** | 10        | F3 (1200×1200)              | Lutande hammarband (**8,6°**) |
| V5      | Övre del, mot bef. hus     | 6 760    | **3 300**   | **3 300**   | **45×170 C24** | **600** | 5         | **Ö1 (3 380×2 100)**        | **Förstorad öppning** ▲     |
| V6      | Vänster utskjutande         | 5 220    | **3 300**   | **2 777** ★ | **45×170 C24** | **600** | 8         | Inga                        | Lutande hammarband (**8,6°**) |
| V7      | Ansl. mot bef. hus         | 7 480    | **3 300**   | **3 300**   | –           | –    | –            | Inga                        | **Bärlina + stödreglar**    |
| V8      | Gavel vänster               | 4 500    | **2 621**   | **3 300**   | **45×170 C24** | **600** | 7         | F2 (1000×1000)              | Lutande hammarband (**8,6°**) |

**Varje vägg har dessutom en infälld regel (45×170 mm) direkt under hammarbandet.**

### Öppningsschema per vägg

#### Vägg V1

| Öppning | Typ       | Hålmått B×H mm | Position fr. vänster hörn mm | Bröstning mm | Överstycke         | Sidoreglar   |
|---------|-----------|----------------|------------------------------|--------------|---------------------|--------------|
| D1      | Ytterdörr | 1 000 × 2 100  | 2 000 ★                      | –            | 2×45×170 L=1100    | 2×45×170     |
| F1      | Fönster   | 1 200 × 1 200  | 5 500 ★                      | 900          | 2×45×170 L=1300    | 2×45×170     |

#### Vägg V4

| Öppning | Typ     | Hålmått B×H mm | Position fr. nedre hörn mm | Bröstning mm | Överstycke         | Sidoreglar   |
|---------|---------|----------------|----------------------------|--------------|---------------------|--------------|
| F3      | Fönster | 1 200 × 1 200  | 2 000 ★                    | 900          | 2×45×170 L=1300    | 2×45×170     |

#### Vägg V5 – FÖRSTORAD ÖPPNING

| Öppning | Typ     | Hålmått B×H mm   | Position fr. ref.hörn mm | Bröstning mm | Överstycke         | Sidoreglar     |
|---------|---------|------------------|--------------------------|--------------|---------------------|----------------|
| **Ö1**  | Öppning | **3 380 × 2 100**| **KONTROLLERAS** ★       | –            | **2×45×220 LVL** ▲ | **2×2×45×170** |

**⚠ Ö1:** Öppningsbredd **3 380 mm** fastställd enligt specifikation. Överstycke **PROJEKTERAS AV KONSTRUKTÖR** – LVL-balk rekommenderas.

#### Vägg V8

| Öppning | Typ     | Hålmått B×H mm | Position fr. nedre hörn mm | Bröstning mm | Överstycke         | Sidoreglar   |
|---------|---------|----------------|----------------------------|--------------|---------------------|--------------|
| F2      | Fönster | 1 000 × 1 000  | 1 500 ★                    | 900          | 2×45×170 L=1100    | 2×45×170     |

**NOTERING:** Sovrumsfönstret mot befintligt hus har **tagits bort** enligt specifikation.

---

## K.2 TAKREGLAR / TAKBJÄLKAR

| Egenskap          | Värde                                            |
|-------------------|-------------------------------------------------|
| Regeltyp          | **45×220 mm** C24                                |
| Installationsläkt | **28×70 mm**                                     |
| C/c               | **600 mm**                                       |
| Lutning           | **8,6°** (15,1 %)                                |
| Fallriktning      | Från hög sida (bef. hus) mot låg sida (Fasad 2)  |
| Upplag hög sida   | **Bärlina 45×220** på befintlig yttervägg         |
| Upplag låg sida   | Hammarband på V1                                  |

### Takregelschema

| Grupp    | Antal | Ungefärlig längd mm | Upplag hög       | Upplag låg        | Notering              |
|----------|-------|---------------------|-------------------|--------------------|-----------------------|
| Huvuddel | 13    | 4 950 (inkl. språng)| V7 bärlina        | V1 hammarband      | Standard              |
| Utskjut. | 17    | 4 950 ★             | V5/V6 hammarband  | V2/V3 hammarband   | KONTROLLERAS ★        |
| Kantbalk | 2     | 4 950               | Gavel V8          | Gavel V4           | Kantbjälke            |
| **Totalt**| **32**|                     |                   |                    |                       |

---

## K.3 ANSLUTNING MOT BEFINTLIGT HUS

| Komponent         | Dimension       | Antal | Längd mm  | Notering                                    |
|-------------------|-----------------|-------|-----------|---------------------------------------------|
| **Bärlina**       | **45×220 mm**   | 1     | 7 480     | Monteras på befintlig yttervägg (220 mm)    |
| **Stödreglar**    | **45×220 mm**   | ca 13 | ca 220    | Breda sidan mot bef. vägg, 45 mm utbyggnad  |
| Kemankare         | M12             | ca 13 | –         | c/c 600 i befintlig vägg                    |

---

## K.4 SYLL, HAMMARBAND, INFÄLLD REGEL, KORTLINGAR, FÖRSTÄRKNINGAR

### Syll (impregnerad NTR AB)

| Vägg-ID | Dimension   | Längd mm | Antal | Notering                |
|---------|-------------|----------|-------|-------------------------|
| V1      | **45×170 mm** | 10 500 | 1     | Kan skarvas vid behov   |
| V2      | **45×170 mm** | 3 240  | 1     |                         |
| V3      | **45×170 mm** | 3 740  | 1     |                         |
| V4      | **45×170 mm** | 6 480  | 1     | Kan skarvas             |
| V5      | **45×170 mm** | 6 760  | 1     | Kan skarvas             |
| V6      | **45×170 mm** | 5 220  | 1     | Kan skarvas             |
| V8      | **45×170 mm** | 4 500  | 1     |                         |

### Hammarband (dubbelt)

| Vägg-ID | Dimension   | Längd mm | Antal (st) | Notering              |
|---------|-------------|----------|------------|-----------------------|
| V1      | **45×170 mm** | 10 500 | 2          | Kan skarvas           |
| V2      | **45×170 mm** | 3 240  | 2          |                       |
| V3      | **45×170 mm** | 3 740  | 2          |                       |
| V4      | **45×170 mm** | 6 480  | 2          | Kan skarvas           |
| V5      | **45×170 mm** | 6 760  | 2          | Kan skarvas           |
| V6      | **45×170 mm** | 5 220  | 2          | Kan skarvas           |
| V8      | **45×170 mm** | 4 500  | 2          |                       |

### Infälld regel under hammarband

| Vägg-ID | Dimension     | Längd mm | Antal | Notering                    |
|---------|---------------|----------|-------|-----------------------------|
| V1–V6, V8 | **45×170 mm** | Samma som vägg | 7 | En per vägg, direkt under HB |

### Överstycken

| Öppning | Dimension        | Längd mm | Antal (st) | Notering                      |
|---------|------------------|----------|------------|-------------------------------|
| D1      | **2×45×170 mm**  | 1 100    | 2          | Standard                      |
| F1      | **2×45×170 mm**  | 1 300    | 2          | Standard                      |
| F2      | **2×45×170 mm**  | 1 100    | 2          | Standard                      |
| F3      | **2×45×170 mm**  | 1 300    | 2          | Standard                      |
| **Ö1**  | **2×45×220 LVL** | **3 580**| **2**      | **PROJEKTERAS AV KONSTRUKTÖR**|

### Sidoreglar (trimmer)

| Öppning | Dimension       | Höjd mm | Antal (st) | Notering              |
|---------|-----------------|---------|------------|-----------------------|
| D1      | **2×45×170 mm** | 2 100   | 4 (2 per sida) |                  |
| F1      | **2×45×170 mm** | 1 200   | 4          |                       |
| F2      | **2×45×170 mm** | 1 000   | 4          |                       |
| F3      | **2×45×170 mm** | 1 200   | 4          |                       |
| **Ö1**  | **2×45×170 mm** | 2 100   | **4**      | **Dubbla trimmer** ▲  |

### Hörnreglar

| Hörn      | Dimension       | Höjd mm     | Antal reglar | Notering          |
|-----------|-----------------|-------------|--------------|-------------------|
| V1/V2     | **45×170 mm**   | **2 621**   | 3            | Standard          |
| V2/V3     | **45×170 mm**   | 2 777 ★     | 3            |                   |
| V3/V4     | **45×170 mm**   | 2 777 ★     | 3            |                   |
| V4/V5     | **45×170 mm**   | **3 300**   | 3            |                   |
| V5/V6     | **45×170 mm**   | **3 300**   | 3            |                   |
| V6/V7     | **45×170 mm**   | **3 300**   | 3            | Ansl. mot bef.hus |
| V8/V1     | **45×170 mm**   | **2 621**   | 3            | Standard          |

### Kortlingar (bröstning/ovan överstycke)

| Placering       | Dimension     | Längd mm | Antal ca | Notering               |
|-----------------|---------------|----------|----------|------------------------|
| Under F1 bröstn.| **45×170 mm** | 500–600  | 2        | c/c 600 under bröstning|
| Under F2 bröstn.| **45×170 mm** | 500–600  | 2        |                        |
| Under F3 bröstn.| **45×170 mm** | 500–600  | 2        |                        |
| Ovan Ö1 överst. | **45×170 mm** | 500–600  | 5        | Mellan överst./hammarb.|

---

## K.5 SAMMANFATTNING FÖR STOMLEVERANTÖR

### Beställningslista (reviderad)

| Nr | Material                    | Dimension        | Totallängd ca (m) | Antal st ca | Notering                    |
|----|------------------------------|------------------|--------------------|-------------|-----------------------------|
| 1  | Konstruktionsvirke C24       | **45×170 mm**    | Väggreglar ~160 m  | ca 58       | Olika längder               |
| 2  | Konstruktionsvirke C24       | **45×170 mm**    | Syll ~40 m         | ca 7        | Impregnerat NTR AB          |
| 3  | Konstruktionsvirke C24       | **45×170 mm**    | Hammarband ~80 m   | ca 14       | Dubbelt                     |
| 4  | Konstruktionsvirke C24       | **45×170 mm**    | Infälld regel ~40 m| ca 7        | Under hammarband            |
| 5  | Konstruktionsvirke C24       | **45×170 mm**    | Överstycken ~5 m   | ca 8        | Standard                    |
| 6  | **LVL-balk**                 | **45×220 mm**    | **3,58 m**         | **2**       | **Ö1 – PROJ. AV KONSTR.** ▲ |
| 7  | Konstruktionsvirke C24       | **45×170 mm**    | Sidoreglar ~18 m   | ca 16       | Dubbla trimmer              |
| 8  | Konstruktionsvirke C24       | **45×170 mm**    | Hörnreglar ~60 m   | ca 21       | 3 per hörn, 7 hörn          |
| 9  | Konstruktionsvirke C24       | **45×170 mm**    | Kortlingar ~6 m    | ca 11       | Under bröstning/ovan överst.|
| 10 | Konstruktionsvirke C24       | **45×220 mm**    | Takreglar ~160 m   | ca 32       | Inkl. kantbalkar            |
| 11 | Konstruktionsvirke C24       | **45×220 mm**    | Bärlina ~7,5 m     | 1           | Mot befintligt hus          |
| 12 | Konstruktionsvirke C24       | **45×220 mm**    | Stödreglar ~2,9 m  | ca 13       | Under bärlina, 45 mm utbyggn.|
| 13 | Installationsläkt            | **28×70 mm**     | Tak ~140 m         | –           | Tvärs takreglar             |
| 14 | Installationsskikt           | 45×45 mm         | Vägg ~90 m         | –           | Horisontella reglar c/c 600  |
| 15 | Luftspaltsläkt               | **28×70 mm**     | Vägg ~160 m        | –           | Vertikal, c/c 600            |
| 16 | Impregnerat virke NTR AB     | **45×170 mm**    | Syll ~40 m         | –           | Ingår i rad 2               |

### Skivmaterial

| Nr | Material                    | Tjocklek | Ca yta m²  | Notering                    |
|----|------------------------------|----------|------------|-----------------------------|
| 17 | Putsskiva                    | **12 mm**| ca 95      | Utsida fasad                |
| 18 | Utvändig isolerskiva (Fasadboard) | **45 mm** | ca 95 | Fasadboard/Västkustskiva  |
| 19 | Träfiberskiva (OSB/Plywood)  | **11 mm**| ca 95      | Invändigt                   |
| 20 | Gipsskiva invändig           | 13 mm    | ca 155     | Väggar + innertak           |
| 21 | Råspont tak                  | **20 mm**| ca 60      | Tak                         |

### Isolering

| Nr | Material                    | Tjocklek | Ca yta m²  | Notering                    |
|----|------------------------------|----------|------------|-----------------------------|
| 22 | Isolering väggar (reglar)    | **170 mm**| ca 95     | I regelstomme 45×170        |
| 23 | Isolering väggar (inst.sk)   | 45 mm    | ca 95      | I installationsskikt        |
| 24 | Isolering tak                | **220 mm**| ca 60     | I takregel 45×220           |

### Takriktning och huvudmått

```
         ← 7 480 →            ← 3 740 →
    ┌────────────────────┬──────────────┐
    │                    │              │   ↑
    │  PULPETTAK 8,6°    │  PULPETTAK   │   │ 6 480
    │  Fall →            │  8,6° Fall → │   │
    │                    │              │   │
    │ Hög sida 3 300 ───►│◄─────────────│   ↓
    │ (bef.hus 220 mm)   │              │
    │                    │              │   ↑
    │                    ├──────────────┘   │ 3 240
    │                    │                  │
    │ Låg sida 2 621 ───►│                  ↓
    └────────────────────┘
    ← ─────── 10 500 ──────── →

    Avstånd bef. vägg–gavel: 2 980 mm
    Öppning Ö1: 3 380 mm
    Höjdskillnad: 679 mm
```

---

## K.6 LEVERANTÖRSNOTERINGAR

1. ★ = Mått kräver kontrollmätning på plats innan beställning
2. ▲ = Kräver konstruktörsverifiering/dimensionering
3. Alla regelhöjder varierar pga pulpettakets lutning (**8,6°**) – leverantör ska beräkna exakta kaplängder baserat på c/c-avstånd och taklutning
4. Öppningsmått för Ö1 (**3 380 mm**) är **FASTSTÄLLT** enligt specifikation
5. Bärlina V7 (45×220, L=7 480) och stödreglar (45×220) levereras separat – icke standard väggelement
6. Syllvirke ska vara impregnerat NTR AB
7. Hammarband är dubbelt – levereras som separata virken
8. **Infälld regel** under hammarband i samtliga väggar – levereras som separat virke
9. Alla längder inkluderar ej kap- och spill. Rekommenderat spill: +10 %
10. LVL-balk för Ö1 beställs efter konstruktörens dimensionering
11. **Sovrumsfönster mot befintligt hus har tagits bort** – ingen öppning i väggen mot befintligt hus (utöver Ö1)

---
* Fältreglar = genomgående väggreglar enligt c/c-modul, exklusive öppningsreglar, hörnreglar, syll och hammarband.

*Reviderad 2026-07-08 enligt projekteringsspecifikation. Väggreglar 45×170 c/c 600, takreglar 45×220 c/c 600, bärlina 45×220, taklutning 8,6°, öppning 3 380 mm.*
