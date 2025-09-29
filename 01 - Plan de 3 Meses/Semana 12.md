# Proyecto Final Integrador / Simulación

## Objetivo de la Semana
Integrar lo aprendido: realizar una simulación (red simulada) que cubra reconocimiento, explotación controlada, detección, respuesta y reporte de inteligencia.

## Módulos/Temas a Cubrir (U.T.)
- Diseño y ejecución de un ejercicio red-team vs blue-team (escenario controlado).
- Recolección de IOCs y creación de reporte CTI.
- Ejecución de playbook de respuesta a incidentes y lecciones aprendidas.

## Contenido

### Conceptos a aprender
- Cómo coordinar un ejercicio que incluya fases: Recon, Acceso Inicial, Escalada, Movimiento Lateral, Exfiltración y Recuperación.
- Métricas de ejercicio: tiempo a detección (MTTD), tiempo a contención (MTTC), cobertura de logs.

### Actividades Prácticas (Proyecto sugerido)
- [ ] **Planificación (día 1):** Definir objetivos del ejercicio, alcance (hosts), reglas de compromiso y backups.  
- [ ] **Fase ofensiva (día 2-3):** Realizar recon, escaneo y explotación en hosts diseñados para pruebas. Documentar TTP.  
- [ ] **Fase defensiva (día 3-4):** En paralelo, activar SIEM/IDS, monitorear, detectar y contener acciones ofensivas.  
- [ ] **Post-mortem (día 5):** Documentar IOCs, preparar un informe CTI y un playbook de mitigación.  
- [ ] **Entrega:** Crear un archivo .md con el reporte final que incluya: resumen ejecutivo, timeline, IOCs, recomendaciones y matriz de riesgo.

### Contenido Recomendado (solo títulos)
- *The Hacker Playbook* series (para metodología).
- MITRE ATT&CK (mapeo final).

## Autoevaluación Asistida
- Prepara un informe ejecutivo de 1 página que responda: ¿Qué pasó? ¿Cómo se detectó? ¿Qué mitigaciones se aplicaron? ¿Qué falta mejorar?
- Mide y documenta: MTTD y MTTC del ejercicio (valores medidos).
- Escenario: si el ejercicio mostrara que un servidor de base de datos quedó sin logs, ¿qué recomendaciones inmediatas propones?
