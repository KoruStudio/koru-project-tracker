# Seguimiento de Proyectos · KSVT

Herramienta de Koru Studio Visual Tools para llevar el avance de proyectos por cliente.

**Qué hace.** Organiza el trabajo en tres niveles: cliente → proyecto → tareas. El avance de cada proyecto es el número de tareas hechas sobre el total, y se recalcula cuando se añaden tareas nuevas. El avance de un cliente cuenta todas sus tareas juntas.

**Cómo se usa.**

1. Abre `index.html` con doble clic.
2. Pulsa «Empezar un archivo nuevo», añade un cliente, un proyecto y sus tareas.
3. Pulsa **Guardar** y elige dónde guardar `seguimiento-koru.json`.
4. La próxima vez, arrastra ese archivo a la herramienta o pulsa «Abrir archivo».

**Guardado en GitHub (recomendado).** Los datos se guardan en `seguimiento.json` dentro de un repositorio **privado** tuyo (por ejemplo `koru-datos`). La herramienta se conecta con una llave de acceso *fine-grained* limitada a ese repositorio, con el permiso «Contents: Read and write». La llave se recuerda solo en el navegador donde la pegaste. Cada cambio queda como una versión en el historial del repositorio. La herramienta se niega a conectar con un repositorio público.

**Dónde viven los datos sin GitHub.** En el archivo `.json` que tú guardas. Nada sale del navegador.

- En Chrome y Edge, después de guardar la primera vez los cambios se escriben solos en ese archivo.
- En Safari y Firefox el navegador no puede escribir en el disco: pulsa «Descargar archivo» al terminar y reemplaza el anterior.

Si guardas el archivo en una carpeta sincronizada (Google Drive, Dropbox, iCloud), lo tienes en todos tus equipos.

**Emoji por cliente.** Pulsa el cuadro junto al nombre para elegir uno, o escribe el nombre empezando por el emoji («🏦 Bancolombia»).

**Enlaces y urgentes.** Cada proyecto guarda los enlaces que abres siempre (Figma, Drive, brief). Cualquier tarea se puede marcar como urgente con el botón «!» que aparece al pasar el cursor.

**Atajos.** `Intro` añade la tarea y deja el campo listo para la siguiente. `Ctrl/Cmd + S` guarda. `Esc` deshace la edición de un nombre. `Alt + ↑ ↓` sobre un cliente cambia su orden.

## Créditos

Sin dependencias externas. Licencia MIT.
