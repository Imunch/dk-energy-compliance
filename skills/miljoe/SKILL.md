---
name: miljoe
description: Dansk og EU miljø-, klima- og VE-ret for energiprojekter. Anvend når brugeren spørger om EU ETS, CBAM, RED III go-to zones, VVM-proces, Klimaloven 70%/2045, havvind-udbud (Thor, energiøer), VE-loven, miljøgodkendelse efter MBL kap. 5 eller den samlede tilladelsesproces for et energiprojekt.
---

# Miljø — Skill til klima-, miljø- og VE-ret

Dette skill dækker det regulatoriske landskab for planlægning, tilladelser og drift af energianlæg i Danmark — med integrerede EU-krav.

## Hvornår dette skill er relevant

Aktivér på spørgsmål der involverer:

- **EU ETS** fase 4 (2021-2030) — direktiv 2003/87 med ændringer fra 2023/959 (Fit for 55), MSR, ETS2
- **CBAM** (EU 2023/956) — grænsetilpasningsmekanisme, rapporteringsforpligtelser, fuld ikrafttræden 1. januar 2026
- **RED III** (EU 2023/2413) — 42,5% VE-mål 2030, go-to zones art. 15c, strategisk miljøvurdering
- **VVM** — Miljøvurderingsloven LBK 4/2023, bilag 1/2, proces
- **Klimaloven** (Lov 965/2020) — 70%/2030, neutralitet 2045, Klimarådet, årlige programmer
- **Havvind** — statsudbud (Thor, Horns Rev), energiøer, open-door (pauset)
- **VE-loven** (LBK 1791/2023) — køberet, værditab, grøn pulje, bonusordning, PtX-udbud
- **Miljøgodkendelse** — MBL kap. 5 § 33, listevirksomheder, IED 2010/75, BREF/BATC
- Relation mellem EU Fit for 55, ESR (2018/842), LULUCF (2018/841) og dansk målsætning

## Grundprincipper

1. **Bindende EU-mål som anker** — RED III 42,5%, ETS -62% vs 2005 i 2030, klimaneutralitet 2050 (EU) / 2045 (DK).
2. **Dansk skærpelse flagges** — hvor DK går videre end EU-minimum (70%/2030, 2045-neutralitet, PtX-udbud).
3. **Proces før substans** — mange projektspørgsmål er i virkeligheden tilladelsesspørgsmål: VVM, habitatscreening, miljøgodkendelse, lokalplan.
4. **Økonomisk kvantificering** — ETS-pris (EUA), CBAM-omkostning per ton CO2e, VE-udbudspriser, koncessionsafgift for havvind.
5. **Lokal accept som juridisk krav** — køberet (20%), værditab, grøn pulje (30-165.000 DKK/MW), VE-bonus. Oversæt til projektøkonomi.
6. **Tidshorisont eksplicit** — angiv om krav er gældende, vedtaget men ikke implementeret, eller under forhandling.

## Arbejdsproces

1. Klassificér projektet (landvind / havvind / sol / PtX / biogas / transmission / industri).
2. Identificér relevante retskilder (EU direktiv/forordning + dansk implementering).
3. Skitsér tilladelsesprocessen i rækkefølge.
4. Kvantificér tidsrammer og omkostninger.
5. Afslut med retskildeliste.

## Referencer

- `references/eu-ets.md` — Direktiv 2003/87 + 2023/959 opsummeret
- `references/cbam.md` — Forordning 2023/956 med tidslinje og produktliste
- `references/red-iii.md` — Direktiv 2023/2413, go-to zones, frister
- `references/klimaloven.md` — Lov 965/2020 med governance-mekanismer
- `references/vvm.md` — LBK 4/2023 og VVM-direktivet 2011/92
- `references/ve-loven.md` — LBK 1791/2023, støtte og lokal accept
- `data/havvind-projekter.json` — Danske havvind-udbud og status

## Output-mønstre

- Mål-tabeller med basisår og deadline.
- Proces-ordnede lister (VVM-trin).
- Pre-blokke til beregninger (CBAM-beløb, CfD-kontrakter).

## Værdi

Støtter projektudviklere, kommuner, miljøkonsulenter og Energinet's egne planlægningsteams. Ikke udtømmende — komplekse habitat- og artsbeskyttelsesspørgsmål (fugle, flagermus, marsvin) kræver specialist-konsulent. Brug dette skill som indgangspunkt, ikke som endelig vurdering.
