# Zettel — [[Segmentación de Red]]

- Date:: 2025-09-29
- Tags:: #zettel #concepto #redes #seguridad #arquitectura

## Idea principal
La segmentación de red es la práctica de dividir una red informática en subredes más pequeñas y aisladas (segmentos).

## Detalles
El objetivo principal de la segmentación es mejorar la seguridad y el rendimiento.

- **Seguridad:** Si un atacante compromete un segmento de la red, la segmentación ayuda a contenerlo y evita que se mueva lateralmente con facilidad a otros segmentos. Permite aplicar políticas de seguridad más granulares entre segmentos.
- **Rendimiento:** Reduce la congestión al aislar el tráfico dentro del segmento donde se origina, en lugar de difundirlo por toda la red.

Tecnologías comunes para implementar la segmentación:
- **Subnetting:** División lógica de una red IP.
- **[[VLAN (Virtual Local Area Network)|VLANs]]:** Creación de redes lógicas independientes en la misma infraestructura física.
- **[[Firewall|Firewalls]] y Listas de Control de Acceso (ACLs):** Para controlar el tráfico que puede pasar entre segmentos.

## Enlaces
- [[Diseño de Redes Seguras]]
- [[VLAN (Virtual Local Area Network)]]
- [[Subnetting]]
- [[Movimiento Lateral]]