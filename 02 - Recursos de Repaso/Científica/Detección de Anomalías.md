# Zettel — [[Detección de Anomalías]]

- Date:: 2025-09-29
- Tags:: #zettel #concepto #seguridad #monitoreo #ia

## Idea principal
La detección de anomalías es una técnica de seguridad que consiste en identificar patrones en los datos que no se conforman con el comportamiento esperado o normal.

## Detalles
En lugar de buscar firmas de ataques conocidos (como hacen los antivirus tradicionales), este enfoque establece una línea base del comportamiento normal del sistema o de la red. Cualquier desviación significativa de esta línea base se marca como una anomalía y se investiga. 

Este método es especialmente útil para detectar ataques de día cero y amenazas internas. Se basa en gran medida en conceptos de [[Probabilidad Condicional]] y estadística para modelar el comportamiento normal y calcular la probabilidad de que una desviación sea maliciosa. Es una técnica clave en [[IDS]] y soluciones de User and Entity Behavior Analytics (UEBA).

## Enlaces
- [[Probabilidad Condicional]]
- [[IDS]]
- [[UEBA]]
- [[Ataque de Día Cero]]