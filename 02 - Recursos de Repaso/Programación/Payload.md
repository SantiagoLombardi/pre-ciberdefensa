# Zettel — [[Payload]]

- Date:: 2025-09-29
- Tags:: #zettel #concepto #programacion #ofensiva #exploit

## Idea principal
En el contexto de un [[Exploit]], el payload es la parte del código que ejecuta la acción maliciosa en el sistema objetivo después de que la vulnerabilidad ha sido explotada con éxito.

## Detalles
El exploit es la "llave" que abre la puerta; el payload es "lo que se hace" una vez dentro. La función del exploit es simplemente entregar y activar el payload.

Tipos comunes de payloads:
- **Reverse Shell / Bind Shell:** Proporcionan acceso de línea de comandos remoto al sistema comprometido.
- **Stagers:** Payloads pequeños cuya única función es descargar y ejecutar un payload más grande y complejo (el "stage").
- **Meterpreter:** Un payload avanzado del Metasploit Framework con una amplia gama de funcionalidades para la post-explotación.

## Enlaces
- [[Exploit]]
- [[Shell]]
- [[Metasploit]]