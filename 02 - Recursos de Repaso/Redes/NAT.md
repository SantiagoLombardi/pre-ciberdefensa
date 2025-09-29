# Zettel — [[NAT]]

- Date:: 2025-09-29
- Tags:: #zettel #concepto #redes #seguridad

## Idea principal
NAT (Network Address Translation) es un método utilizado por routers para reescribir la dirección IP de origen de los paquetes que lo cruzan, permitiendo que múltiples dispositivos en una red privada compartan una única dirección IP pública.

## Detalles
Funciona mapeando direcciones IP privadas (como 192.168.x.x) a una dirección IP pública. Esto conserva el limitado espacio de direcciones IPv4 y añade una capa de seguridad al ocultar la estructura de la red interna. Las variantes comunes son NAT estático, NAT dinámico y PAT (Port Address Translation), que también utiliza puertos para diferenciar las conexiones.

## Enlaces
- [[Direccionamiento IP]]
- [[Subnetting]]
- [[Firewall]]