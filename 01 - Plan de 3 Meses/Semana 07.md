# Forense e Incidentes

## Objetivo de la Semana
Introducción a la informática forense, adquisición de evidencia, análisis de volcado de memoria y respuesta a incidentes.

## Módulos/Temas a Cubrir (U.T.)
- Ciclo de respuesta a incidentes (Preparation, Identification, Containment, Eradication, Recovery, Lessons Learned).
- Herramientas de adquisición: FTK Imager, `dd`.
- Análisis de memoria: Volatility.
- Análisis de discos: Autopsy, sleuthkit.

## Contenido

### Conceptos a aprender
- Preservación de la cadena de custodia.
- Tipos de evidencias: logs, pcap, volcado de memoria.
- Análisis básico con Volatility para buscar procesos y conexiones residuales.

### Actividades Prácticas
- [ ] Crear una imagen de disco simulada con `dd` (lab) y examinarla con Autopsy.
- [ ] Capturar memoria de una VM (si es posible) y analizar con Volatility para listar procesos.
- [ ] Revisar logs del sistema (`/var/log/`, Event Viewer) y correlacionar eventos.
- [ ] Redactar un playbook básico de respuesta a incidentes (3 páginas).

### Contenido Recomendado (solo títulos)
- *Linux Malware Incident Response*.
- NIST SP 800-61: Guide to Computer Security Incident Handling.

## Autoevaluación Asistida
- ¿Cuál es el primer paso al confirmar un incidente de malware?
- Describe cómo tomar un volcado de memoria y por qué es útil.
- Escenario: un servidor muestra procesos desconocidos; lista 5 pasos para triage forense inicial.
