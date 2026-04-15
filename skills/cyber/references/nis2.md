# NIS2 — Direktiv (EU) 2022/2555

Revideret netværks- og informationssikkerhedsdirektiv. Trådt i kraft 16. januar 2023, implementeringsfrist 17. oktober 2024. Ophævede NIS1 (2016/1148).

## Omfang

Bilag 1 ("højt kritiske sektorer") inkluderer **energi**: elektricitet, fjernvarme, olie, gas, brint. Derudover drikkevand, transport, sundhed, digital infrastruktur, IT-tjenester, offentlig administration, rumfart.

Bilag 2 ("andre kritiske sektorer") inkluderer postvæsen, affald, kemiindustri, fødevarer, fremstilling, digitale tjenesteudbydere, forskning.

## Enhedstyper

- **Væsentlig enhed** (essential) — store enheder i højt kritiske sektorer. Proaktivt tilsyn.
- **Vigtig enhed** (important) — mellemstore enheder i højt kritiske sektorer + store/mellemstore i andre kritiske sektorer. Reaktivt tilsyn.

Tærskler efter Kommissionens anbefaling 2003/361/EF: store = ≥250 ansatte eller ≥50 mio. EUR omsætning; mellemstore = ≥50 ansatte eller ≥10 mio. EUR.

## Centrale forpligtelser

- **Art. 20** — Ledelsesorganer godkender risikostyringsforanstaltninger, overvåger implementering, deltager i træning. **Personligt ansvar** for ledelsen.
- **Art. 21** — Tekniske, operationelle og organisatoriske foranstaltninger (10-punkts-listen: politikker, hændelseshåndtering, kontinuitet, supply chain, kryptografi, adgangskontrol, MFA, cyberhygiejne, mv.).
- **Art. 23** — Hændelsesrapportering til CSIRT: **tidlig varsling 24 t**, **hændelsesrapport 72 t**, **statusrapport på anmodning**, **afsluttende rapport 1 måned**.
- **Art. 24-25** — Certificering (frivillig eller pålagt af Kommissionen).
- **Art. 32-37** — Tilsyn, tvangsforanstaltninger, sanktioner.

## Sanktioner (art. 34)

- Væsentlig enhed: op til **10 mio. EUR eller 2% af årlig global omsætning** (det højeste).
- Vigtig enhed: op til **7 mio. EUR eller 1,4% af årlig global omsætning**.
- Suspension af certificering og midlertidig diskvalifikation af ledelsespersoner mulig.

## Dansk implementering

Implementeret via Lov om foranstaltninger til sikring af et højt cybersikkerhedsniveau (NIS2-loven). Center for Cybersikkerhed (CFCS) er national myndighed for højt kritiske sektorer. Sektorspecifikke myndigheder (Energistyrelsen for energi) udøver sektortilsyn efter delegation.

## Interaktion med andre rammer

- **CER** (2022/2557) — fysisk resiliens (vedtaget samme dag som NIS2). Væsentlige enheder efter NIS2 er typisk også kritiske enheder efter CER.
- **DORA** (2022/2554) — finansielle enheder undtaget fra NIS2, dækket af DORA.
- **NCCS** (2024/1366) — Network Code on Cybersecurity for el-sektoren er lex specialis for TSO/DSO/producenter i el og supplerer NIS2 med sektorspecifikke krav.
- **GDPR** (2016/679) — hændelser med personoplysninger udløser også GDPR-notifikation (72 t til Datatilsynet).

## Hyppige misforståelser

- "Vi er et lille selskab, så NIS2 gælder ikke" — undtagelser har nuancer; energi har særlige tærskler uanset størrelse for visse aktiviteter.
- "NIS2 er kun IT" — dækker også OT/ICS når informationssystemer kontrollerer kritiske processer.
- "Leverandører er vores ansvar når de er NIS2-omfattede" — art. 21(2)(d) kræver at enheden selv vurderer supply chain, ikke blot stoler på leverandørens egen status.
