# Zettel — [[Diseño de Redes Seguras]]

- Date:: 2025-09-29
- Tags:: #zettel #concepto #redes #seguridad #arquitectura

## Idea principal
El diseño de redes seguras es la práctica de planificar y construir una infraestructura de red aplicando principios de seguridad desde el principio (Security by Design) para proteger la confidencialidad, integridad y disponibilidad de los datos.

## Detalles
En lugar de añadir la seguridad como un añadido posterior, se integra en cada capa de la arquitectura de red. Se basa en el principio de **Defensa en Profundidad**, que consiste en superponer múltiples capas de controles de seguridad.

Componentes y principios clave:
- **[[Segmentación de Red]]:** Dividir la red en zonas más pequeñas y aisladas para contener los ataques.
- **[[Firewall|Firewalls]]:** Controlar el tráfico que fluye entre los segmentos de la red.
- **[[IDS e IPS]]:** Monitorear el tráfico en busca de actividad maliciosa.
- **Principio de Mínimo Privilegio:** Otorgar solo el nivel de acceso estrictamente necesario para que un dispositivo o usuario funcione.
- **Zonas Desmilitarizadas (DMZ):** Subredes aisladas para alojar servicios expuestos a internet (como servidores web).

## Enlaces
- [[Defensa en Profundidad]]
- [[Segmentación de Red]]
- [[Firewall]]
- [[IDS e IPS]]
- [[DMZ]]