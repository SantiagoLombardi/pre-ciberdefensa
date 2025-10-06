# Fundamentos y Laboratorio Inicial

## Objetivo de la Semana
Establecer ambiente de laboratorio, comprender triada CIA, introducir redes básicas y OSINT.

## Módulos/Temas a Cubrir (U.T.)
- Triada CIA y principios de seguridad.
- Modelo OSI / TCP-IP y direcciones IP.
- Fundamentos de Linux/Windows.
- Introducción a [[Wireshark]] y OSINT.

## Contenido

### Conceptos a aprender
- [[Triada CIA|Triada CIA]]: Confidencialidad, Integridad, Disponibilidad.
- Modelo OSI y mapeo a protocolos TCP/IP.
- IPs, subredes básicas, DNS.
- Comandos básicos: [[comando - ip| ip]], `ifconfig`, `netstat`, `ping`, `traceroute`.
- Conceptos básicos de OSINT y ética al recolectar información.

### Actividades Prácticas
- [x] Montar VM: Kali + Ubuntu + Windows en VirtualBox/VMWare.
- [x] Crear snapshot inicial de cada VM.
- [x] Ejecutar `ifconfig`/`ip a` y describir la salida.
- [x] Capturar tráfico en la red LAN con [[Wireshark]] (navegar una web y observar DNS/HTTP).
- [x] Realizar una búsqueda OSINT básica sobre una entidad ficticia (usar WHOIS, búsquedas avanzadas).
- [x] **Opcional (más horas):** Completar TryHackMe *Pre Security*.

### Contenido Recomendado (solo títulos)
- OWASP Top 10 (lectura contextural).
- *Introducción a la Seguridad Informática* (libro).
- CompTIA Security+ (como objetivo de certificación introductoria).
- TryHackMe: *Intro to Pentesting*, YouTube: "Linux desde cero".

## Autoevaluación Asistida
- Define la triada CIA con un ejemplo para cada elemento.
- Describe qué información contiene una respuesta DNS.
- Enlista 5 comandos de red útiles y explica para qué sirve cada uno.
- Escenario: tienes una IP interna con tráfico elevado en puerto 445; describe primeros 3 pasos de investigación.
