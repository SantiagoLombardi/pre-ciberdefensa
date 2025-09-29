# Zettel — [[Regex (Expresiones Regulares)]]

- Date:: 2025-09-29
- Tags:: #zettel #concepto #programacion #parsing

## Idea principal
Una expresión regular (regex) es una secuencia de caracteres que define un patrón de búsqueda. Se utiliza para la búsqueda y manipulación de texto.

## Detalles
Las regex son una herramienta extremadamente poderosa y omnipresente en la informática. En ciberseguridad, se utilizan para:

- **Análisis de Logs:** Buscar patrones específicos que puedan indicar una actividad maliciosa (ej. intentos de login fallidos, patrones de ataque en logs de firewall).
- **Validación de Entradas:** Asegurarse de que los datos introducidos por un usuario se ajustan a un formato esperado, para prevenir ataques como XSS o SQLi.
- **Reglas de IDS/IPS:** Definir patrones de tráfico de red que deben ser bloqueados o alertados.
- **Data Loss Prevention (DLP):** Identificar datos sensibles como números de tarjetas de crédito o DNI en el tráfico de red o en archivos.

Aunque son muy potentes, las regex complejas pueden ser difíciles de leer y mantener, y pueden ser vulnerables a ataques de Denegación de Servicio (ReDoS).

## Enlaces
- [[Análisis de Logs]]
- [[IDS]]
- [[DLP]]