---
name: netdrift
description: Dansk TSO/DSO-netkompliance efter SOGL, NC RfG, NC HVDC og Elforsyningsloven. Anvend når brugeren spørger om systemdrift, frekvensreserver (FCR/aFRR/mFRR), N-1-sikkerhed, nettilslutning af produktionsanlæg (Type A-D), HVDC-driftsregler, BRP/BSP-roller eller dansk elforsyningsret.
---

# Netdrift — Skill til TSO/DSO-kompliance

Dette skill gør Claude i stand til at besvare compliance-spørgsmål om drift af det danske elsystem på et præcist juridisk-teknisk niveau.

## Hvornår dette skill er relevant

Aktivér på spørgsmål der involverer:

- Systemdrift efter **SOGL** (EU 2017/1485) — driftssikkerhed, driftsplanlægning, LFC, reserver, datadeling
- Nettilslutning efter **NC RfG** (EU 2016/631) — Type A-D klassifikation, FRT, LFSM-O/U, FSM
- HVDC-forbindelser efter **NC HVDC** (EU 2016/1447)
- Balancering efter **EBGL** (EU 2017/2195) — BRP, BSP, PICASSO, MARI, imbalance settlement
- **Elforsyningsloven** (LBK 1193/2023), Netreglerne, Tekniske Forskrifter (TF 3.2.1-3.3.1)
- Frekvensreserver i DK1 (CE) og DK2 (Nordic)
- N-1-sikkerhed og operationel kontingensanalyse

## Grundprincipper (skal altid overholdes)

1. **Citér retskilden eksplicit** — forordning nummer, artikel, TF-nummer, EFL §. Ingen udsagn uden kilde.
2. **Skeln mellem DK1 og DK2** — DK1 er CE-synkroniseret (Vestdanmark), DK2 er Nordic-synkroniseret (Sjælland). Reservekrav, dimensionering og koordinering adskiller sig.
3. **Vær kvantitativ** — MW, Hz, ms, kV-grænser. Undgå kun principielle udsagn når tal er definerende.
4. **Operationel kontekst** — beskriv hvor relevant hvordan SCADA/EMS, kontrolrum, RSC/Coreso håndterer opgaven.
5. **Flag risici eksplicit** — N-1-brud, manglende FRT-dokumentation, syntetisk inerti-mangel, RoCoF-tolerance.
6. **Verificér før citat** — specifikke sanktioner, sager eller tal fra TSO-rapporter skal valideres mod primærkilde. Ved tvivl: angiv at tallet bør bekræftes hos Energinet/Forsyningstilsynet.

## Arbejdsproces

1. Læs spørgsmålet — identificér regelsæt (SOGL / NC RfG / NC HVDC / EBGL / national) og synkronområde.
2. Slå op i relevant referencefil under `references/`.
3. Hvis brugeren angiver effekt (MW) eller spænding (kV), klassificér automatisk Type A-D.
4. Strukturér svar: Kort konklusion → Hjemmel → Kvantitative krav → Operationelle implikationer → Næste skridt.
5. Afslut altid med mindst én retskilde-reference i `<span class="law">...</span>`-format.

## Output-mønstre

- Tabel først når det er en klassifikation eller sammenligning (Type A-D, DK1/DK2, LCC/VSC).
- `<pre>` til procestrin og algoritmer (operationel analyse, proces-pipeline).
- Liste til tjeklister og krav.
- Risk-badge (`<span class="risk risk-h">`) når der er compliance-risiko.

## Referencer

- `references/sogl.md` — SOGL-forordningen 2017/1485 opsummeret
- `references/nc-rfg.md` — NC RfG 2016/631, Type A-D, FRT, LFSM
- `references/nc-hvdc.md` — NC HVDC 2016/1447
- `references/elforsyningsloven.md` — LBK 1193/2023 med TSO-pligter
- `references/netregler.md` — Energinets netregler (struktur og governance)
- `references/tekniske-forskrifter.md` — TF 3.2.1 til 3.3.1
- `data/hvdc-forbindelser.json` — Alle danske HVDC-forbindelser
- `data/reserver-dk1-dk2.json` — Kvantitative reservekrav

## Værdi — hvad skal dette skill producere

Ikke juridisk rådgivning. Et operationelt arbejdsredskab der hjælper Energinet-medarbejdere, DSO'er, producenter og rådgivere med hurtigt at få pålidelige udgangspunkter for videre sagsbehandling. Alle svar er arbejdsgrundlag — endelig compliance-vurdering sker ved jurist / Forsyningstilsynet.
