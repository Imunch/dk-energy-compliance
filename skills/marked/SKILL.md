---
name: marked
description: Compliance for det engrosenergimarked som danske aktører handler på — REMIT II, CACM, SDAC/SIDC, 15-minutters MTU, UMM-offentliggørelse, markedsdeltagerregistrering og balanceansvar. Anvend når brugeren spørger om markedsmisbrug, inside information, bidding zones, gate closure, NTC/Flow-Based kapacitetsberegning eller BRP/BSP-roller.
---

# Marked — Skill til engrosenergimarkedet

Dette skill dækker regulatoriske spørgsmål om engroshandel med elektricitet og naturgas, med fokus på REMIT II og CACM-regelsættet.

## Hvornår dette skill er relevant

Aktivér på spørgsmål der involverer:

- **REMIT II** (EU 2024/1106) — ny forordning fra 2024 der reviderer REMIT (1227/2011). Registrering, inside info, markedsmanipulation, algoritmisk handel, ACER-tilsyn
- **CACM** (EU 2015/1222) — kapacitetsallokering og flaskehalshåndtering, SDAC, EUPHEMIA, budzoner
- **EBGL** (EU 2017/2195) — BRP, BSP, imbalance settlement, PICASSO, MARI
- 15-minutters **MTU** — konsekvenser for Nord Pool, XBID, balancering
- **Markedsmisbrug** — spoofing, wash trades, layering, cross-market, physical withholding
- **UMM** (Urgent Market Messages) og inside information efter art. 4
- Danske markedsdeltagere, Forsyningstilsynets tilsyn, ACER-koordinering

## Grundprincipper

1. **REMIT II-centreret** — 2024/1106 er ny norm. Citér altid både 2024/1106 OG den tilsvarende artikel i 1227/2011 hvor relevant, så brugeren kan se kontinuiteten.
2. **Kvantificér sanktioner præcist** — REMIT II hæver maks-bøde til 15% af omsætning eller 15 mio. EUR for juridiske personer, 5 mio. EUR for fysiske. Angiv altid beregningsgrundlag.
3. **Farvekodede risici** — Grøn (formalia), Gul (regelbrud), Orange (sanktion), Rød (strafansvar).
4. **ACER/FST-perspektiv** — angiv hvem der fører tilsyn (ACER direkte, Forsyningstilsynet nationalt) og hvem der efterforsker.
5. **Handlingsorienteret** — når brugeren spørger hvad de skal gøre, giv konkrete trin: hvordan registrere, hvordan rapportere UMM, hvordan teste algoritmisk kill-switch.
6. **Forsigtighed om konkrete sager** — historiske enforcement-sager skal verificeres mod ACER's REMIT Quarterly Reports eller nationale regulatorers afgørelser før citering med præcise bøde-beløb eller årstal. Referér hellere til typologi end til specifikke sager.

## Arbejdsproces

1. Identificér markedssegment (SDAC, SIDC, balancering, derivater, gas).
2. Identificér aktørrolle (producent, forbruger, trader, BRP, BSP, NEMO).
3. Slå op i `references/`.
4. Ved misbrug-spørgsmål: list indikatorer (ikke kun definition), og tjek Forsyningstilsynet-praksis.
5. Strukturér: Hjemmel → Krav/forbud → Indikatorer → Sanktionsrisiko → Næste skridt.

## Referencer

- `references/remit-ii.md` — 2024/1106 opsummeret, sammenligning med 1227/2011
- `references/cacm.md` — CACM 2015/1222, SDAC, SIDC, EUPHEMIA
- `references/ebgl.md` — EBGL 2017/2195, balancering, PICASSO/MARI
- `references/markedsmisbrug-typologi.md` — Kategorier, indikatorer, detektionssignaler
- `data/nemos.json` — Nominated Electricity Market Operators
- `templates/umm-template.md` — Skabelon til UMM-offentliggørelse

## Output-mønstre

- Tabel ved sammenligning (REMIT I vs II, BRP vs BSP, NTC vs FB).
- `<pre>` til tidslinjer (gate closure, SDAC-day D-1 12:00 → D+1 settlement).
- Indikator-lister efter misbrugsdefinition.

## Værdi

Støtter compliance-officers, risk/legal-funktioner hos energihandlere, og TSO-tilsyn. Ikke juridisk rådgivning — udgangspunkt for interne drøftelser og for dialog med Forsyningstilsynet.
