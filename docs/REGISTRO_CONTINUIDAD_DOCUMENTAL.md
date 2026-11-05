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



## Cambios documentales registrados — 2026-11-05 (segunda pasada)

| Repositorio | Archivo | Cambio aplicado | Commit | Verificación |
|---|---|---|---|---|
| hanzzel-social-bridge (privado) | CHECKPOINT.md | Se actualizó la fecha documental y se agregó una nota que separa v0.9.0 implementada en GitHub de las pruebas Linux, OAuth y permisos aún pendientes; se preservó el historial. | b6559e4 | Relectura exacta posterior: OK. |
| hanzzel-social-bridge (privado) | KIT_PRUEBAS_MANUALES.md | Se identificó explícitamente como kit histórico de v0.7.2/v0.7.3 y se remitió al checkpoint vigente para evitar usar cifras antiguas como estado actual. | f7291a4 | Relectura exacta posterior: OK. |
| hanzzel-social-bridge (privado) | CONTINUIDAD.md | Se marcó la nota v0.7.3 como antecedente histórico y se enlazó el estado actual al traspaso y checkpoint. | f72a83a | Relectura exacta posterior: OK. |
| H2O-quimicaVQE (privado) | CITATION.cff | Se retiraron un ORCID y un correo claramente de ejemplo; no se inventaron datos de contacto reales. | 2b17ef7 | Relectura exacta posterior: OK. |
| H2O-quimicaVQE (privado) | CHECKLIST.md | Se aclaró que el repositorio existe pero continúa privado; se eliminó la declaración «listo para publicar» mientras quedan controles sin marcar. | 9be7274 | Relectura exacta posterior: OK. |
| H2O-quimicaVQE (privado) | CHANGELOG.md | Se registraron los cambios documentales de esta pasada sin alterar la versión del software ni el historial de código. | dd49b60 | Relectura exacta posterior: OK. |
| ciel-bridge (privado) | README.md | Se corrigió la descripción «no contiene código fuente»: ahora distingue el canal privado del núcleo Ciel y enumera los scripts auxiliares visibles en `tools/` y la documentación. | 03725f7 | Relectura exacta posterior: OK. |

### Estado observado en esta pasada

- H2O-quimicaVQE sigue con visibilidad `private`; la conexión permite lectura y escritura de archivos, pero no expone una acción para cambiar la visibilidad del repositorio.
- Ciel Core: README y documentos de límites/ensayo consultados. No se encontraron contradicciones editoriales que justificaran una modificación en esta pasada. La carpeta `docs/` no contiene un `README.md` en la ruta consultada; no se creó uno por inferencia.
- Ciel Bridge: el README ahora refleja la existencia de herramientas auxiliares y mantiene la distinción respecto del núcleo Ciel Core.
- NavierStokes-CriticalFlow-Experiments: el README actual ya no contiene el texto de preparación «copiá y pegá» señalado en una observación anterior; no se aplicó un cambio adicional.



## Cambios y hallazgos documentales — 2026-11-05 (repositorios públicos)

| Repositorio | Archivo | Cambio o hallazgo | Commit | Verificación |
|---|---|---|---|---|
| AlertaTemprana | README.md | Se repararon caracteres de reemplazo visibles y un error ortográfico. Se aclaró que `config.py` aparece versionado pese a la regla de `.gitignore`, y se listaron como pendientes de revisión los archivos de runtime presentes en la raíz. | a24164d | Relectura exacta posterior: OK; cero caracteres U+FFFD en el README. |
| Experimento-9-Horizonte-Perceptivo | README.md | Se alineó el nombre de la carpeta del árbol documental con el nombre real del repositorio. La instrucción de instalación se corrigió a `cd Experimento-9-Horizonte-Perceptivo`, coincidente con la carpeta creada al clonar el repositorio. | c3423f0, f5526b7 | Relectura posterior: árbol y comando de instalación verificados; OK. |
| EllipticCurve-BSD-Engine | README.md | Se corrigió el nombre del archivo de ejecución: la ruta disponible es `BSD_Engine_v4.0-FULL.py`, cuyo encabezado interno identifica el motor como v4.1. Se conservó el nombre físico histórico. | 20296ff | Relectura exacta posterior: OK. |
| nubea | README.md | Se cerró el bloque Markdown que absorbía los apartados siguientes y se alineó el nombre del directorio del árbol con el repositorio. | 811a4cb | Relectura exacta posterior: OK. |

