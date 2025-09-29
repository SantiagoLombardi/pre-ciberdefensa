# Ataques de Red y Detección

## Objetivo de la Semana
Practicar ataques de red básicos (ARP spoofing, sniffing) y conocer herramientas de detección como Snort/Suricata; comprender hashing y manejo de contraseñas.

## Módulos/Temas a Cubrir (U.T.)
- ARP spoofing / MITM y contramedidas.
- IDS/IPS: Snort, Suricata.
- Hashing y salting; cracking de contraseñas.

## Contenido

### Conceptos a aprender
- ARP spoofing y mitigaciones (ARP inspection, static ARP).
- Diferencia IDS vs IPS.
- Tipos de hash (MD5/SHA) y necesidad de salt.

### Actividades Prácticas
- [ ] Configurar Cowrie honeypot o un servicio SSH simulado.
- [ ] Ejecutar ARP poisoning (ambiente controlado) con Ettercap y observar en Wireshark.
- [ ] Instalar Snort, crear regla simple y dispararla con tráfico de prueba.
- [ ] Usar John the Ripper en hashes almacenados de prueba.
- [ ] **Opcional:** Implementar un honeypot y analizar logs entrantes.

### Contenido Recomendado (solo títulos)
- TryHackMe: *Blue Team Fundamentals*.
- NIST SP 800-61 (Respuesta a incidentes).

## Autoevaluación Asistida
- ¿Qué indica un spike en conexiones SYN en un log de firewall?
- Explica por qué el salt hace más difícil un ataque de rainbow tables.
- Escenario: detectas tráfico ARP anómalo; ¿acciones inmediatas?
