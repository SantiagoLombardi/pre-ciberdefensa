# Zettel — [[Cifrado en Tránsito]]

- Date:: 2025-09-29
- Tags:: #zettel #concepto #seguridad #redes #criptografia

## Idea principal
El cifrado en tránsito (o in-transit) es el proceso de cifrar los datos antes de que se envíen a través de una red y descifrarlos en el destino. 

## Detalles
Su objetivo principal es proteger la confidencialidad e integridad de los datos mientras viajan por redes que no son de confianza, como Internet. Impide que un adversario que intercepte el tráfico (ver [[Ataque Man-in-the-Middle (MITM)]]) pueda leer o modificar la información.

Se complementa con el "cifrado en reposo" (at-rest), que protege los datos cuando están almacenados en un disco o base de datos.

Protocolos comunes que implementan cifrado en tránsito:
- [[TLS (Transport Layer Security)]]
- [[IPsec (Internet Protocol Security)]]
- [[SSH (Secure Shell)]]
- [[VPN (Virtual Private Network)]]

## Enlaces
- [[Ataque Man-in-the-Middle (MITM)]]
- [[Confidencialidad]]
- [[Integridad]]