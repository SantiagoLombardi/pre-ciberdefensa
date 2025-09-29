# SIEM, Logs y Análisis

## Objetivo de la Semana
Aprender a recolectar, normalizar y correlacionar logs; introducción a SIEM y reglas básicas de detección.

## Módulos/Temas a Cubrir (U.T.)
- Tipos de logs: syslog, Windows Event Logs, firewall logs, netflow, pcap.
- SIEM básico: ELK stack (Elasticsearch, Logstash, Kibana) o alternativas (Wazuh).
- Reglas de correlación y alertas.

## Contenido

### Conceptos a aprender
- Normalización y parsing de logs.
- Configuración básica de un pipeline ELK/Wazuh para ingestión.
- Detección de patrones: brute force, anomalías de tráfico.

### Actividades Prácticas
- [ ] Configurar Filebeat/Logstash para enviar logs de una VM al ELK local (o Wazuh).
- [ ] Crear una alerta simple en Kibana (por ejemplo, X intentos de login fallidos).
- [ ] Analizar un pcap con tshark/wireshark y extraer indicadores (IPs, dominios).
- [ ] **Opcional:** Integrar Suricata para generar alertas y visualizarlas en ELK.

### Contenido Recomendado (solo títulos)
- Wazuh documentation (servicio SIEM open source).
- Elasticsearch: guía básica de ingestión y queries.

## Autoevaluación Asistida
- ¿Qué diferencia hay entre un SIEM y un sistema de logs centralizados?
- Diseña una regla simple para detectar escaneos de puertos.
- Escenario: recibes un threshold de 500 conexiones nuevas en 5 minutos desde una IP; ¿qué investigas primero?
