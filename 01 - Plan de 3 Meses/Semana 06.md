# Post-Explotación y Movimiento Lateral

## Objetivo de la Semana
Practicar escalada de privilegios, pivoting y persistencia en entornos comprometidos (laboratorio controlado).

## Módulos/Temas a Cubrir (U.T.)
- Escalada de privilegios Windows y Linux.
- Pivoting / Tunneling (ProxyChains, SSH -D).
- Pass-the-Hash, Pass-the-Ticket, Mimikatz (en laboratorio controlado).
- Persistencia y limpieza (para entender defensa).

## Contenido

### Conceptos a aprender
- Binarios SUID, exploitation local en Linux.
- Técnicas de Pass-the-Hash y mitigaciones.
- Herramientas de pivoting y su impacto en defensa.

### Actividades Prácticas
- [ ] Identificar y explotar SUID mal configurados en VM Linux de laboratorio.
- [ ] Usar `ssh -D` para crear un SOCKS proxy y enrutar tráfico.
- [ ] Simular extracción de hashes (en entorno controlado) y reutilizarlos para acceso lateral.
- [ ] Documentar pasos de post-explotación en un informe breve.

### Contenido Recomendado (solo títulos)
- *The Hacker Playbook 2*.
- MITRE ATT&CK: movilidad lateral y persistencia.

## Autoevaluación Asistida
- Enumera 3 mitos sobre escalada de privilegios.
- Diferencia técnica entre Pass-the-Hash y Pass-the-Ticket.
- Escenario: consiguió acceso de usuario en una máquina; describe pasos para moverse lateralmente y cómo defenderlo.
