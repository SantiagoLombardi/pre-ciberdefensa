# Zettel — [[Entropía (Criptografía)]]

- Date:: 2025-09-29
- Tags:: #zettel #concepto #criptografia #aleatoriedad

## Idea principal
En el contexto de la criptografía, la entropía es una medida de la imprevisibilidad o aleatoriedad de los datos. 

## Detalles
Una alta entropía es fundamental para la generación de claves criptográficas seguras, nonces e initialization vectors (IVs). Si los datos utilizados para generar una clave tienen baja entropía (es decir, son predecibles), la clave resultante será débil y vulnerable a ataques de fuerza bruta o adivinación. Los generadores de números pseudoaleatorios (CSPRNG) están diseñados para producir salidas con alta entropía para fines criptográficos.

## Enlaces
- [[Generación de Claves]]
- [[CSPRNG]]
- [[Ataque de Fuerza Bruta]]