# Case Study Intermediate Python- Hacker Statistics🎲

Imagina lo siguiente: estás caminando por el Empire State Building hasta DataCamp HeadQuarters y estás jugando con un amigo. Tiras un dado cien veces:
- Si es 1 o 2, bajará un escalón.
- Si es 3, 4 o 5, subirás un paso.
- Si sacas un 6, lanzarás el dado de nuevo y subirás el número de pasos resultante.

Por supuesto, no puedes ir más bajo que el escalón número 0. Y también, admites que eres un poco torpe y que tienes un 0,1% de posibilidades de caerte por las escaleras cuando haces un movimiento. Caerte significa que tienes que empezar de nuevo desde el paso 0. 

Con todo esto en mente, apuestas con tu amigo a que llegarás a los 60 pasos de altura.

**¿Cuál es la probabilidad de que ganes esta apuesta?**

Para resolverlo simularemos este proceso miles de veces y ver en qué fracción de las simulaciones alcanzará los 60 pasos. Esta es una forma de -hackear estadísticas-.
