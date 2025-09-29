# Zettel — [[Principios de Programación Segura]]

- Date:: 2025-09-29
- Tags:: #zettel #concepto #programacion #seguridad #devsecops

## Idea principal
La programación segura (Secure Coding) es la práctica de escribir código que sea resistente a los ataques y que no introduzca vulnerabilidades de seguridad. Se basa en un conjunto de principios fundamentales.

## Detalles
Dos de los principios más importantes son:

1.  **Validación y Sanitización de Entradas (Input Validation/Sanitization):**
    - **Principio:** Nunca confíes en los datos que provienen del usuario o de fuentes externas.
    - **Práctica:** Todos los datos de entrada deben ser validados para asegurar que tienen el formato, tipo y longitud correctos. Además, deben ser "sanitizados" para eliminar o neutralizar cualquier carácter o secuencia potencialmente maliciosa (ej. escapar caracteres HTML para prevenir XSS, usar consultas parametrizadas para prevenir SQLi).

2.  **Manejo Adecuado de Excepciones (Proper Exception Handling):**
    - **Principio:** El programa debe ser capaz de manejar errores inesperados de forma segura.
    - **Práctica:** Capturar las excepciones y errores de forma controlada, evitando la divulgación de información sensible del sistema (ej. rutas de archivos, trazas de pila) a los usuarios. Los mensajes de error deben ser genéricos para el usuario, pero los detalles deben registrarse en [[Log]]s seguros para los desarrolladores.

## Enlaces
- [[Sanitización de Entradas]]
- [[Manejo de Excepciones]]
- [[XSS]]
- [[SQL Injection]]