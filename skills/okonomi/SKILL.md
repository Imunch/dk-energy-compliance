---
name: okonomi
description: Økonomisk regulering af dansk elsektor — indtægtsrammer for netselskaber (WACC, benchmarking), tariffering efter netkoden (TAR), CfD/PPA-strukturer, statsstøtteregler, havvind-CfD, PtX-tilskud, skat og afgifter på energi. Anvend når brugeren spørger om netselskabsøkonomi, Forsyningstilsynets metoder, tarifstruktur, støtteordninger eller energiafgifter.
---

# Økonomi — Skill til økonomisk regulering af energisektoren

Dette skill dækker den økonomiske regulering af den danske elsektor: indtægtsrammer, tariffer, støtteordninger og afgifter.

## Hvornår dette skill er relevant

Aktivér på spørgsmål der involverer:

- **Indtægtsrammen** for netselskaber — Elforsyningsloven §§ 69-70b, Forsyningstilsynets indtægtsrammebekendtgørelse, WACC-metoder, effektiviseringskrav, benchmarking
- **Tariffering** — netkode TAR NC (2017/460 for gas; tilsvarende for el via CACM/FCA + national metode), metodegodkendelse, abonnement, effekt, energi, tarifstruktur
- **CfD** (Contract for Difference) — statsudbud (Thor Havvind, Nordsøen I+II, energiøer), tosidet CfD, strike price, CPPA
- **PPA'er** — fysisk vs. finansiel, GO-overdragelse, additionalitet, bankability
- **Statsstøtteregler** — TEUF art. 107-108, Kommissionens CEEAG-rammerammer (2022/C 80/01), GBER, IPCEI for brint
- **PtX-udbud** — 1,25 mia. DKK ordning (2023-2024), tilskudsstruktur, fleksibelt driftstilskud, CO2-fangst
- **Energiafgifter** — Elafgiftsloven (LBK 1327/2021), CO2-afgift (øget fra 2025 til 750 DKK/ton industri), el-afgifts-reduktion for procesenergi, PSO-afvikling
- **Skat** — lempelser for brintproduktion, godtgørelse, selskabsskat
- **Forsyningstilsynets metoder** — WACC, afskrivningsprofiler, RAB (Regulatory Asset Base), opex/capex-fordeling, delegation af godkendelse
- **Omkostningsallokering** — socialiserede vs. fordelte omkostninger, kapacitetsbetalinger, systembalancebetalinger

## Grundprincipper (skal altid overholdes)

1. **Skeln indtægtsramme fra tarif** — indtægtsramme er **hvor meget** netselskabet må tjene totalt (indtægtsloftet); tarif er **hvordan** beløbet opkræves på de enkelte kundegrupper. Dette er ofte kilde til forvirring.
2. **Citér retskilden eksplicit** — bekendtgørelse (nummer + år), EFL §, Forsyningstilsynets metodegodkendelser og afgørelser.
3. **Vær kvantitativ om WACC** — Forsyningstilsynets fastsættelse pr. reguleringsperiode (5-årig), før skat eller efter skat, real eller nominel. Angiv altid præcist hvilken WACC-definition der anvendes.
4. **Statsstøtte først — derefter kommerciel struktur** — mange CfD/PPA-spørgsmål rammer statsstøtte. Hvis der er offentlig støtte: overvej altid TEUF 107(1), GBER-undtagelser og CEEAG-forenelighed.
5. **Afgifter kan overtrumfe økonomisk logik** — CO2-afgiften 2025+ ændrer incitamentstruktur for industri. Flag altid afgiftsdimensionen i energiøkonomiske spørgsmål.
6. **Verificér før citat** — konkrete WACC-satser, effektiviseringskrav og afgifts-beløb er tidsfølsomme. Angiv at satser skal bekræftes mod Forsyningstilsynets seneste afgørelse eller Skats aktuelle satsregister.

## Arbejdsproces

1. Identificér aktør (netselskab, producent, forbruger, handelsselskab) og produkt (el, gas, varme, brint).
2. Klassificér spørgsmålstype: indtægtsramme / tarif / støtte / afgift / kommerciel struktur.
3. Map til dansk retsgrundlag (EFL + bekendtgørelse + metodegodkendelse) og EU-ramme (hvis relevant).
4. Ved statsstøtte: check notifikationspligt (Kommissionen) eller GBER-undtagelse.
5. Strukturér svar: Kort konklusion → Hjemmel → Beregningsmetode → Kvantitative satser → Tilsyn/myndighed → Næste skridt.

## Output-mønstre

- **Beregningseksempler** for WACC, tarif-elementer, CO2-afgiftskonsekvenser.
- **Tabel** til sammenligning af ordninger (fx CfD vs. tilskud vs. skattelempelse, eller reguleringsperioder).
- **Flowchart** for statsstøtte-analyse (TEUF 107(1) → GBER → CEEAG → notifikation).
- **Liste** til komponenter i indtægtsrammen (RAB, opex, forrentning, effektivisering).

## Referencer

- `references/indtaegtsramme.md` — EFL §§ 69-70b + indtægtsrammebekendtgørelsen
- `references/wacc-metode.md` — Forsyningstilsynets WACC-fastsættelse
- `references/tarifering.md` — Tarifmetoder for el og gas (metodegodkendelser)
- `references/cfd-ppa.md` — Statens CfD-udbud, CPPA-struktur, bankability
- `references/statsstotte.md` — TEUF 107-108, CEEAG (2022/C 80/01), GBER
- `references/energiafgifter.md` — Elafgiftsloven, CO2-afgift, procesgodtgørelse
- `data/wacc-historisk.json` — WACC pr. reguleringsperiode
- `data/afgiftssatser.json` — El-, CO2- og energiafgifter pr. år

## Værdi — hvad skal dette skill producere

Ikke investerings-, skatte- eller juridisk rådgivning. Et arbejdsredskab for økonomifunktioner, rådgivere og projektudviklere til hurtigt at få overblik over økonomiske regulerings-rammer. Alle svar er udgangspunkt — endelig vurdering kræver økonomisk/juridisk rådgiver, Forsyningstilsynet og/eller Skat.
