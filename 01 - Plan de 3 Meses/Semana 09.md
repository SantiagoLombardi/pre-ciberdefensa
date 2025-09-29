# Criptografía Aplicada y Matemáticas

## Objetivo de la Semana
Cubrir fundamentos matemáticos aplicados a criptografía (aritmética modular, curvas, intercambio de claves) y prácticas de PKI.

## Módulos/Temas a Cubrir (U.T.)
- Matemáticas discretas básicas: congruencias, aritmética modular, teoría de números.
- Cifrado simétrico vs asimétrico; RSA, ECC.
- Hashing, HMAC, salting y PBKDF2/Bcrypt/Argon2.
- PKI, certificados X.509 y TLS basics.

## Contenido

### Conceptos a aprender
- Por qué RSA depende de factorización y ECC de logaritmo discreto.
- Qué hace un certificado X.509 y cómo validar la cadena de certificación.
- Cómo funcionan HMAC y KDFs para derivación segura de claves.

### Actividades Prácticas
- [ ] Calcular una operación modular (ejercicio manual) y entender inversos modulares.
- [ ] Generar pares de claves RSA/ECC con `openssl` y firmar/verificar un fichero.
- [ ] Configurar un servidor web con TLS (certificado auto-firmado) y analizar handshake TLS con Wireshark.
- [ ] Simular almacenamiento seguro de contraseñas con bcrypt/Argon2 (scripts en Python).

### Contenido Recomendado (solo títulos)
- *Criptografía y seguridad de redes* (libro).
- NIST SP 800-57 (gestión de claves).

## Autoevaluación Asistida
- Explica en términos simples por qué RSA se considera seguro (a qué dificultad matemática se asocia).
- ¿Qué diferencia fundamental hay entre firma digital y cifrado?
- Escenario: detectar un certificado caducado en un servidor; ¿pasos para mitigación?
