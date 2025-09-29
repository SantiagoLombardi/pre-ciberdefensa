# Zettel — [[ARP]]

- Date:: 2025-09-29
- Tags:: #zettel #concepto #redes #capa2

## Idea principal
ARP (Address Resolution Protocol) es un protocolo de comunicación utilizado para descubrir la dirección de la capa de enlace (dirección MAC) asociada con una dirección de la capa de internet (dirección IP) determinada.

## Detalles
Cuando un host necesita enviar un paquete a otro host en la misma red local, conoce la dirección IP de destino, pero no la dirección MAC. ARP envía una solicitud de difusión (ARP request) preguntando "¿quién tiene esta IP?". El host con esa IP responde con su dirección MAC (ARP reply). Este mapeo se almacena en la caché ARP del host solicitante.

## Enlaces
- [[Modelo OSI]]
- [[Direccionamiento IP]]
