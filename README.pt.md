# Zambezisport

[English](README.md) | **Português**

🏜️ **Saúde ambiental para o motociclismo e ralis no deserto — lê a etapa antes de a correr.**

Nas condições de um rali-raide, o ambiente é um adversário: calor no cockpit que
cozinha pilotos dentro de equipamento selado, poeira que sufoca motores e cega
motociclistas, UV que castiga cada minuto exposto. A Zambezisport transforma
dados ambientais em orientação clara de correr / encurtar / cancelar para
etapas e eventos no deserto — construída para as condições da África Austral,
relevante onde quer que o deserto mande.

- 🌐 **Site** → [zambezisport.com](https://zambezisport.com)

## Código aberto

Utilitários de conservação dos oceanos em
[**zambezisport-ocean**](https://github.com/Zambezisport/zambezisport-ocean):

| ficheiro | o que é |
|---|---|
| [`degree-heating.ts`](https://github.com/Zambezisport/zambezisport-ocean/blob/main/degree-heating.ts) | Stress térmico de branqueamento de corais (Degree Heating Weeks) |
| [`wave-spectrum.ts`](https://github.com/Zambezisport/zambezisport-ocean/blob/main/wave-spectrum.ts) | Espectro de ondas → estado do mar e operacionalidade |
| [`tides.ts`](https://github.com/Zambezisport/zambezisport-ocean/blob/main/tides.ts) | Previsão harmónica de marés para trabalho de campo |
| [`drift.ts`](https://github.com/Zambezisport/zambezisport-ocean/blob/main/drift.ts) | Trajetórias de deriva de objetos flutuantes |

Utilitários de condições de etapa no deserto em
[**zambezisport-utils**](https://github.com/Zambezisport/zambezisport-utils):

| ficheiro | o que é |
|---|---|
| [`wbgt.ts`](https://github.com/Zambezisport/zambezisport-utils/blob/main/wbgt.ts) | Stress térmico para pilotos — WBGT ajustado ao fato de corrida / cockpit selado |
| [`aqi.ts`](https://github.com/Zambezisport/zambezisport-utils/blob/main/aqi.ts) | Poeira e qualidade do ar — AQI de PM2.5/PM10 com orientação por etapa |
| [`uv.ts`](https://github.com/Zambezisport/zambezisport-utils/blob/main/uv.ts) | Bandas UV da OMS e conselhos de horário para etapas em deserto aberto |
| [`hydration.ts`](https://github.com/Zambezisport/zambezisport-utils/blob/main/hydration.ts) | Planeamento de fluidos e sódio para stints e etapas no calor |
| [`session.ts`](https://github.com/Zambezisport/zambezisport-utils/blob/main/session.ts) | Veredicto composto correr / cautela / encurtar / cancelar por etapa |

Estimativas de planeamento — a decisão final cabe à direção de prova e à equipa
médica. Licença MIT.
