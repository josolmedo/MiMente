Se utiliza principalmente para crear archivos vacíos nuevos y actualizar las marcas de tiempo (fecha y hora de acceso o modificación) de archivos o directorios existentes.

- **Crear un archivo vacío:** `touch archivo.txt` (si no existe, lo crea).

- **Crear múltiples archivos:** `touch archivo1.txt archivo2.txt`.

- **Actualizar la fecha de modificación:** `touch archivo.txt` (si ya existe, actualiza la hora a la actual).

- **Cambiar solo la hora de acceso (-a):** `touch -a archivo.txt`.  

- **Cambiar solo la hora de modificación (-m):** `touch -m archivo.txt`.

- **Establecer una fecha específica (-t):** `touch -t YYYYMMDDHHMM.SS archivo.txt`.

- **Crear archivos sin actualizar la fecha (-c):** `touch -c archivo.txt` (no crea el archivo si no existe).