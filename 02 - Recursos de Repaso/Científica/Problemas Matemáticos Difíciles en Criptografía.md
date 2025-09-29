# Zettel — [[Problemas Matemáticos Difíciles en Criptografía]]

- Date:: 2025-09-29
- Tags:: #zettel #concepto #criptografia #matematicas

## Idea principal
La seguridad de la mayoría de los algoritmos de criptografía asimétrica se fundamenta en la supuesta dificultad computacional de resolver ciertos problemas matemáticos.

## Detalles
Un "problema difícil" en este contexto es uno para el cual no se conoce un algoritmo eficiente que pueda resolverlo en un tiempo razonable (tiempo polinomial) para entradas grandes. La seguridad reside en la brecha que existe entre la facilidad para realizar una operación en una dirección y la extrema dificultad para revertirla.

Ejemplos clave:
- **Problema de la Factorización de Enteros:** Base de [[RSA]]. Es fácil multiplicar dos números primos grandes, pero es extremadamente difícil encontrar los factores primos originales a partir del producto.
- **Problema del Logaritmo Discreto (DLP):** Base de DSA y Diffie-Hellman. 
- **Problema del Logaritmo Discreto de Curva Elíptica (ECDLP):** Base de [[Criptografía de Curva Elíptica (ECC)]]. Es una variante del DLP que ofrece mayor seguridad con claves más cortas.

## Enlaces
- [[Criptografía Asimétrica]]
- [[RSA]]
- [[Criptografía de Curva Elíptica (ECC)]]