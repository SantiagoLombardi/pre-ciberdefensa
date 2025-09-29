# Zettel — [[TLS (Transport Layer Security)]]

- Date:: 2025-09-29
- Tags:: #zettel #protocolo #redes #criptografia #seguridad

## Idea principal
TLS es el protocolo criptográfico más extendido para proporcionar comunicaciones seguras a través de una red. Es el sucesor de SSL (Secure Sockets Layer).

## Detalles
TLS opera en la capa de transporte y se utiliza para asegurar el tráfico de aplicaciones de capa superior, principalmente el tráfico web (HTTPS). Proporciona tres servicios de seguridad:

1.  **Confidencialidad:** A través del [[Cifrado en Tránsito]] de los datos.
2.  **Integridad:** Mediante códigos de autenticación de mensajes (MACs) para detectar alteraciones.
3.  **Autenticación:** Utiliza certificados digitales X.509 (parte de una PKI) para verificar la identidad del servidor (y opcionalmente del cliente).

El proceso de establecimiento de una conexión segura se conoce como "TLS Handshake".

## Enlaces
- [[Cifrado en Tránsito]]
- [[HTTPS]]
- [[Certificado Digital]]
- [[PKI (Public Key Infrastructure)]]