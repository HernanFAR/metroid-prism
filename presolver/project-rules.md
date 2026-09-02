---
flavor: PResolver
topic: Project Rules
---

# Reglas base de Metroid Prism

Este documento define reglas mínimas para que una IA pueda trabajar dentro de Metroid Prism sin confundir el objeto estudiado con las herramientas usadas para expresarlo.

## 1. Cada documento declara Flavor y Topic

Todo archivo Markdown del proyecto debe declarar al inicio:

```yaml
---
flavor: <Flavor usado principalmente>
topic: <Topic validado para ese Flavor>
---
```

- **flavor** indica qué herramienta de representación guía principalmente el documento.
- **topic** indica qué clase de asunto se está expresando mediante esa herramienta.

Los valores no deben tratarse como texto libre. Los valores reconocidos y sus combinaciones válidas se definen en `presolver/registry.md`.

La declaración de un Flavor no convierte al Topic en parte de ese Flavor. El Topic pertenece al objeto estudiado; el Flavor es solamente la perspectiva utilizada para expresarlo.

Los documentos de coordinación, definición de reglas o estudio de los propios flavors pueden utilizar `flavor: PResolver`.

Un documento puede apoyarse en otros flavors, incluidos flavors todavía hipotéticos, cuando ayuden a expresar correctamente el Topic. Esa utilización debe quedar explícita en el contenido y no implica que el Flavor hipotético haya sido validado como abstracción definitiva.

## 2. Cada combinación validada debe explicar su frontera

Toda combinación validada de `flavor` y `topic` debe tener un documento propio bajo `presolver/combinations/`.

Ese documento debe explicar al menos:

- qué elementos del Topic puede expresar adecuadamente el Flavor;
- qué elementos no son responsabilidad clara de ese Flavor;
- qué aspectos podrían ser candidatos a otro Topic o a un Flavor nuevo;
- cómo reconocer que la combinación está siendo forzada más allá de su utilidad.

La finalidad no es cerrar la taxonomía, sino hacer visibles las fronteras mientras el material real las tensiona.

## 3. Identificar primero el elemento estudiado

Antes de decidir qué Flavor aplicar, determina **qué cosa de Metroid se está intentando comprender o documentar**.

Puede tratarse, por ejemplo, de:

- un elemento transversal del canon;
- un personaje, especie, facción, lugar o tecnología;
- un evento o cambio persistente;
- la narrativa de una obra;
- una mecánica o experiencia interactiva;
- una decisión de diseño;
- una materialización técnica.

Esta lista no es una taxonomía cerrada. Si el material exige otra clase de elemento, debe registrarse antes de forzarlo dentro de una categoría existente.

## 4. Elegir después las herramientas de representación

Los flavors coordinados por PResolver son **herramientas para expresar perspectivas**, no los elementos de Metroid en sí mismos.

- **NContinuity** ayuda a expresar realidad ficcional y continuidad.
- **IEnacta** ayuda a expresar experiencia interactiva.
- **VSlices** ayuda a expresar materialización técnica.

Una pregunta o documento puede requerir más de un Flavor.

No asumir que porque un elemento puede expresarse con NContinuity, IEnacta o VSlices debe almacenarse necesariamente bajo una carpeta con ese nombre.

## 5. Un Flavor no es una frontera de lectura ni una ontología del objeto

Un Flavor determina una perspectiva útil para explicar algo. No define qué información puede consultarse ni transforma automáticamente aquello que describe en una entidad propia del Flavor.

Ejemplo: NContinuity puede ayudar a expresar worldbuilding, pero el worldbuilding de Metroid **no es NContinuity**.

## 6. Distinguir alcance transversal y alcance de obra

Antes de ubicar conocimiento, determina su alcance.

### Transversal

Describe algo que pertenece al universo compartido más allá de una obra concreta. Ejemplos: especies, personajes, tecnología, lugares, reglas ficcionales, cronología y consecuencias persistentes.

### Específico de obra

