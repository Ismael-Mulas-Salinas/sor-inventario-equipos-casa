- **Alumno:** Ismael Mulas Salinas
- **Bloque:** B0.P03 · Casa · 
Inventario de equipos con Git y GitHub
- **Fase / ejercicio:** Fase
- **Fecha de inicio:** 25/10/2026
- **Fecha de entrega:** 26/10/2026

---

## 🎯 Qué se pedía
Lo que había que conseguir en esta práctica era crear un inventario de equipos desde cero aplicando control de versiones con Git y GitHub. En concreto, los objetivos principales eran:

Montar una bóveda y un repositorio limpios y bien aislados (fuera de OneDrive y SOR).

Guardar la evolución del inventario en tres versiones o commits distintos (el estado inicial, la actualización de equipos y una ampliación con fichas, criterios y archivos multimedia ignorados).

Consultar la primera versión del proyecto de manera histórica (mediante detached HEAD) sin romper ni perder el trabajo actual, y luego regresar a la rama principal.

Cerrar la bitácora y documentar todo el proceso en un cuarto commit documental.


## ⌨️ Comandos y pasos importantes

- `comando` — para qué sirve.

## 🛠️ Qué he hecho

Prerrequisitos y Preparación (H0 - H1)

H0: Me puse a revisar que Git estuviera al día, que mi usuario y mi correo fueran los correctos y que las claves SSH con GitHub funcionaran.

H1: Me armé la bóveda local de Boveda_Inventario_Casa bien apartada de OneDrive y de todo lo demás, creando solo las carpetas clave al principio.

Archivos Iniciales y Repositorio (H2 - H4)

H2: Dejé lista la bitácora, puse el .gitignore para esquivar los videos molestos, creé el README.md y armé el inventario/equipos.csv con los dos primeros equipos.

H3: Le eché un ojo a la ruta con el pwd y arranqué Git con la rama main dentro de 01_Proyecto.

H4: Me creé el repositorio vacío en GitHub llamado sor-inventario-equipos-casa y lo vinculé como mi origin.

Versiones del Producto (H5 - H7)

H5 (Primera versión): Mandé el add de los archivos iniciales, solté el primer commit ("Crear inventario inicial de equipos") y le metí el push a main.

H6 (Segunda versión): Actualicé el CSV cambiando al EQ01 de aula y al EQ02 a mantenimiento, guardé los cambios con el commit ("Actualizar ubicacion y estado de equipos") y tiré de push.

H7 (Tercera versión y ampliación):

Metí carpetas nuevas, la ficha del EQ02, el archivo de estados, el dibujo en PNG, el equipo EQ03 y actualicé el README.

Tiré un par de videos de prueba en la carpeta para comprobar que el .gitignore se los saltaba sin problema.

Preparé todo poco a poco, lancé el commit ("Ampliar inventario y documentar mantenimiento") y subí la tercera versión.

Consulta Histórica y Cierre (H7b - H8)

Consulta: Usé el comando del switch detach con el código del primer commit para chusmear cómo era antes el CSV y luego me regresé al main sin romper nada.

H8 (Video y Bitácora):

Apagué el OBS, guardé el video en su sitio y lo subí a YouTube (en oculto/no listado) a la playlist con sus 9 marcas de tiempo exactas.

Rellené del todo la bitácora con los links definitivos y me marqué un cuarto commit documental ("Completar bitacora y enlace del video de casa") con su respectivo push.

## 🚩 Qué me ha fallado y cómo lo he resuelto

los fallos cometidos han sido errores muy tontos y tendre que estar mas atento a ellos.

## 🤔 Respuestas a las preguntas
1. El repositorio está en 01_Proyecto porque así se mantiene organizado dentro de la bóveda y se evita controlar con Git archivos que no pertenecen al proyecto.

2. En la segunda versión cambié dos celdas de datos del archivo equipos.csv. En diff se ven las líneas modificadas: las antiguas aparecen con - y las nuevas con +.

3. Editar una fila modifica el archivo en el directorio de trabajo, mientras que usar git add prepara esos cambios para incluirlos en el siguiente commit.

4. La ficha nueva aparece en git status porque es un archivo nuevo sin seguimiento. No aparece en el diff de equipos.csv porque es un archivo independiente y no forma parte de ese CSV.

5. En la ampliación preparé individualmente los archivos modificados y nuevos que debían incluirse en el commit. Con git diff --cached pude comprobar los cambios que estaban preparados para confirmarse.

6. Comprobé que los clips existían revisando los archivos en su carpeta y verifiqué que estaban ignorados mediante git status y las reglas de .gitignore, sin añadirlos al repositorio.

7. Al visitar el primer commit recuperé la ubicación y el estado iniciales de los archivos. EQ03 volvió a mostrar los datos que tenía en esa versión histórica, por lo que los cambios posteriores dejaron de verse temporalmente.

8. Este CSV necesita historial para registrar los cambios, conocer versiones anteriores y recuperar datos modificados por error. Sin embargo, no ofrece por sí solo control de acceso, edición simultánea ni resolución automática de conflictos, como necesitaría un inventario multiusuario real.

9. Comprobé la subida de la bitácora revisando el estado del repositorio y verificando que el archivo estuviera incluido en el commit enviado al repositorio remoto. El cierre se realiza después del vídeo porque primero hay que completar y demostrar el procedimiento y después documentar y cerrar la actividad.

Nota: las respuestas describen el procedimiento habitual de Git. Para confirmar los nombres exactos de las dos celdas, los archivos preparados y los datos originales de EQ03, habría que revisar los cambios reales del proyecto.

## 🔗 Enlaces

- **Vídeo de esta fase:** https://youtu.be/kujK3RRFp5M
- **Playlist:** https://www.youtube.com/playlist?list=PLNEyCJwa3HJE
## 💭 Dudas / a repasar

esta todo claro pero cometo muchos errores
