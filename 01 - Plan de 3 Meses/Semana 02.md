# Redes y Hardening

## Objetivo de la Semana
Profundizar en direccionamiento, DHCP/DNS, administración de usuarios y aplicar prácticas básicas de hardening.

## Módulos/Temas a Cubrir (U.T.)
- Subnetting, NAT, DHCP/DNS.
- Administración de usuarios en Linux/Windows.
- Hardening básico y gestión de parches.
- Introducción a virtualización y snapshots.

## Contenido

### Conceptos a aprender
- CIDR, máscara, gateway, NAT.
- Configuración y funcionamiento de DHCP y DNS.
- Listas de control: permisos y grupos en Linux/Windows.
- Recomendaciones de hardening: deshabilitar servicios, aplicar parches.

### Actividades Prácticas
- [ ] Crear subredes en tu laboratorio y probar conectividad entre subredes.
- [ ] Configurar `dnsmasq` o Bind en una VM como servidor DNS local.
- [ ] Crear usuarios limitados y probar sudoers.
- [ ] Aplicar actualizaciones y documentar proceso (apt/yum/Windows Update).
- [ ] **Opcional:** Implementar una VM pfSense y crear reglas básicas de firewall.

### Contenido Recomendado (solo títulos)
- *Computer Networking* (Kurose & Ross).
- CCNA (material de estudio).
- NIST SP 800-53 (lectura de controles).

## Autoevaluación Asistida
- Explica cómo funciona NAT y por qué se usa.
- ¿Qué es una máscara /24 y cuántas direcciones útiles tiene?
- Escenario: un servicio expuesto en puerto 3389 (RDP) no debería ser público; ¿qué medidas de hardening propones?
