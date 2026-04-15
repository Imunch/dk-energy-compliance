---
name: gas
description: Dansk og EU regulering af naturgas og brint — Gas Package 2024 (Forordning 2024/1789 + Direktiv 2024/1788), Lov om gasforsyning, brintinfrastruktur, certificering af grøn brint (RFNBO), ENTSOG-netkoder, oplagring, forsyningssikkerhed (SoS 2017/1938). Anvend når brugeren spørger om gasnetadgang, tarifering, brint-tilslutning, certificeringsordninger for brint eller aftagepligter.
---

# Gas & Brint — Skill til gas- og brintregulering

Dette skill dækker den regulatoriske ramme for naturgas- og brint-infrastruktur i Danmark og EU, med fokus på den nye "Gas Package" fra 2024 der integrerer brint i gas-reguleringen.

## Hvornår dette skill er relevant

Aktivér på spørgsmål der involverer:

- **Gas Package 2024** — Forordning (EU) 2024/1789 (ny gas- og brintforordning) og Direktiv (EU) 2024/1788 (nyt gas- og brintdirektiv). Trådt i kraft august 2024, implementeringsfrist for DK: **5. august 2026**
- **Lov om gasforsyning** (LBK 1100/2023) — dansk gasforsyningslov, netoperatør-pligter, Energinet som TSO
- **Brintinfrastruktur** — dedikeret brintnet, tredjepartsadgang (TPA), tariffering, ENNOH (European Network of Network Operators for Hydrogen)
- **RFNBO** (Renewable Fuels of Non-Biological Origin) — Delegeret forordning 2023/1184 + 2023/1185 (additionalitet, geografisk og tidsmæssig korrelation, tælling)
- **Certificering af grøn brint** — ISCC EU, TÜV, national ordning via Klima-, Energi- og Forsyningsministeriet
- **Biometan/opgraderet biogas** — indfødning i gasnet, tilslutningsvilkår, BNG-certifikater
- **ENTSOG netkoder** — TAR NC (tarifering 2017/460), CAM NC (kapacitetsallokering 2017/459), BAL NC (balancering 312/2014), INT NC (interoperabilitet 2015/703)
- **Forsyningssikkerhed** — Forordning (EU) 2017/1938 (SoS-forordningen), N-1-kriteriet, præventiv handlingsplan
- **Oplagring** — Forordning (EU) 2022/1032 (oplagringsforordning fra 2022 med 90%-målsætning), Stenlille som dansk gasoplag
- Skift fra fossilgas til brint, repurposing af eksisterende rørledninger, Energinets brintinfrastruktur-udrulning

## Grundprincipper (skal altid overholdes)

1. **Gas Package 2024 er den nye norm** — forsyning efter 2026. Citér både 2024/1789 og den forudgående 715/2009, og både 2024/1788 og 2009/73/EF, så brugeren kan se kontinuitet og ændringer.
2. **Skeln mellem fossilgas, biometan og brint** — regulatoriske definitioner er forskellige. Biometan = "VE-gas", brint = særlig definition (art. 2 i 2024/1789). Blandinger har egne regler.
3. **Citér retskilden præcist** — forordning/direktiv + artikel + dansk implementering. Energinet er certificeret TSO for både gas og (kommende) brint.
4. **RFNBO-kriterier er tekniske og kvantitative** — additionalitet (ny VE), geografisk (bud-zone eller direkte forbindelse), tidsmæssig (time-for-time fra 2030). Angiv disse kvantitativt når brugeren spørger om certificering.
5. **Vær præcis om infrastruktur-roller** — Energinet TSO, Evida som DSO (distribution), Gas Storage Denmark A/S (oplagring i Stenlille/Lille Torup). Disse har forskellige forpligtelser.
6. **Verificér før citat** — den danske implementering af Gas Package 2024 er under udarbejdelse (frist 5/8-2026). Konkrete danske regler skal bekræftes mod Energistyrelsens lovprogram og Forsyningstilsynets afgørelser.

## Arbejdsproces

1. Identificér energibærer (fossilgas, biometan, brint, blanding) og aktørrolle (producent, shipper, TSO, DSO, forbruger).
2. Bestem om spørgsmålet angår EU-forordning (direkte virkning), direktiv (national implementering) eller dansk ret.
3. Map til konkret artikel i Gas Package + tilsvarende bestemmelse i tidligere regulering.
4. Ved brint-spørgsmål: tjek om RFNBO-kvalifikation er nødvendig (for at tælle mod VE-mål eller for incitamenter).
5. Strukturér svar: Kort konklusion → Hjemmel → Konkrete krav → Dansk kontekst (Energinet/Evida/FST) → Næste skridt.

## Output-mønstre

- **Tabel** til sammenligning Gas Package 2024 vs. tidligere regulering, eller fossilgas vs. biometan vs. brint.
- **Tidslinje** for implementeringsfrister (EU-ikrafttræden vs. national frist).
- **Beregningseksempler** for RFNBO-tælling (MWh VE per MWh brint, additionalitetsberegning).

## Referencer

- `references/gas-package-2024.md` — Forordning 2024/1789 + Direktiv 2024/1788 opsummeret
- `references/gasforsyningsloven.md` — LBK 1100/2023, Energinets pligter
- `references/rfnbo.md` — Delegerede forordninger 2023/1184 + 2023/1185
- `references/entsog-netkoder.md` — TAR, CAM, BAL, INT
- `references/sos.md` — Forsyningssikkerhed 2017/1938 + oplagring 2022/1032
- `references/brintinfrastruktur.md` — Energinets brintplan, dedikeret net, repurposing
- `data/danske-gaspunkter.json` — Entry/exit-punkter, storage, bio-opgraderingsanlæg

## Værdi — hvad skal dette skill producere

Ikke endelig juridisk eller kommerciel rådgivning. Et operationelt arbejdsredskab for projektudviklere, shippers, rådgivere og compliance-funktioner i sektoren. Alle svar er udgangspunkt — endelig vurdering kræver jurist, Energinet-dialog og Forsyningstilsynets eventuelle afgørelser.
