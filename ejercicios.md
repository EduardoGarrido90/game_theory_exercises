# Ejercicios

[Inicio](README.md) · [Soluciones](soluciones.md)

Todos los pagos son ficticios. Cada jugador intenta obtener el mayor pago para sí mismo.

## Ejercicio 1: Compartir apuntes

Ana y Bruno preparan un examen y deciden simultáneamente **compartir** o **no compartir** sus apuntes. Compartir cuesta esfuerzo y recibir apuntes ayuda. Los puntos resumen esos efectos: **no son notas del examen**.

Cada casilla muestra **(puntos de Ana, puntos de Bruno)**.

| Ana / Bruno | Comparte | No comparte |
|---|---:|---:|
| **Comparte** | (3, 3) | (0, 5) |
| **No comparte** | (5, 0) | (1, 1) |

1. Si Bruno comparte, ¿qué le conviene hacer a Ana? ¿Y si Bruno no comparte?
2. Repite el razonamiento para Bruno. Encuentra el equilibrio de Nash.
3. ¿Qué combinación daría a ambos más puntos que el equilibrio? ¿Por qué hay un dilema?

## Ejercicio 2: Elegir aula

Carla y Diego quieren estudiar juntos. Sin comunicarse, eligen simultáneamente **aula A** o **aula B**. Les da igual el aula: coincidir da 2 puntos a cada uno y separarse da 0.

Cada casilla muestra **(puntos de Carla, puntos de Diego)**.

| Carla / Diego | Aula A | Aula B |
|---|---:|---:|
| **Aula A** | (2, 2) | (0, 0) |
| **Aula B** | (0, 0) | (2, 2) |

1. Si Diego elige A, ¿qué prefiere Carla? ¿Y si elige B?
2. Encuentra los **dos equilibrios de Nash en decisiones puras** y comprueba qué pasa si alguien cambia solo.
3. ¿Es (A, B) un equilibrio? ¿Para qué serviría acordar un aula antes de elegir?

## Ejercicio 3: Un puesto escolar

Dos pequeñas empresas ficticias, **Sol** y **Luna**, consideran vender limonada en una feria escolar. Primero Sol decide **abrir** o **no abrir**. Luna observa esa decisión y después decide **abrir** o **no abrir**.

Cada pareja muestra **(beneficio de Sol, beneficio de Luna)** en euros ficticios. Son beneficios netos: ya incluyen los costes.

```text
Sol decide
├── Abrir → Luna decide
│   ├── Abrir     → (1, 1)
│   └── No abrir  → (4, 0)
└── No abrir → Luna decide
    ├── Abrir     → (0, 4)
    └── No abrir  → (0, 0)
```

1. Si Sol ha abierto, ¿qué le conviene a Luna? Si Sol no ha abierto, ¿qué decide Luna?
2. Anticipando esas respuestas, compara los beneficios de Sol al abrir y al no abrir. ¿Qué elige?
3. Escribe el resultado final y los beneficios. ¿Por qué has empezado por las decisiones de Luna?
