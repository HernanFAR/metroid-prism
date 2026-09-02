---
flavor: PResolver
topic: Flavor and Topic Registry
---

# Registro de Flavor y Topic

Este documento define los valores reconocidos actualmente para `flavor` y los `topic` válidos asociados a cada uno.

La intención es que ambos campos sean vocabularios controlados. Si una necesidad real no cabe en ellos, debe registrarse la tensión y evaluar una extensión del registro en vez de inventar silenciosamente un valor nuevo.

## Flavors reconocidos

### PResolver

Herramienta de coordinación. Define reglas para elegir, combinar, relacionar y evaluar flavors y topics.

Topics válidos actuales:

- `Project Rules`
- `Flavor and Topic Registry`
- `Flavor Definition`
- `Pending Concept`
- `Flavor Topic Combination`

### NContinuity

Herramienta para expresar realidad ficcional y continuidad: qué existe, cómo funciona, qué ocurrió y qué persiste o cambia dentro del universo.

Topics válidos actuales:

- `Historia`
- `Worldbuilding`

Estos topics son iniciales y deberán tensionarse contra el material real.

### IEnacta

Herramienta para expresar experiencia interactiva.

Todavía no posee topics validados. Deben emerger del estudio de las obras.

### VSlices

Herramienta para expresar materialización técnica.

Todavía no posee topics validados. Deben emerger del estudio de las obras.

## Combinaciones válidas

Cada combinación validada de `flavor` y `topic` debe tener un documento propio bajo `presolver/combinations/`.

Actualmente se reconoce:

- `NContinuity + Historia`

`NContinuity + Worldbuilding` se reconoce provisionalmente como combinación posible por la definición actual de NContinuity, pero debe documentarse como combinación sólo cuando el análisis de Metroid nos obligue a precisar sus fronteras.

## Extensión del registro

Un nuevo Flavor o Topic no debe agregarse sólo porque resulte conceptualmente imaginable.

Debe existir una necesidad observada en el material o en la coordinación que justifique distinguirlo.

El uso provisional de un Flavor o Topic hipotético está permitido cuando se declare explícitamente como exploratorio. Su utilidad deberá evaluarse antes de incorporarlo a este registro como valor validado.
