# Zettel — [[Aritmética Modular]]

- Date:: 2025-09-29
- Tags:: #zettel #concepto #matematicas #criptografia

## Idea principal
La aritmética modular es un sistema de aritmética para enteros, donde los números "se envuelven" al alcanzar un cierto valor llamado módulo.

## Detalles
Funciona de manera similar a un reloj. En un reloj de 12 horas, las horas se envuelven después de las 12. Por ejemplo, 4 horas después de las 10 no son las 14, sino las 2. En aritmética modular, esto se expresa como `(10 + 4) mod 12 = 2`. Esta propiedad es fundamental para la criptografía de clave pública, como RSA, que basa su seguridad en la dificultad de resolver ciertos problemas dentro de un sistema modular.

## Enlaces
- [[RSA]]
- [[Congruencia]]
- [[Criptografía]]