Describe propiedades de una materialización concreta. Ejemplos: la narrativa particular de Metroid Fusion, su progresión jugable, sus controles o la implementación técnica de una mecánica.

Un mismo elemento puede relacionar ambos alcances.

## 7. El canon es uno

Las obras no poseen continuidades independientes por defecto. Cada juego revela, representa o modifica una parte del mismo universo canónico.

Cuando dos obras aporten información sobre el mismo objeto ficcional, el conocimiento debe coordinarse en vez de duplicarse como verdades aisladas.

## 8. La narrativa de una obra no se reduce al canon ni a IEnacta

La narrativa de un juego puede seleccionar eventos canónicos, ordenarlos, ocultarlos, revelarlos, focalizarlos y presentarlos desde una estructura propia.

NContinuity puede ayudar a expresar qué es verdadero dentro de la ficción. IEnacta puede ayudar a expresar cómo el jugador vive o descubre esa presentación. Ninguno de los dos se considera por ahora equivalente a la narrativa de la obra.

Hasta que el estudio del material justifique una abstracción más precisa, **Work Narrative** se mantiene como concepto pendiente y no como Flavor oficial.

## 9. Evidence no es Observation

- **Evidence** es la fuente: juego, manual, entrevista, material oficial, código, decompilación u otra referencia relevante.
- **Observation** es aquello que puede establecerse directamente a partir de esa evidencia.

No conviertas automáticamente una interpretación en observación.

## 10. No extender el canon durante la fase descriptiva

Mientras una tarea tenga como objetivo documentar el canon existente:

- no agregar eventos nuevos;
- no completar vacíos con propuestas propias;
- no tratar hipótesis como hechos;
- no reinterpretar una obra para hacerla más coherente de lo que la evidencia permite.

Las propuestas, extensiones y continuidades alternativas deberán declararse explícitamente cuando Metroid Prism entre en una fase de diseño o reinterpretación.

## 11. Las referencias tienen significado

Una referencia entre documentos no debe considerarse solo navegación Markdown. Debe existir porque dos elementos o representaciones mantienen una relación relevante.

PResolver definirá progresivamente el vocabulario de relaciones. Hasta entonces, las relaciones deben describirse con lenguaje explícito y no ambiguo.

Las referencias pueden conectar:

- elementos transversales con elementos de una obra;
- distintos elementos de una misma obra;
- representaciones realizadas con diferentes flavors;
- evidencia con conocimiento documentado.

## 12. No forzar una cadena entre flavors

No asumir que todo conocimiento sigue obligatoriamente una secuencia como:

`NContinuity -> IEnacta -> VSlices`

Los flavors son herramientas complementarias y sus relaciones dependen del elemento estudiado.

Puede existir, por ejemplo:

- worldbuilding sin representación jugable directa;
- una mecánica sin relevancia narrativa;
- una decisión técnica sin correspondencia directa con una mecánica concreta;
- una narrativa de obra que use conocimiento del canon y experiencia interactiva sin reducirse a ninguna de ambas perspectivas.

## 13. Permitir flavors hipotéticos como instrumentos de exploración

Un Flavor hipotético puede utilizarse provisionalmente cuando permita expresar una dimensión que los flavors actuales no cubren bien.

Su uso debe servir para **probar la necesidad de la abstracción**, no para asumirla de antemano.

Si el Flavor hipotético demuestra ser innecesario, redundante o demasiado específico, el conocimiento expresado debe poder conservarse y reorganizarse sin tratar la abstracción descartada como parte del objeto estudiado.

## 14. Preferir conocimiento compartido antes que duplicación

Si un hecho es transversal al universo, debe existir en un lugar transversal apropiado y las obras deben referenciarlo cuando sea necesario.

No copies una definición completa en cada juego salvo que la obra cambie, contradiga, especialice o revele una variante relevante del concepto.

## 15. Dejar que el material refine las reglas

Estas reglas son iniciales. No deben convertirse en dogma.

Si una obra de Metroid no puede representarse limpiamente con las abstracciones o la organización actuales, registra la tensión y revisa el modelo antes de forzar el material dentro de él.
