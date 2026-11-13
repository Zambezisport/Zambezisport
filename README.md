# Zambezisport

**English** | [Português](README.pt.md)

🌍 **Environmental health for outdoor sport — train hard, read the conditions.**

Heat stress, air quality and UV decide whether a session builds an athlete or
breaks one. Zambezisport turns environmental data into clear go / modify / cancel
guidance for outdoor training and events — built for the conditions of southern
Africa, useful anywhere the weather wins.

- 🌐 **Website** → [zambezisport.com](https://zambezisport.com)

## Open source

Small dependency-free TypeScript utilities in
[**zambezisport-utils**](https://github.com/Zambezisport/zambezisport-utils):

| file | what it is |
|---|---|
| [`wbgt.ts`](https://github.com/Zambezisport/zambezisport-utils/blob/main/wbgt.ts) | Wet-bulb globe temperature estimate + activity risk bands |
| [`aqi.ts`](https://github.com/Zambezisport/zambezisport-utils/blob/main/aqi.ts) | EPA air-quality index from PM2.5 / PM10, with exercise guidance |
| [`uv.ts`](https://github.com/Zambezisport/zambezisport-utils/blob/main/uv.ts) | WHO UV-index bands and protection windows |
| [`hydration.ts`](https://github.com/Zambezisport/zambezisport-utils/blob/main/hydration.ts) | Sweat-rate, fluid and sodium targets for a session |
| [`session.ts`](https://github.com/Zambezisport/zambezisport-utils/blob/main/session.ts) | Composite go / caution / modify / cancel verdict for outdoor sessions |

Estimates are planning aids, not medical advice. MIT licensed.
