---
flavor: presolver
topic: metroid-prism
---

# Metroid Prism

Metroid Prism es un estudio del universo y las obras de Metroid apoyado por múltiples herramientas de representación.

Su objetivo no es convertir a Metroid en una colección de flavors. Metroid, su canon, sus obras, su narrativa, su worldbuilding, sus mecánicas y sus implementaciones son el **objeto de estudio**. Los flavors son instrumentos conceptuales que ayudan a expresar perspectivas parciales sobre esos elementos.

El proyecto parte de una idea simple: un mismo elemento puede requerir varias perspectivas para ser comprendido y expresado correctamente.

## Herramientas iniciales

PResolver coordina distintas herramientas o **flavors** de representación:

- **NContinuity**: ayuda a expresar la realidad ficcional y su continuidad, incluyendo worldbuilding, eventos, relaciones, estados y cambios persistentes.
- **IEnacta**: ayuda a expresar la experiencia interactiva mediante la cual una obra hace vivir, descubrir o manipular elementos del juego y del universo.
- **VSlices**: ayuda a expresar la materialización técnica de comportamientos, reglas y sistemas.

Pueden aparecer nuevos flavors cuando una perspectiva suficientemente distinta requiera una herramienta propia.

Los flavors no son narrativa, worldbuilding, gameplay o implementación en sí mismos. Tampoco determinan necesariamente la estructura de carpetas del conocimiento estudiado. Son formas de describirlo.

## Elementos estudiados

Metroid Prism podrá estudiar elementos transversales al universo y elementos propios de obras concretas. Entre ellos pueden aparecer, sin pretender cerrar todavía la taxonomía:

- canon y worldbuilding;
- personajes, especies, facciones, lugares y tecnología;
- eventos y continuidad;
- narrativa de una obra;
- experiencia interactiva y mecánicas;
- diseño visual, sonoro u otras dimensiones perceptuales;
- implementación técnica.

Algunos de estos elementos podrán requerir uno o varios flavors para ser expresados correctamente.

## Principios iniciales

1. **El objeto estudiado no es el Flavor.** Un Flavor es una herramienta de representación aplicada sobre uno o más elementos de Metroid.
2. **Un Flavor expresa una perspectiva, no un aislamiento.** Un documento puede apoyarse en varios flavors o referenciar conocimiento expresado mediante otros flavors cuando sea semánticamente relevante.
3. **El canon es transversal a las obras.** Un juego representa, revela o modifica una parte del mismo universo canónico, pero una obra concreta también posee propiedades propias como narrativa, estructura interactiva y materialización técnica.
4. **Las referencias entre documentos son parte del conocimiento.** PResolver deberá definir cómo expresar, interpretar y coordinar esas relaciones sin imponer que los flavors sean la estructura primaria del repositorio.
5. **Evidence y Observation son conceptos distintos.** Una fuente constituye evidencia; aquello que puede establecerse directamente desde ella constituye una observación.
6. **No se deben introducir extensiones al canon mientras el objetivo sea documentar el canon existente.** Inferencias creativas, propuestas y continuidades alternativas pertenecen a etapas explícitamente diferenciadas del estudio.
7. **La estructura debe emerger del material.** Metroid Prism no intenta definir de antemano un esquema universal para videojuegos; las obras deberán tensionar y refinar tanto las abstracciones como la organización del proyecto.

## Sobre la narrativa de una obra

La narrativa de un juego se reconoce por ahora como un elemento propio de la obra, distinto de la continuidad ficcional transversal y de la experiencia interactiva.

Por ejemplo, NContinuity puede ayudar a expresar qué eventos son verdaderos en el canon; una futura representación narrativa podrá describir qué eventos selecciona una obra, en qué orden los presenta, desde qué perspectiva y cómo administra su revelación; IEnacta puede ayudar a expresar cómo el jugador vive o descubre esa presentación.

Por ahora esto se mantiene como un **concepto pendiente**, no como un Flavor oficial. Preferimos observar cómo aparece en los juegos antes de formalizar una herramienta dedicada.

## Alcance inicial

El estudio recorrerá el canon de Metroid obra por obra, considerando como referencias principales las versiones que actualmente representan los eventos canónicos correspondientes, incluyendo **Metroid: Zero Mission** y **Metroid: Samus Returns**, además de la saga **Metroid Prime**.

Antes de modelar cada obra, PResolver y los flavors deberán establecer reglas mínimas de navegación, responsabilidad y referencia suficientes para que una IA pueda determinar correctamente qué elemento está estudiando, qué herramientas pueden ayudar a expresarlo, qué conocimiento debe consultar y dónde conviene registrar nuevos hallazgos.
