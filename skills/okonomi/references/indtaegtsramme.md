# Indtægtsrammen for netselskaber

Den økonomiske regulering af danske el- og gasnetselskaber. Hjemmel: **Elforsyningsloven §§ 69-70b** (LBK 1193/2023) og Forsyningstilsynets indtægtsrammebekendtgørelse (aktuelt BEK 1462/2022 for el). Gasdistribution reguleres via tilsvarende bekendtgørelse under Lov om gasforsyning.

## Grundprincip

Netselskaber er naturlige monopoler og må ikke opkræve mere end en fastsat indtægtsramme. Rammen består af:

```
Indtægtsramme = OPEX + Afskrivning + Forrentning(WACC × RAB) − Effektiviseringskrav
```

Hvor:
- **OPEX** = driftsomkostninger (godkendt historisk niveau justeret for inflation og effektivisering)
- **Afskrivning** = regulatoriske afskrivninger på RAB
- **RAB** (Regulatory Asset Base) = den regulatoriske kapitalbase
- **WACC** = vægtet kapitalomkostning fastsat af Forsyningstilsynet
- **Effektiviseringskrav** = generelt + selskabsspecifikt (fra benchmarking)

## Reguleringsperiode

El: 5-årige perioder. Nuværende periode 2024-2028 (forudgående 2018-2023). Gas: 4-årige perioder.

Ved periodestart fastsættes:
- WACC
- Generelt effektiviseringskrav
- Selskabsspecifik benchmarking-effektivisering
- Kapacitetsmekanismer

## WACC-fastsættelse

Forsyningstilsynet fastsætter WACC før periodens start. Metode (FST's WACC-afgørelse for reguleringsperioden):

```
WACC_før_skat = (E/V × Re + D/V × Rd × (1-t)) / (1-t)
```

- **Risikofri rente** — typisk gennemsnit af 10-årig dansk statsobligation.
- **Beta** — asset beta branche + re-gearing til selskabets kapitalstruktur.
- **Markedsrisikopræmie (MRP)** — fastsættes af FST, typisk i intervallet 4-6%.
- **Fremmedkapitalpræmie** — kreditmargin baseret på benchmark-udstedelser.
- **Kapitalstruktur** — notionel E/D-fordeling (typisk 40/60 til 50/50).

Faktisk WACC-niveau: verificér mod Forsyningstilsynets seneste afgørelse. Satser varierer pr. reguleringsperiode og er tidsfølsomme.

## Benchmarking

Forsyningstilsynet anvender DEA (Data Envelopment Analysis) til at sammenligne selskabers effektivitet. Inputs: OPEX, CAPEX-annuitet. Outputs: netlængde, antal kunder, leveret energi, topografiske faktorer.

Resultat: hvert selskab får et individuelt effektiviseringskrav afhængigt af afstand til effektiv front.

## Kompensation for investeringer (CAPEX-tillæg)

- Nye anlæg indgår i RAB og forrentes via WACC.
- Ekstraordinære investeringer (grøn omstilling, cyberresiliens) kan udløse særlig godkendelse.
- I grøn omstilling har Forsyningstilsynet indført særlige metoder for investeringer i bl.a. havvind-nettilslutning og brintforberedelse.

## Tilsyn og klage

- Forsyningstilsynet fastsætter indtægtsrammer, godkender metoder, fører løbende tilsyn.
- Klage over FST-afgørelser til **Energiklagenævnet**.
- Domstolsprøvelse mulig herefter.

## Hyppige misforståelser

- "Indtægtsrammen er en pris-ramme" — nej; det er en **beløbs-ramme**. Tariffen (pris) fastsættes af selskabet og skal summen give indtægt ≤ rammen.
- "Ubrugt ramme kan overføres" — kun delvist. Regulerings-over/underdækning balanceres over en årrække, ikke fuldt fleksibelt.
- "WACC er fast for hele perioden" — grundlæggende ja, men der findes "åbningsklausuler" ved markante renteændringer eller særlige forhold.

## Næste skridt for compliance-analyse

1. Identificér selskabets reguleringsperiode og gældende WACC/effektiviseringskrav.
2. Tjek Forsyningstilsynets seneste indtægtsrammeafgørelse for selskabet.
3. Forstå forholdet mellem indtægtsramme og faktisk fakturering (over/underdækning).
4. Ved investeringsspørgsmål: tjek om der er særlig metode for den type CAPEX.
