---
id: 20251001211149
date: 2025-10-01
tags:
  - zettel
  - censys
  - redes
---
# Censys

## Idea Atómica

**Censys** es una **plataforma de inteligencia de amenazas** y motor de búsqueda para internet que opera de forma similar a Shodan, enfocándose en la **clasificación de activos** (_Asset Inventory_) y la **evaluación continua de riesgos** mediante escaneos detallados de puertos y certificados SSL/TLS.

## Desarrollo

Censys, desarrollado originalmente en la **Universidad de Michigan**, se distingue por su enfoque en la **transparencia y profundidad** del escaneo, indexando no solo la información del _banner_ (como Shodan) sino también datos ricos de configuraciones de TLS/SSL, certificados digitales, y la interconexión de _hosts_ en la web.

### Diferencias Clave con Shodan (Contexto de _Recon_)

Mientras que Shodan es más conocido por su capacidad para encontrar dispositivos basados en los _banners_ de respuesta de sus servicios, Censys ofrece bases de datos estructuradas con mayor **énfasis en la criptografía** y la cadena de confianza. Sus bases de datos principales son:

1. **Hosts (Direcciones IP):** Similar a Shodan, indexa protocolos y servicios abiertos.
2. **Certificados (Certificados TLS/SSL):** Examina e indexa todos los certificados encontrados en Internet, lo que es crucial para la **identificación de dominios** y la **monitorización de _phishing_** o infraestructura maliciosa.

### Utilidad Avanzada en Ciberseguridad

- **Gestión de Superficie de Ataque Externa (EASM):** Las organizaciones lo usan para ver su infraestructura desde la perspectiva de un atacante, descubriendo **activos olvidados** (_shadow IT_) y determinando si todos los certificados están a punto de caducar o usan **cifrados débiles**.

- **Detección de Amenazas:** Permite búsquedas extremadamente específicas, como encontrar todos los _hosts_ que usan un **certificado autofirmado** o que exponen una versión particular de OpenSSL con una vulnerabilidad crítica.

- **Investigación de Ciberdelincuentes:** Al igual que Shodan, ayuda a perfilar la infraestructura de un atacante o de un grupo APT, rastreando patrones en sus configuraciones y el uso de certificados.


En un estudio de ciberseguridad, utilizar Censys y Shodan conjuntamente proporciona una **visión completa y bidimensional** del panorama de seguridad global y del riesgo asociado a los activos conectados.

## Conexiones

- **Fuente(s):** Documentación oficial de Censys, Investigaciones académicas sobre escaneo de internet a gran escala, Artículos de análisis de _threat intelligence_.
- **Notas relacionadas:**
- [[Shodan]] (Herramienta principal para escaneo pasivo/activo de internet)
- [[TLS]] (Protocolo de cifrado analizado por Censys)
- [[Criptografia]] (Base teórica de los datos de certificados)
- [[Gestion-Superficie-de-Ataque-EASM]] (Concepto que Censys ayuda a implementar)
- [[Certificados-Digitales-Seguridad-y-Riesgos]] (Uso de la base de datos de certificados)
