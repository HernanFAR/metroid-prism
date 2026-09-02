# Reglas base de Metroid Prism

Este documento define las reglas mínimas que una IA debe aplicar al trabajar dentro de Metroid Prism.

## 1. Identificar primero la perspectiva

Antes de crear o modificar conocimiento, determina desde qué Flavor se está hablando.

- **NContinuity**: realidad ficcional y continuidad del universo.
- **IEnacta**: experiencia interactiva de una obra concreta.
- **VSlices**: materialización técnica de reglas, comportamientos y sistemas.
- **PResolver**: coordinación entre flavors, alcances y referencias.

La misma materia puede aparecer en varios flavors si cada documento expresa una perspectiva distinta sobre ella.

## 2. Un Flavor no es una frontera de lectura

Un documento puede y debe consultar o referenciar documentos de otros flavors cuando exista una relación semántica relevante.

La pertenencia a un Flavor determina la responsabilidad principal de la afirmación, no qué información puede consultar.

## 3. Distinguir alcance transversal y alcance de obra

Antes de ubicar conocimiento, determina su alcance.

### Transversal

Describe el universo de Metroid más allá de una obra concreta. Ejemplos: especies, personajes, tecnología, lugares, reglas ficcionales, cronología y consecuencias persistentes.

### Específico de obra

Describe cómo una obra concreta presenta, enactúa o implementa una parte del universo. Ejemplos: progresión jugable de Metroid Fusion, controles de Metroid Prime o implementación técnica de una mecánica en Zero Mission.

Un documento puede relacionar ambos alcances.

## 4. El canon es uno

Las obras no poseen continuidades independientes por defecto. Cada juego revela, representa o modifica una parte del mismo universo canónico.

Cuando dos obras aporten información sobre el mismo objeto ficcional, el conocimiento debe coordinarse en vez de duplicarse como verdades aisladas.

## 5. Evidence no es Observation

- **Evidence** es la fuente: juego, manual, entrevista, material oficial, código, decompilación u otra referencia relevante.
- **Observation** es aquello que puede establecerse directamente a partir de esa evidencia.

No conviertas automáticamente una interpretación en observación.

## 6. No extender el canon durante la fase descriptiva

Mientras una tarea tenga como objetivo documentar el canon existente:

- no agregar eventos nuevos;
- no completar vacíos con propuestas propias;
- no tratar hipótesis como hechos;
- no reinterpretar una obra para hacerla más coherente de lo que la evidencia permite.

Las propuestas, extensiones y continuidades alternativas deberán declararse explícitamente cuando Metroid Prism entre en una fase de diseño o reinterpretación.

## 7. Las referencias tienen significado

Una referencia entre documentos no debe considerarse solo navegación Markdown. Debe existir porque un conocimiento depende, enactúa, implementa, evidencia, contrasta o se relaciona de otra forma con otro conocimiento.

PResolver definirá progresivamente el vocabulario de relaciones. Hasta entonces, las relaciones deben describirse con lenguaje explícito y no ambiguo.

## 8. No forzar una cadena entre flavors

No asumir que todo conocimiento sigue obligatoriamente una secuencia como:

`NContinuity -> IEnacta -> VSlices`

Puede haber:

- conocimiento NContinuity sin representación jugable directa;
- mecánicas IEnacta sin relevancia narrativa;
- decisiones VSlices de infraestructura sin correspondencia directa con una mecánica concreta;
- referencias directas entre cualquier par de flavors cuando corresponda.

## 9. Preferir conocimiento compartido antes que duplicación

Si un hecho es transversal al universo, debe existir en un lugar transversal apropiado y las obras deben referenciarlo cuando sea necesario.

No copies una definición completa en cada juego salvo que la obra cambie, contradiga o revele una variante relevante del concepto.

## 10. Dejar que el material refine las reglas

Estas reglas son iniciales. No deben convertirse en dogma.

Si una obra de Metroid no puede representarse limpiamente con las abstracciones actuales, registra la tensión y revisa las abstracciones antes de forzar el material dentro de ellas.
