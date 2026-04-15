# NC RfG — Kommissionens forordning (EU) 2016/631

Network Code on Requirements for Generators. Fastlægger tekniske krav til nettilslutning af produktionsanlæg i EU.

## Type A-D klassifikation (art. 5)

| Type | Effekt | Spænding | Kerne-krav |
|------|--------|----------|------------|
| A | 0,8 kW - 1,5 MW | Alle | Frekvens-P, P/U, FSM på tilslutningspunktet |
| B | 1,5 - 50 MW | Alle | + FRT, styring, fjernbetjening, udfaldssignal |
| C | 50 - 75 MW | Alle | + reguleringsreserver, LFSM-O og LFSM-U |
| D | ≥ 75 MW ELLER ≥ 110 kV | Transmission | + black-start-beredskab, syntetisk inerti, fuld modelvalidering |

## LFSM — Limited Frequency Sensitive Mode

- **LFSM-O** (over-frequency) — obligatorisk aktivering ved frekvens > **50,2 Hz** (CE) / 50,1 Hz (Nordic). Reducerer P lineært med frekvens.
- **LFSM-U** (under-frequency) — obligatorisk ved frekvens < **49,8 Hz**. Opregulerer P. Kun krav for Type C og D.
- **FSM** — Frequency Sensitive Mode (normal drift inden for dødbånd)

## Fault Ride Through (FRT)

Krav om at anlægget forbliver tilsluttet under netfejl med lav spænding:

- **Type B+:** skal modstå 0% U i op til 150 ms efter trefasefejl
- **Type D:** udvidede krav med forskellige U-profiler
- Implementeret via TF 3.2.5 (vind), TF 3.2.3 (sol), TF 3.2.1 (batteri)

## Proces for nettilslutning (art. 29-33)

1. Tilslutningsforespørgsel
2. EON — Energy Operator Notification
3. ION — Interim Operational Notification (midlertidig drift til test)
4. FON — Final Operational Notification (endelig driftstilladelse)
5. LON — Limited Operational Notification (ved kendte afvigelser)

## Dansk implementering

Tekniske Forskrifter (TF) under Netreglerne:

- **TF 3.2.1** Batterianlæg
- **TF 3.2.2** Termiske anlæg > 11 kW
- **TF 3.2.3** Solcelleanlæg
- **TF 3.2.5** Vindkraftanlæg > 11 kW
- **TF 3.2.6** HVDC-forbindelser (supplerer NC HVDC)

## Auto-klassifikation

Givet brugerens anlægsstørrelse i MW:

```
hvis P >= 75 MW eller U >= 110 kV: Type D
hvis 50 <= P < 75 MW: Type C
hvis 1,5 <= P < 50 MW: Type B
hvis 0,0008 <= P < 1,5 MW: Type A
```
