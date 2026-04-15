# CfD og PPA — Kommercielle strukturer for VE-finansiering

## Contract for Difference (CfD)

**Princip:** modparten (stat eller uafhængig offtaker) udbetaler differencen mellem aftalt strike-pris og markedspris (typisk spotpris). Tosidet CfD: producent udbetaler hvis markedspris overstiger strike.

### Dansk statslig CfD

**Hjemmel:** VE-loven (LBK 1791/2023) og særskilte udbudsbekendtgørelser for hvert udbud.

**Afholdte/aktuelle udbud (indikativ liste — verificér mod Energistyrelsens hjemmeside):**

- **Thor Havvind** — afgjort 2021. Tildelt til RWE. 1 GW. Ingen eller minimal statsstøtte; concession-struktur.
- **Nordsøen I** — to-siddet CfD udbudt. Strike-pris konkurrencedygtig.
- **Energiøer** — Nordsøen Energiø og Bornholm Energiø. Strukturen ændret gennem 2024-2025.
- **Solceller/landvind** — åbne dør-udbud (pauset) og teknologineutrale udbud.

### EU-regulering efter elmarkedsreformen 2024

Europa-Parlamentets og Rådets **Forordning 2024/1747** (elmarkedsreformen) forpligter medlemsstater til at anvende tosidede CfD eller tilsvarende mekanismer for langsigtede statsstøttede VE-investeringer. Revisionen trådte i kraft juli 2024.

## Power Purchase Agreement (PPA)

**Typer:**

- **Fysisk PPA** — konsekvent fysisk levering fra anlæg til aftager. Bankable hvis anlægget er forpligtet til at levere og prisen er fast/kollaret.
- **Finansiel PPA / Virtual PPA (vPPA)** — ingen fysisk levering; rent finansielt swap mellem flydende spotpris og fast pris.
- **Corporate PPA (CPPA)** — direkte mellem producent og erhvervsaftager (fx Google, Novo Nordisk).

**Bankability-kriterier:**

- Modpartens kreditværdighed (investment grade foretrukket).
- PPA-varighed typisk 10-15 år for projektfinansiering.
- Volumenfleksibilitet (take-or-pay eller as-generated).
- GO-overdragelse (grønne oprindelsescertifikater).
- Curtailment-risikoallokering.
- Prisformel (fast, indekseret, kollaret).

### CPPA og RFNBO-kvalifikation

PPA'er der skal kvalificere el som VE til brintproduktion (RFNBO) skal opfylde:
- Additionalitet: nyt VE-anlæg ≤36 måneder fra elektrolysator-start.
- Geografisk korrelation: samme budzone.
- Tidsmæssig korrelation: månedlig til 2030, time-for-time fra 2030.

Se `../../gas/references/rfnbo.md` for detaljer.

## Statsstøtte-aspekt

- CfD med offentlig modpart = statsstøtte efter TEUF art. 107(1) → kræver notifikation eller GBER-undtagelse.
- CEEAG (Climate, Environmental and Energy Aid Guidelines — 2022/C 80/01): ramme for godkendelse.
- Udbuddet skal være ikke-diskriminerende, konkurrenceåbent, kvantificeret i forhold til behov.
- Kumulationsregler med andre ordninger (GBER, IPCEI).

## Forholdet til indtægtsramme/tariffering

CfD og PPA er **kommercielle aftaler** — adskilt fra den regulerede indtægtsramme for netselskaber. TSO/DSO-tariffer betales af producenten uanset CfD/PPA-struktur (undtagelser kan gælde for visse systembidrag).

## Hyppige misforståelser

- "PPA = køberet" — nej; PPA er en frivillig aftale. Køberet er lov-påkrævet tilbud til lokalbefolkning ved VE-projekter (VE-loven § 13).
- "CfD = tilskud" — delvist. Tosidede CfD kan give nettoudbetaling til staten når spotpris > strike.
- "Strike-pris er altid fast i kroner" — kan være indekseret (inflation, råstof) afhængigt af udbudsvilkår.

## Næste skridt

1. Identificér om aftalen har offentlig modpart (statsstøtte-analyse nødvendig) eller er CPPA.
2. Ved offentlig CfD: tjek seneste udbudsbekendtgørelse og tildelingsbeslutning.
3. Ved CPPA: bankability-tjek, RFNBO-kvalificeringsanalyse hvis relevant, GO-håndtering.
4. Husk tarifomkostninger og balanceansvar i projektøkonomi.
