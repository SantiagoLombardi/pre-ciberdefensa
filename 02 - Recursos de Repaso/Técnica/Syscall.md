# Zettel — [[Syscall]]

- Date:: 2025-09-29
- Tags:: #zettel #concepto #sistema_operativo #kernel

## Idea principal
Una Syscall (llamada al sistema) es el mecanismo fundamental que utiliza un programa de aplicación para solicitar un servicio al kernel del sistema operativo.

## Detalles
Dado que el kernel se ejecuta en un espacio de memoria protegido (kernel space), las aplicaciones en el espacio de usuario (user space) no pueden acceder directamente a los recursos del sistema (como hardware o archivos). Las syscalls actúan como una interfaz controlada para realizar operaciones privilegiadas, como abrir un archivo (`open`), crear un proceso (`fork`) o establecer una conexión de red (`socket`). Monitorear syscalls es una técnica avanzada de detección de malware.

## Enlaces
- [[Kernel]]
- [[Sistema Operativo]]
- [[Endpoint Detection and Response (EDR)]]