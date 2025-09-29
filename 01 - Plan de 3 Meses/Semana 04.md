# Vulnerabilidades Web y Explotación

## Objetivo de la Semana
Entender las vulnerabilidades web principales (OWASP Top 10) y practicar explotación básica con proxies y herramientas.

## Módulos/Temas a Cubrir (U.T.)
- OWASP Top 10: XSS, SQLi, CSRF, etc.
- Burp Suite / OWASP ZAP como proxy.
- SQLMap, DVWA, OWASP Juice Shop.
- Metasploit para exploits comunes.

## Contenido

### Conceptos a aprender
- Tipos de XSS y mitigaciones.
- SQL Injection: parametrización y ORM como mitigación.
- Ciclo de explotación: identificación, elaboración de payload, explotación, post-explotación.

### Actividades Prácticas
- [ ] Montar DVWA o Juice Shop y explotar SQLi.  
- [ ] Usar Burp Suite para interceptar y modificar peticiones.  
- [ ] Realizar XSS reflejado en una aplicación de laboratorio.  
- [ ] Usar SQLMap para extraer una tabla de prueba.  
- [ ] **Opcional:** Hacer un scan con OWASP ZAP y analizar falsos positivos.

### Contenido Recomendado (solo títulos)
- *The Web Application Hacker's Handbook*.
- OWASP Top 10 (documento oficial).
- TryHackMe: *Web Fundamentals*.

## Autoevaluación Asistida
- Define XSS almacenado vs reflejado con ejemplos.
- ¿Por qué la parametrización evita SQLi?
- Escenario: un formulario muestra datos sin sanitizar; propone 3 pruebas para confirmar XSS.
