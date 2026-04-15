---
name: cyber
description: Cybersikkerhed og resiliens for den danske energisektor — NIS2, CER, Network Code on Cybersecurity (NCCS), sektorspecifikke krav fra Energistyrelsen og Energinet. Anvend når brugeren spørger om hændelsesrapportering, OT/IT-segmentering, leverandørkrav, risikostyring, beredskab eller tilsyn efter NIS2/CER for energiaktører.
---

# Cyber — Skill til cybersikkerhed og fysisk resiliens

Dette skill dækker det regulatoriske rammeværk for cybersikkerhed og kritisk infrastrukturbeskyttelse i den danske energisektor, med fokus på NIS2, CER og det sektorspecifikke Network Code on Cybersecurity.

## Hvornår dette skill er relevant

Aktivér på spørgsmål der involverer:

- **NIS2** (EU 2022/2555) — netværks- og informationssikkerhedsdirektivet 2. generation, implementeret i DK med Lov om foranstaltninger til sikring af et højt cybersikkerhedsniveau (NIS2-loven)
- **CER** (EU 2022/2557) — Critical Entities Resilience direktivet (fysisk modstandsdygtighed for kritiske enheder)
- **NCCS** — Network Code on Cybersecurity for el-sektoren (Kommissionsforordning 2024/1366)
- **GDPR** krydsfelt — personoplysninger i SCADA-adgange, målerdata, mv.
- **Sektorkrav fra Energistyrelsen** — bekendtgørelser om beredskab, IT-beredskab, fysisk sikring
- **Energinets krav** — leverandørklausuler, DSO/TSO-interface, certificering
- Hændelsesrapportering (tidsfrister 24/72 t / 1 md.), risikostyring, leverandørsikkerhed
- OT/IT-segmentering, ICS/SCADA-sikkerhed, IEC 62443, NERC CIP-paralleller

## Grundprincipper (skal altid overholdes)

1. **Skeln klart mellem NIS2 og CER** — NIS2 = cyber, CER = fysisk. Mange energiaktører er omfattet af begge.
2. **Energy er "højt kritisk sektor"** — bilag 1 i NIS2: elektricitet, fjernvarme, olie, gas, brint. Det betyder **væsentlige enheder** (tungeste forpligtelser) ved tærskelværdier.
3. **Citér retskilden eksplicit** — artikelnummer, betragtning hvis relevant, national gennemførelseslov. Skeln direktivet (2022/2555) fra den danske lov.
4. **Tidsfrister er absolutte** — tidlig varsling 24 t, hændelsesrapport 72 t, afsluttende rapport 1 måned. Gør dette tydeligt i ethvert svar om hændelser.
5. **Ledelsesansvar er personligt** — NIS2 art. 20 kræver at bestyrelse/direktion godkender risikostyring og deltager i træning. Nævn dette når spørgsmålet angår governance.
6. **Sanktionsniveau** — op til 10 mio. EUR / 2% af årlig global omsætning for væsentlige enheder. Præcisér at dette er EU-niveau; dansk implementering kan afvige.
7. **Verificér før citat** — konkrete DK-bekendtgørelser og -vejledninger udvikler sig hurtigt. Angiv at krav skal bekræftes mod Center for Cybersikkerhed (CFCS), Energistyrelsen eller Energinets beredskabsvejledning.

## Arbejdsproces

1. Identificér aktørtype: TSO, DSO, producent, aggregator, leverandør, handler.
2. Klassificér under NIS2: **væsentlig enhed** (essential) eller **vigtig enhed** (important) — tærskler er sektor- og størrelsesbaserede.
3. Bestem om CER også gælder (kritisk enhed i forsyning af el/gas/olie).
4. Map spørgsmålet til artikelniveau: art. 20 (ledelse), art. 21 (tekniske foranstaltninger), art. 23 (rapportering), art. 24-25 (certificering), art. 32-37 (tilsyn/sanktion).
5. Strukturér svar: Kort konklusion → Omfattet? → Konkret forpligtelse → Frist/tærskel → Tilsynsmyndighed → Næste skridt.
6. Afslut med mindst én retskilde-reference.

## Output-mønstre

- **Tabel** til klassifikation (væsentlig vs. vigtig enhed, NIS2 vs. CER, sektortærskler).
- **Tidslinje** til hændelsesrapportering (24 t → 72 t → 1 md.).
- **Risk-badge** ved compliance-gab (`<span class="risk risk-h">` for akut gap, `risk-m` for forbedringsbehov).
- **Liste** til art. 21 foranstaltninger (politikker, håndtering, kontinuitet, supply chain, kryptografi, mv.).

## NIS2 art. 21 minimum-foranstaltninger (10-punkts-listen)

Alle omfattede enheder skal implementere:

1. Politikker for risikoanalyse og informationssikkerhed
2. Hændelseshåndtering
3. Forretningskontinuitet (backup, genopretning, kriseledelse)
4. Forsyningskædesikkerhed (leverandør- og tjenesteudbyder-relationer)
5. Sikkerhed i anskaffelse, udvikling og vedligehold af IT-systemer, herunder sårbarhedshåndtering
6. Politikker og procedurer til vurdering af risikostyringsforanstaltningernes effektivitet
7. Grundlæggende cyberhygiejne og træning
8. Politikker og procedurer om kryptografi
9. HR-sikkerhed, adgangskontrol, aktivstyring
10. Multi-faktor-godkendelse, sikret kommunikation, sikret nødkommunikation

## Referencer

- `references/nis2.md` — Direktiv (EU) 2022/2555 opsummeret med artikelreference
- `references/cer.md` — Direktiv (EU) 2022/2557 (Critical Entities Resilience)
- `references/nccs.md` — Network Code on Cybersecurity (2024/1366) for el-sektoren
- `references/dk-implementering.md` — NIS2-loven, CFCS-vejledninger, Energistyrelsens bekendtgørelser
- `references/hændelsesrapportering.md` — Tidslinje, tærskler, skabeloner
- `references/leverandørkæde.md` — Art. 21(2)(d) og ENISA-vejledninger for supply chain

## Værdi — hvad skal dette skill producere

Ikke certificeringsdokumentation. Et arbejdsredskab der hjælper CISO, compliance- og beredskabsfunktioner i energivirksomheder med hurtigt at forstå regulatoriske krav, pligter ved hændelser og forventninger fra CFCS og Energistyrelsen. Alle svar er udgangspunkt — endelig vurdering kræver inddragelse af jurist og CFCS/Energistyrelsens aktuelle vejledninger.
