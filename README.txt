v5.1-excel-v3

1. Subí index.html a GitHub Pages (raíz del repositorio).
2. No hace falta service worker.
3. Escaneá un libro: el ISBN se agrega automáticamente a la lista local.
4. Escaneá otro libro para continuar.
5. Exportar Excel es la única acción que descarga el archivo.

Columnas: ISBN, Titulo, Autor, Editorial, Precio_SBS, SBS, Fecha.

Nota: SBS no expone públicamente desde el navegador un dato de precio que podamos leer de forma confiable; por eso Precio_SBS queda preparado pero vacío. La columna SBS conserva el acceso a la consulta.

Los datos se guardan en localStorage del navegador/dispositivo.
