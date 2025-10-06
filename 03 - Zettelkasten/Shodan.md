---
id: 20251001210256
date: 2025-10-01
tags:
  - zettel
  - shodan
  - navegador
---
# Shodan

## Idea Atómica
**Shodan** es un **motor de búsqueda** especializado que indexa *banners* y metadatos de dispositivos conectados a Internet (como servidores, cámaras web y sistemas de control industrial) para facilitar la **detección de activos y la identificación de vulnerabilidades**.

## Desarrollo
Shodan, a menudo apodado el "**buscador de la Internet de las Cosas (IoT)**" o el "**Google de *hackers***," funciona de manera fundamentalmente diferente a motores de búsqueda tradicionales como Google. En lugar de buscar contenido en páginas web, Shodan escanea puertos y servicios en todo el espectro de direcciones IP públicas para recopilar **información de *banners***. Un *banner* es la respuesta de texto que un servicio de red (como un servidor web o SSH) envía automáticamente cuando se establece una conexión (p. ej., un servidor web reporta `Server: Apache/2.4.6`). 

Esta información incluye:
* **Tipo de dispositivo** (cámara, *router*, servidor, impresora, SCADA, etc.).
* **Sistema operativo** y **versión del *software***.
* **Ubicación geográfica** (a nivel de ciudad/país).
* **Puertos abiertos** y **protocolos** en uso.

### Utilidad en Ciberseguridad
* **Auditoría y *Penetration Testing***: Los *pentesters* lo usan para obtener una **visibilidad externa** de la infraestructura de una organización, revelando **superficies de ataque** no intencionadas (como puertos expuestos o servicios desactualizados).
* **Investigación de Amenazas ([[CTI (Cyber Threat Intelligence)|Threat Intelligence]])**: Permite a los analistas rastrear la distribución global de *malware* o identificar la prevalencia de vulnerabilidades específicas (por ejemplo, buscando todos los servidores que ejecutan una versión de *software* con una vulnerabilidad conocida, como *Heartbleed*).
* **Defensa (Blue Team)**: Los equipos de seguridad pueden usar Shodan para verificar que sus propios dispositivos no estén accidentalmente expuestos al público y para monitorear la **exposición de sus activos**.

A diferencia de Google, que respeta el archivo `robots.txt`, Shodan escanea activamente y expone dispositivos que a menudo no están destinados a ser accesibles públicamente o que tienen configuraciones predeterminadas (como credenciales por defecto) que representan **riesgos de seguridad críticos**.

## Conexiones
- **Fuente(s):** Documentación oficial de Shodan, Apuntes de clase/lectura sobre ciberinteligencia (CTI) y reconocimiento (*Reconnaissance*).
- **Notas relacionadas:**
  - [[Censys]] (Motor de búsqueda alternativo con enfoque en certificados)
  - [[Ciberinteligencia-CTI-Introduccion]] (Contexto más amplio de la inteligencia de amenazas)
  - [[Vulnerabilidades-Criticas-Tipos-y-CVSS]] (Relación con la identificación de *software* vulnerable)
  - [[Fases-del-Pen-Testing-Reconocimiento]] (Etapa donde Shodan es fundamental)
  - [[IoT-Seguridad-Dispositivos-y-Riesgos]] (El foco principal de los activos indexados)

---