# Soluciones razonadas y verificadas

[Inicio](README.md) · [Ejercicios](ejercicios.md)

## Solución 1: Compartir apuntes

1. Si Bruno comparte, Ana prefiere no compartir: **5 > 3**. Si Bruno no comparte, Ana también prefiere no compartir: **1 > 0**.
2. Por simetría, Bruno tiene las mismas preferencias. No compartir es una **estrategia estrictamente dominante** para ambos. El único equilibrio de Nash es **(No comparte, No comparte)**, con pagos **(1, 1)**. Cualquier cambio unilateral reduce el pago del que cambia de 1 a 0.
3. Compartir ambos daría **(3, 3)**: ambos mejorarían respecto a (1, 1). Pero si el otro comparte, no compartir permite pasar de 3 a 5. El dilema es el conflicto entre los incentivos individuales y el beneficio mutuo.

**Verificación:** 5 > 3 > 1 > 0. Cada jugador prefiere estrictamente no compartir ante cualquiera de las dos acciones del otro; ninguna otra casilla puede ser equilibrio.

## Solución 2: Elegir aula

1. Carla prefiere A si Diego elige A (2 > 0), y B si Diego elige B (2 > 0). Diego razona igual.
2. Los equilibrios puros son **(A, A)** y **(B, B)**. En ambos, cambiar solo reduce el pago del que cambia de 2 a 0.
3. **(A, B) no es equilibrio**: Carla puede cambiar a B y mejorar de 0 a 2; Diego también podría mejorar cambiando solo a A. Lo mismo ocurre con (B, A). Un acuerdo previo que ambos sigan ayuda a coincidir.

**Verificación:** de las cuatro casillas, solo las dos diagonales son mejores respuestas mutuas. Hay exactamente **dos equilibrios puros**. Si se permiten sorteos, existe además un equilibrio mixto en el que cada jugador elige cada aula con probabilidad 1/2; no se necesita para resolver este ejercicio.

## Solución 3: Un puesto escolar

1. Tras abrir Sol, Luna prefiere abrir (1 euro) a no abrir (0 euros): **1 > 0**. Tras no abrir Sol, Luna también prefiere abrir: **4 > 0**.
2. Sol anticipa que Luna abrirá en ambos casos. Abrir le da **1 euro** y no abrir le da **0 euros**. Por tanto, Sol abre.
3. **Ambas abren**, con beneficios **(1, 1) euros**. Se empieza por Luna para anticipar su respuesta antes de decidir qué le conviene a Sol: eso es la **inducción hacia atrás**.

**Verificación:** la estrategia completa es «Sol abre; Luna abre tras cualquiera de las dos decisiones de Sol». Las decisiones se apoyan en desigualdades estrictas: 1 > 0, 4 > 0 y, finalmente, 1 > 0 para Sol. La inducción hacia atrás determina una solución única, llamada equilibrio perfecto en subjuegos.
