# Reconocimiento (Recon)

## Objetivo de la Semana
Dominar técnicas de reconocimiento pasivo y activo; usar [[Nmap]] y fuentes OSINT avanzadas para recopilar información.

## Módulos/Temas a Cubrir (U.T.)
- Recon pasivo vs activo; OSINT avanzado.
- Escaneo con [[Nmap]] (sS, sU, sV, -O).
- Shodan, WHOIS, DNS enumeration.
- Bases de datos y documentación de hallazgos.

## Contenido

### Conceptos a aprender
- Diferencias entre recon pasivo y activo; límites legales/éticos.
- Uso avanzado de Nmap: scripts NSE, timing, evasión.
- Interpretación de resultados y priorización de objetivos.

### Actividades Prácticas
- [ ] Ejecutar `nmap -sS -sV -O target` en una máquina de laboratorio y documentar hallazgos.
- [ ] Usar WHOIS y `dig` para mapear un dominio controlado.
- [ ] Hacer un mapa OSINT de una entidad ficticia (emails, subdominios, empleados).
- [ ] **Opcional:** Registrarte en Shodan y buscar servicios expuestos por tipo.

### Contenido Recomendado (solo títulos)
- TryHackMe: *Nmap* room.
- *Metasploit: The Penetration Tester’s Guide* (lectura referencial).
- MITRE ATT&CK — tácticas de reconocimiento.

## Autoevaluación Asistida
- ¿Qué información aporta un NSE script de Nmap?
- Interpretar una salida: puerto 22/tcp open ssh; servicio: OpenSSH 7.2p2 — ¿riesgos?
- Escenario: identificas un servidor con versión de PHP vieja; ¿qué priorizas y por qué?
