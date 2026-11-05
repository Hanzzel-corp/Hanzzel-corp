# Registro de continuidad documental — Hanzzel Corp

**Fecha de apertura:** 2026-11-04  
**Responsable institucional:** José Zamora — Investigador principal independiente.  
**Propósito:** conservar decisiones editoriales y cambios documentales para que el recorrido de los proyectos pueda reconstruirse en el futuro.

## Alcance y límites

Este registro trata exclusivamente sobre organización, consistencia y continuidad documental. No es una auditoría científica, matemática, de seguridad ni de código. No valida ni invalida resultados, hipótesis o experimentos.

- Preservar el contenido técnico y las afirmaciones originales.
- No reinterpretar resultados ni suavizar afirmaciones científicas por iniciativa editorial.
- Distinguir hechos documentados, nombres históricos, nombres actuales y datos pendientes.
- Mantener los repositorios privados y sus documentos fuera de la documentación pública.
- No inventar fechas, versiones, funcionalidades, resultados ni relaciones entre proyectos.
- Toda modificación debe hacerse con lectura previa, cambio acotado, commit identificable y verificación posterior.

## Cambios documentales registrados — 2026-11-04

| Repositorio | Archivo | Cambio aplicado | Verificación |
|---|---|---|---|
| telegram-ai-video-bot | README.md | Se corrigió el enlace de clonación Markdown y se cerró el bloque de código de ejecución. | Relectura posterior: contenido coincide con el cambio. |
| Cero-Absoluto-Simulation | README.md | Se reemplazó el usuario ficticio del enlace de clonación por la URL real del repositorio y se ordenó la sección de autoría sin quitar la atribución institucional. | Relectura posterior: contenido coincide con el cambio. |
| IA-video | README.md | Se aclaró que IA-video es el nombre del repositorio y SVD-TelegramBot ∑Δ el nombre del proyecto descrito. | Relectura posterior: contenido coincide con el cambio. |
| NavierStokes-CriticalFlow-Experiments | README.md | Se retiraron las instrucciones de preparación del archivo («versión final para subir» y «copiá y pegá…»), conservando el contenido técnico. | Relectura posterior: contenido coincide con el cambio. |
| NCT_MILENIO_SOLVER | README.md | Se aclaró la diferencia entre nombre del repositorio y nombre del motor; se corrigió el enlace de clonación. | Relectura posterior: contenido coincide con el cambio. |
| hanzzel-bot-builder | README.md | Se reemplazó la descripción mínima por una ficha prudente que identifica el propósito general y deja explícito qué alcance falta documentar. | Relectura posterior: contenido coincide con el cambio. |

| hanzzel-store | README.md | Se creó una guía raíz basada en el contenido existente de `llms.txt` y los archivos del sitio. Se documentó el flujo de compra tal como está publicado, sin afirmar checkout ni entrega automática. | Relectura posterior: contenido coincide con el cambio. |
| camino-cuaternario | README.md | Se creó una guía raíz basada en `index.html` y `data.json`. Se clasificó como iniciativa de recaudación, no como proyecto de investigación; no se inventó enlace de donación. | Relectura posterior: contenido coincide con el cambio. |

## Criterios de autoría

Cuando aparezcan variantes históricas de una firma, no eliminarlas automáticamente. Registrar la firma tal como aparece en el documento histórico y aclarar la identidad institucional actual únicamente cuando exista respaldo suficiente. No asumir que dos nombres son equivalentes sin contexto documental.

## Pendientes de continuidad

- Completar la lectura de los README restantes del inventario público.
- Revisar documentos internos de cada proyecto sin publicar contenido privado.
- Recuperar, cuando existan, checkpoints, changelogs, bitácoras y decisiones técnicas.
- Crear una ficha por proyecto con: propósito declarado, estructura documental, versiones registradas, estado expresamente documentado, hitos, decisiones y pendientes.
- Resolver discrepancias de nombres y versiones mediante documentos fuente, no por deducción.
- Revisar los repositorios cuyo README no estaba disponible en la primera lectura; no crear documentación sustitutiva sin inspeccionar sus archivos.

## Registro de futuras modificaciones

Agregar una entrada por cambio con fecha, repositorio, archivo, motivo, descripción precisa, commit y resultado de verificación. Si un dato no está disponible, consignarlo como «no documentado».

## Hallazgos de inventario — 2026-11-04

- `hanzzel-store` y `camino-cuaternario` no tenían `README.md` en la raíz. Se inspeccionaron sus archivos públicos antes de crear las guías raíz.
- `H2O-quimicaVQE` permanece privado. Su README se llama `Readme.md` (R mayúscula/minúsculas restantes), no `README.md`. El repositorio contiene documentación propia, changelog, checklist y archivos de proyecto. No se modificó ni se copió ningún contenido privado al índice público.
- La descripción del índice maestro para Camino Cuaternario se corrigió para reflejar su naturaleza de iniciativa de recaudación de fondos, según su página pública.


## Cambios documentales registrados — 2026-11-05

| Repositorio | Archivo | Cambio aplicado | Verificación |
|---|---|---|---|
| Cero-Absoluto-Simulation | README.md | Se unificó la sección de autoría y se eliminó la contradicción entre «proyecto institucional» y «proyecto individual». Se conservó la atribución a Hanzzel Corp y la dirección de investigación de José Zamora. | Verificado por relectura; commit 33016dd. |
| NCT_MILENIO_SOLVER | README.md | Se corrigió el comando de cambio de directorio posterior al clonado: ahora coincide con el nombre de carpeta creado por el repositorio. | Verificado por relectura; commit cd9d5d2. |

## Hallazgos adicionales — 2026-11-05

- telegram-ai-video-bot: el README actual tiene correctamente cerrados los bloques de código y el enlace de clonación está bien formado; no requiere el arreglo que se había señalado en un diagnóstico anterior.
- IA-video: el README ya distingue expresamente el nombre del repositorio (IA-video) del nombre del proyecto (SVD-TelegramBot ∑Δ); no requiere ese cambio.
- NCT_MILENIO_SOLVER: el README ya distingue el nombre del repositorio del nombre del motor (NCT Visual Engine). El problema concreto detectado era únicamente el comando cd de instalación.
- hanzzel-bot-builder: el README deja explícito que la descripción funcional y los pasos de uso están pendientes de documentar a partir de los archivos reales. No se añadieron funcionalidades por inferencia.
- El índice maestro y este registro de continuidad ya existen en Hanzzel-corp/Hanzzel-corp/docs/; no se recrearon.
