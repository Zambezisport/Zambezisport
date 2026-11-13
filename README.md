# Zambezisport

**English** | [Português](README.pt.md)

🏜️ **Environmental health for desert motorsport — read the stage before you race it.**

In rally-raid conditions, the environment is a competitor: cockpit heat that
cooks drivers through sealed gear, dust that starves engines and blinds riders,
UV that punishes every exposed minute. Zambezisport turns environmental data
into clear run / shorten / cancel guidance for desert stages and events —
built for the conditions of southern Africa, relevant anywhere the desert wins.

- 🌐 **Website** → [zambezisport.com](https://zambezisport.com)

## Open source

Small dependency-free TypeScript utilities in
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