### Hallazgos pendientes de actuación

- **AlertaTemprana:** en la raíz pública aparecen `config.py`, `chat_id.json`, `ubicacion_usuario.json` y `clima_log.csv`, aunque el README los describe como archivos locales/de runtime y advierte no versionar `config.py`. No se inspeccionaron ni se eliminaron sus contenidos en esta pasada. Requiere revisión de privacidad y decisión explícita sobre retirar o conservar esos archivos; no asumir que `.gitignore` protege archivos ya versionados.
- **Experimento-9-Horizonte-Perceptivo:** el árbol ya muestra el nombre de repositorio correcto, pero el comando de instalación todavía usa `cd 9-ortogonalidad`. No se completó esa segunda corrección.
- **Experimento10_ResonanciaPhiSync:** los nombres de scripts referidos en la guía coinciden con archivos observados en la raíz. No se aplicaron cambios en esta pasada.
- **Blue Arrow, Observatorio.-Vivo y nubea:** se revisaron README; en Nubea se corrigió el bloque Markdown. Los demás quedan sujetos a revisión más profunda de rutas/archivos si se continúa la pasada completa.



## Cambios documentales registrados — 2026-11-05 (continuación de revisión)

| Repositorio | Archivo | Cambio aplicado | Commit | Verificación |
|---|---|---|---|---|
| Observatorio.-Vivo | README.md | Se corrigieron las rutas de instalación y estructura para usar el nombre real del repositorio; se corrigió el nombre del archivo de captura de brotes según el archivo existente `Bortes.png`. | b69dc22 | Relectura exacta posterior: OK. |
| Observatorio.-Vivo | README_EN.md | Se sustituyó el URL de clonación de ejemplo, se alineó el directorio con el repositorio real, se reconstruyó el árbol para eliminar entradas duplicadas y se reemplazó el correo de ejemplo por el canal de Issues. | d90e785 | Relectura exacta posterior: OK. |
| hanzzel-corp.github.io | README.md | Se amplió el árbol de archivos para incluir las carpetas y recursos presentes; se aclaró que los archivos de Umami están preparados pero inactivos con IDs vacíos; se corrigieron instrucciones para trabajar sobre el repositorio existente. | 551cf86, 043fe51 | Relecturas exactas posteriores: OK. |

### Discrepancias aún pendientes de resolución

- **Observatorio.-Vivo:** la versión del producto en español figura como v0.3.0 y el motor interno como v6.1.2; la documentación inglesa conserva un historial que llega a v6.1.3. No se eligió una versión por deducción. Hace falta identificar el estado/versionado vigente desde el registro de cambios o código antes de sincronizar ambas versiones.
- **Experimento-9-Horizonte-Perceptivo:** carpeta del árbol y comando de instalación alineados con el nombre real del repositorio.
- **H2O-quimicaVQE:** el README usa el nombre físico `Readme.md`; el repositorio contiene también `tests/README.md` y documentación de scripts. La cita ya no contiene los valores de contacto de ejemplo. La visibilidad permanece privada.
- **Portfolio:** la analítica sigue pospuesta y los archivos preparados permanecen inactivos mientras no se configuren IDs; no se activó ningún servicio ni se publicaron métricas.



## Actualización del índice maestro — 2026-11-05

- Se actualizó `docs/INDICE_MAESTRO_PROYECTOS.md` para fechar la pasada del 05/11/2026 y dejar constancia de que el inventario público no cambió; los repositorios privados siguen fuera del índice.
- Commit: `2bdd5ab`. Relectura exacta posterior: OK.



## Sincronización de versiones de Observatorio Vivo — 2026-11-05

- Se consultó el valor declarado por la aplicación en `app.py`: FastAPI title/version = `Observatorio Vivo v6.1.5` / `6.1.5`.
- Se actualizó el README español de motor interno v6.1.2 a v6.1.5 (commit `69a026e`).
- Se actualizó el README inglés para distinguir versión de producto v0.3.0 y motor v6.1.5 (commit `05ff625`). El historial inglés se marcó como parcial: no se inventaron notas para v6.1.4 ni v6.1.5.
- Ambas modificaciones fueron releídas y verificadas exactamente.

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
