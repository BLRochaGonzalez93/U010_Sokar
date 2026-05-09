# U010_Sokar

[English](README.en.md) | [Español](README.md)

## Resumen

**SOKAR: La Venganza del Mal** es un concepto/GDD completo para un juego de terror 3D en primera persona. El jugador controla a **Daniel Hernández**, hijo del fallecido Dr. Raúl Hernández, que regresa a la casa familiar para recoger recuerdos y documentos de su padre, pero acaba atrapado en una pesadilla marcada por una maldición familiar y por la presencia de una entidad demoníaca conocida como **Sokar**.

El proyecto está diseñado alrededor de exploración, tensión ambiental, sigilo, detección de audio, linterna, inventario limitado, puzzles, jumpscares aleatorios y una narrativa de terror psicológico centrada en el misterio de la familia Hernández.

## Colaboración

Proyecto conceptual desarrollado junto a **Hugo C.R.** y **Sergio M.C.**  
Mi contribución prevista se centra en programación gameplay, sistema de interacción, sigilo, detección de audio, combate limitado, rendimiento y estructura técnica.

## Documentación de diseño

El proyecto cuenta con un GDD completo:

- [`GDD_SOKAR_LaVenganzaDelMal.pdf`](./Media/Diagrams/GDD_SOKAR_LaVenganzaDelMal.pdf)

El documento recoge la presentación del proyecto, target, plataformas, referencias, elementos diferenciales, sinopsis, objetivos, mecánicas, dinámicas, estética, mundo, personajes, enemigos, objetos, historia, menús, controles, dificultad, sonido, producción y software previsto.

## Plataformas previstas

- PC
- PlayStation 5
- Xbox Series X

## Tecnologías previstas

- Unity
- C#
- Sistema de físicas 3D de Unity
- First Person Controller
- UI
- AudioSource
- Post Processing
- Lighting
- Blender
- Substance Painter
- Photoshop
- Visual Studio
- Git LFS
- GitHub

## Diseño documentado

- Terror 3D en primera persona.
- Público objetivo adulto.
- Protagonista: Daniel Hernández.
- Antagonista: Sokar, entidad demoníaca con rasgos humanos y caninos.
- Localización principal: casa familiar de los Hernández.
- Mundo dual entre realidad cotidiana y dimensión sobrenatural.
- Ambientación opresiva basada en casa abandonada, sótano, sombras, distorsión visual y sonido.
- Referencias principales: *Madison*, *Visage*, *Outlast* y *P.T.*
- Narrativa centrada en la muerte del Dr. Raúl Hernández, el diario del padre, la maldición familiar y la búsqueda de respuestas.
- Estética realista de terror psicológico con cambios dinámicos del entorno.
- GUI/HUD minimalista para favorecer la inmersión.
- Menú inicial integrado visualmente en una pared de la casa.

## Sistemas previstos

- `FirstPersonController` — movimiento en primera persona.
- `InteractionSystem` — interacción contextual con puertas, cajones, notas y objetos.
- `StealthSystem` — sigilo, escondites y comportamiento silencioso.
- `AudioDetectionSystem` — detección de sonido durante el modo furtivo.
- `FlashlightSystem` — linterna, iluminación, pistas ocultas y riesgo de detección.
- `DynamoRechargeSystem` — recarga manual de linterna mediante dinamo.
- `InventorySystem` — inventario limitado.
- `PuzzleSystem` — puzzles integrados en el entorno.
- `JumpscareManager` — sustos fijos y aleatorios.
- `SokarAI` — persecución, modo furtivo y estados de amenaza.
- `SaveLoadSystem` — nueva partida, cargar partida y progreso.
- `UIManager` — HUD minimalista, pausa, opciones y feedback de sonido.
- `SoundManager` — pasos, ambiente, demonio, impactos y tensión musical.
- `NarrativeManager` — diario, símbolos, rituales, diálogos y eventos narrativos.

## Mecánicas previstas

- Desplazamiento en primera persona.
- Interacción con objetos del entorno.
- Combate limitado con objetos improvisados.
- Sigilo y escondites.
- Inventario limitado.
- Reconocimiento del entorno mediante pistas visuales y auditivas.
- Linterna con energía limitada.
- Recarga de linterna con dinamo.
- Jumpscares aleatorios.
- Modo furtivo de Sokar.
- Detección de audio mediante medidor de sonido.
- Puzzle de candado numérico.
- Puzzle de viales.
- Búsqueda de llaves.
- Símbolos y rituales.
- Diario del padre como herramienta narrativa y de progresión.
- Coleccionables: notas, cartas, fotografías, artículos personales, grabadoras y huesos.
- Múltiples finales.
- Logros.

## Contenido pendiente de desarrollo

Actualmente el proyecto se encuentra en fase de concepto y documentación. No hay scripts, assets completos ni build jugable publicados.

Próximos pasos previstos:

- Crear prototipo base en Unity.
- Implementar controlador en primera persona.
- Implementar sistema de interacción.
- Implementar linterna y recarga con dinamo.
- Implementar inventario limitado.
- Implementar sistema de sigilo.
- Implementar detección de audio.
- Implementar modo furtivo de Sokar.
- Implementar jumpscares aleatorios.
- Implementar puzzles principales.
- Crear greybox de la casa familiar.
- Crear primera versión de la entidad Sokar.
- Añadir HUD minimalista.
- Crear sistema de guardado/carga.
- Preparar primera demo jugable.

## Visuales

> Existen imágenes conceptuales y de portada, pero el pack visual web final queda pendiente de consolidar.

Nombres previstos para el pack visual:

- `sokar-logo.png`
- `sokar-cover.png`
- `sokar-banner.png`
- `sokar-thumbnail-01-haunted-house.png`
- `sokar-thumbnail-02-sokar-entity.png`
- `sokar-thumbnail-03-flashlight-exploration.png`
- `sokar-thumbnail-04-stealth-mode.png`

## Build

Actualmente no hay una build pública disponible.

**Build próximamente.**

## Estado

**Concepto / GDD completo.**

El proyecto cuenta con documentación completa de diseño, narrativa, mecánicas, estética, personajes, enemigo principal, objetos, menús, controles, sonido, logros y planificación de producción.

## Aprendizajes

Este proyecto me permitió trabajar el diseño de un GDD completo para una experiencia de terror 3D.

También me sirvió para planificar mecánicas de sigilo, audio y exploración, así como sistemas de tensión basados en linterna, sonido, escondites y presencia enemiga.

Además, el proyecto me ayudó a diseñar una narrativa basada en misterio, diario, símbolos y maldición familiar, junto a puzzles integrados en el entorno.

Por último, permitió practicar el diseño de una UI minimalista orientada a inmersión y la planificación de un proyecto en equipo con roles de programación, FX y modelado.
