# Zettel — [[Ataque Man-in-the-Middle (MITM)]]

- Date:: 2025-09-29
- Tags:: #zettel #ataque #redes #seguridad

## Idea principal
Un ataque Man-in-the-Middle (o "ataque de intermediario") ocurre cuando un atacante se interpone secretamente en la comunicación entre dos partes, que creen que se están comunicando directamente entre sí.

## Detalles
El atacante establece conexiones independientes con las víctimas y retransmite los mensajes entre ellas, haciéndoles creer que están hablando directamente. Esto le permite interceptar, leer, y potencialmente modificar todo el tráfico.

Ejemplos de técnicas para lograr la posición de intermediario:
- **ARP Spoofing:** En redes locales, el atacante engaña a las víctimas para que le envíen el tráfico a él en lugar de al router o al destino real.
- **DNS Spoofing / Cache Poisoning:** El atacante corrompe la resolución de nombres para redirigir a la víctima a un servidor malicioso que él controla.
- **Creación de Puntos de Acceso Wi-Fi Falsos (Evil Twin).**

El [[Cifrado en Tránsito]] (usando [[TLS (Transport Layer Security)]] o [[IPsec (Internet Protocol Security)]]) es la principal defensa contra los ataques MITM, ya que aunque el atacante intercepte el tráfico, no podrá leerlo ni modificarlo sin romper el cifrado.

## Enlaces
- [[Cifrado en Tránsito]]
- [[ARP Spoofing]]
- [[DNS Spoofing]]