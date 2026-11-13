# Zambezisport

**English** | [Português](README.pt.md)

🏜️🌊 **Motorsport for nature — on the desert stage and the open water.**

On a rally-raid stage or an offshore leg, the environment is a competitor:
cockpit heat that cooks drivers through sealed gear, dust that starves engines
and blinds riders, seas that decide whether a boat races or stays in harbour,
UV that punishes every exposed minute. Zambezisport carries nature and
environmental initiatives where motorsport audiences actually look — and turns
environmental data into clear run / shorten / cancel guidance for desert
stages and ocean events.

The environment isn't the backdrop. It's the judge.

- 🌐 **Website** → [zambezisport.com](https://zambezisport.com)

## Open source

Ocean field-work and water-sport utilities in
[**zambezisport-ocean**](https://github.com/Zambezisport/zambezisport-ocean):

| file | what it is |
|---|---|
| [`degree-heating.ts`](https://github.com/Zambezisport/zambezisport-ocean/blob/main/degree-heating.ts) | Coral-bleaching thermal stress (Degree Heating Weeks) |
| [`wave-spectrum.ts`](https://github.com/Zambezisport/zambezisport-ocean/blob/main/wave-spectrum.ts) | Wave spectrum → sea state and survey-boat workability |
| [`tides.ts`](https://github.com/Zambezisport/zambezisport-ocean/blob/main/tides.ts) | Harmonic tide prediction for field-work windows |
| [`drift.ts`](https://github.com/Zambezisport/zambezisport-ocean/blob/main/drift.ts) | Surface drift / leeway trajectories for floating objects |

Desert-stage condition utilities in
[**zambezisport-utils**](https://github.com/Zambezisport/zambezisport-utils):

| file | what it is |
|---|---|
| [`wbgt.ts`](https://github.com/Zambezisport/zambezisport-utils/blob/main/wbgt.ts) | Heat stress for drivers & riders — WBGT adjusted for racing gear / sealed cockpit |
| [`aqi.ts`](https://github.com/Zambezisport/zambezisport-utils/blob/main/aqi.ts) | Dust & air quality — AQI from PM2.5/PM10 with stage guidance |
| [`uv.ts`](https://github.com/Zambezisport/zambezisport-utils/blob/main/uv.ts) | WHO UV bands and peak-window advice for open-desert stages |
| [`hydration.ts`](https://github.com/Zambezisport/zambezisport-utils/blob/main/hydration.ts) | Fluid & sodium planning for stints and stages in heat |
| [`session.ts`](https://github.com/Zambezisport/zambezisport-utils/blob/main/session.ts) | Composite run / caution / shorten / cancel verdict per stage |

Estimates are planning aids — final calls belong to race control and medical
staff. MIT licensed.
