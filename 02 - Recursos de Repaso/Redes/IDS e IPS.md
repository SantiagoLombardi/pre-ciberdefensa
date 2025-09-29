# Zettel — [[IDS e IPS]]

- Date:: 2025-09-29
- Tags:: #zettel #tecnologia #redes #seguridad #monitoreo

## Idea principal
Los Sistemas de Detección de Intrusiones (IDS) y los Sistemas de Prevención de Intrusiones (IPS) son tecnologías que monitorean una red o un sistema en busca de actividad maliciosa o violaciones de políticas.

## Detalles
La principal diferencia entre ellos es su modo de operación:

- **IDS (Sistema de Detección de Intrusiones):** Es un sistema pasivo. Monitorea el tráfico, y si detecta una amenaza, genera una alerta para que un analista la investigue. No bloquea el tráfico por sí mismo.

- **IPS (Sistema de Prevención de Intrusiones):** Es un sistema activo o "en línea". Se sitúa en el camino del tráfico y puede bloquear o prevenir activamente las amenazas que detecta, además de generar una alerta.

Ambos pueden usar dos métodos de detección principales:
1.  **Detección Basada en Firmas:** Busca patrones que coincidan con firmas de ataques conocidos (similar a un antivirus).
2.  **Detección Basada en Anomalías:** Busca desviaciones del comportamiento normal de la red (ver [[Detección de Anomalías]]).

## Enlaces
- [[Diseño de Redes Seguras]]
- [[Detección de Anomalías]]
- [[Firewall]]