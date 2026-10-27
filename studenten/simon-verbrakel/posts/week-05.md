# Week 5

## Mijn value chain, met de foutmarge erin

Productiesetup: Haiku 5.5. Score uit `build/foutmarge.md`: v3 haalt 9 tot 10 op 10 (3 runs, n = 10). Alle bronnen: **gemeten**, **gevraagd** (aan iemand) of **geschat**.

| Schakel | Waarde | Bron |
|---|---|---|
| 1. Met de hand | Openen 15 s · lezen 30 s · beslissen 30 s · noteren 20 s = **95 s** | geschat (uit week 4), nog niet met een stopwatch gemeten |
| 2. Score | 9 tot 10 op 10 (foutmarge, n = 10, 3 runs) | gemeten (`build/foutmarge.md`) |
| 2. Met de tool | Vinden en openen 15 s · kopiëren en plakken 10 s · wachten 8 s · nakijken 10 s = 43 s. Fouten herstellen = deel fout × 95 s: bij 9/10 is dat 10% × 95 = 9,5 s, bij 10/10 is dat 0 s. Samen **52,5 s** (9/10) of **43 s** (10/10) | wachttijd gemeten (week 4), rest geschat (uit week 4), foutdeel gemeten |
| 3. Winst per bericht | 95 − 52,5 = **42,5 s** (9/10) · 95 − 43 = **52 s** (10/10) | berekend |
| 4. Volume | 5 per dag · 25 per week · 100 per maand · **1.100 per jaar** | geschat. Ik gebruik de tool zelf als particuliere belegger: ik volg elke werkdag ongeveer 5 nieuwsberichten over defensie op voor ik beslis over mijn aandelen. Dat schreef ik ook in week 4. De 30 per dag in `build/kosten.md` was te hoog. Aanname: 220 werkdagen per jaar (zoals in de README), dus 1.100 en niet 12 × 100 |
| 5. Uren per jaar | 42,5 s × 1.100 = **13 u** (9/10) · 52 s × 1.100 = **15,9 u** (10/10) | berekend |
| 6. Uurkost | €14,38 bruto × 1,5 = **€21,57** | bruto gemeten bij Indeed België (gemiddeld basisloon student, 11 oktober 2026, https://be.indeed.com/career/student/salaries). Factor 1,5: vuistregel uit `cursus/week-05/README.md` (Acerta, Securex, Teamed), aanname |
| 7. Kost van de tool | 1.100 × $0,00042 = $0,46 = **€0,42 per jaar** (Haiku 5.5, 2.600 tokens in, 319 uit, 1 dollar = 0,90 euro) | gemeten (`build/modellen.md`, prijs uit de tabel van week 5); wisselkoers is een aanname |
| 8. Netto per jaar | 13 × 21,57 − 0,42 = **± €280** (9/10) · 15,9 × 21,57 − 0,42 = **± €342** (10/10) | berekend |
| 9. Bereik | **± €280 tot ± €342 per jaar**. Midden (9,5/10): ± €311 | foutmarge |
| 10. Zwakste cijfer | De 95 s met de hand: geschat, niet gemeten. Is het de helft (47,5 s), dan is het netto **± €29** (10/10) of **± −€2** (9/10), midden ± €14. Bij 9/10 wint de tool dan niets meer. Daarbij daalt ook het fouten herstellen, want dat is 10% van de handtijd. | geschat |

**Wat beweegt het netto het meest?** De 95 s. Mijn foutmarge (9 tot 10 op 10) verschuift het netto met ± €62 per jaar. Als de handtijd de helft is, verschuift het netto met ± €300. Mijn zwakste cijfer weegt dus ongeveer vijf keer zwaarder dan de foutmarge.

**Tweede zwak punt:** de uurkost. Ik ben geen werkgever. €21,57 is wat mijn tijd waard is tegen een studentenloon plus de factor 1,5, een aanname. Het bedrag is klein: bij 1.100 berichten per jaar gaat het om 13 tot 16 uur.

**Te doen:** handtijd meten met een stopwatch op enkele berichten.
