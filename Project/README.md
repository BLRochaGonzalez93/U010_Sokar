# U010_Sokar

[English](README.en.md) | [Español](README.md)

## Resumen

Concepto/GDD completo para una experiencia de terror 3D en primera persona. **SOKAR: La Venganza del Mal** plantea una aventura de terror psicológico donde Daniel Hernández vuelve a la casa familiar tras la muerte de su padre y queda atrapado entre una realidad cotidiana deteriorada y una dimensión sobrenatural ligada a una maldición.

El diseño se centra en una experiencia inmersiva basada en exploración, tensión, sonido, sigilo, linterna, puzzles y una entidad demoníaca impredecible.

## Colaboración

Proyecto conceptual desarrollado junto a **Hugo C.R.** y **Sergio M.C.**  
Mi contribución prevista se centra en programación gameplay, sistema de interacción, sigilo, detección de audio, combate limitado, rendimiento y estructura técnica.

## Documentación

- [`GDD_SOKAR_LaVenganzaDelMal.pdf`](./GDD_SOKAR_LaVenganzaDelMal.pdf)

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
- Historia de misterio y maldición familiar.
- Protagonista: Daniel Hernández.
- Enemigo principal: Sokar.
- Entorno principal: casa familiar de los Hernández.
- Mundo paralelo / dimensión sobrenatural.
- Casa deteriorada, opresiva y cambiante.
- Entidad demoníaca con rasgos humanos y caninos.
- Menú inicial integrado en una pared con manchas de sangre.
- HUD minimalista para mantener la inmersión.
- Controles previstos para gamepad y teclado/ratón.
- Curva de dificultad progresiva.
- Rejugabilidad mediante finales, secretos, coleccionables y logros.

## Sistemas previstos

- `FirstPersonController`
- `InteractionSystem`
- `StealthSystem`
- `AudioDetectionSystem`
- `FlashlightSystem`
- `DynamoRechargeSystem`
- `InventorySystem`
- `PuzzleSystem`
- `JumpscareManager`
- `SokarAI`
- `SaveLoadSystem`
- `UIManager`
- `SoundManager`
- `NarrativeManager`

## Mecánicas previstas

- Movimiento en primera persona.
- Exploración de la casa.
- Interacción con puertas, cajones, llaves, notas y objetos.
- Combate limitado con objetos del entorno.
- Sigilo, escondites y movimiento silencioso.
- Detección de audio en modo furtivo.
- Uso estratégico de linterna.
- Recarga manual con dinamo.
- Inventario limitado.
- Reconocimiento del entorno.
- Pistas visuales y auditivas.
- Puzzle de candado numérico.
- Puzzle de viales.
- Búsqueda de llaves.
- Símbolos y rituales.
- Coleccionables y grabadoras.
- Jumpscares aleatorios.
- Múltiples finales.
- Logros.

## Contenido pendiente de desarrollo

No existen scripts ni build jugable en esta fase. El proyecto se encuentra documentado como concepto y diseño completo.

Próximos pasos:

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

## Arquitectura prevista

La arquitectura inicial podría organizarse en:

- `Player` — controlador, cámara, input y movimiento.
- `Interaction` — objetos interactuables, puertas, cajones, llaves y notas.
- `Stealth` — escondites, agacharse, sonido y detección.
- `Sokar` — IA, persecución, modo furtivo y eventos.
- `Inventory` — ranuras, objetos usables y objetos clave.
- `Flashlight` — luz, energía, dinamo y consumo.
- `Puzzles` — candados, viales, símbolos y rituales.
- `Narrative` — diario, diálogos, escenas y eventos.
- `UI` — HUD, pausa, opciones, inventario y medidor de sonido.
- `Audio` — pasos, ambiente, sustos, demonio y música dinámica.
- `Save` — guardado, carga y progreso.

## Capturas

> Pendiente de añadir capturas finales.

Ruta prevista:

![Gameplay](./Media/screenshots/gameplay-01.png)

## Build

Actualmente no hay una release pública disponible.

**Build próximamente.**

## Estado

**Concepto / GDD completo.**

El proyecto dispone de documentación detallada, pero aún no se encuentra en fase de desarrollo jugable.

## Aprendizajes

Este proyecto me permitió diseñar un GDD completo para una experiencia de terror 3D.

También me ayudó a planificar sistemas de sigilo, audio y exploración, además de mecánicas de tensión basadas en linterna, sonido y escondites.

Además, permitió trabajar diseño narrativo mediante misterio, diario, símbolos, rituales y maldición familiar, junto a puzzles integrados en el entorno.

Por último, el proyecto sirvió para plantear una UI minimalista orientada a inmersión y una estructura de producción en equipo con roles de programación, FX y modelado.
