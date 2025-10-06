# Zettel — [[IPsec (Internet Protocol Security)]]

- Date:: 2025-09-29
- Tags:: #zettel #protocolo #redes #criptografia #seguridad

## Idea principal
IPsec es un conjunto de protocolos que se utiliza para asegurar las comunicaciones a nivel de la capa de red (Capa 3 del modelo OSI). Puede proteger todo el tráfico IP entre dos puntos.

## Detalles
IPsec es más flexible pero también más complejo que [[TLS (Transport Layer Security)]]. Se utiliza comúnmente para implementar [[VPN (Virtual Private Network)]]s.

Opera en dos modos:
- **Modo Transporte:** Cifra solo el payload (los datos) del paquete IP, dejando la cabecera original intacta. Se usa para comunicaciones host-a-host.
- **Modo Túnel:** Cifra y encapsula el paquete IP original completo dentro de un nuevo paquete IP. Se usa para comunicaciones red-a-red (gateways de VPN).

Componentes principales de IPsec:
- **AH (Authentication Header):** Proporciona integridad y autenticación, pero no confidencialidad.
- **ESP (Encapsulating Security Payload):** Proporciona confidencialidad (cifrado) y opcionalmente integridad y autenticación.

## Enlaces
- [[Cifrado en Tránsito]]
- [[VPN|VPN (Virtual Private Network)]]
- [[Capa de Red]]