ESCANER ISBN SBS -> EXCEL

Base: v5.1 corregida. v6 no se usa.

FUNCIONAMIENTO
1. Escanea un ISBN.
2. La app consulta el catálogo público de SBS por ISBN.
3. Si encuentra el libro, agrega una fila a la planilla local del navegador.
4. "Descargar Excel" genera libros-sbs.xlsx.
5. Los registros quedan guardados en localStorage para no perderlos al cerrar la página.

COLUMNAS
ISBN | Titulo | Autor | Editorial | Precio | URL | Fecha

IMPORTANTE
La página https://ag.sbs.com.ar/Home/Books es el panel autenticado de SBS. Esta versión usa el catálogo público de SBS para poder obtener los datos automáticamente desde una web/PWA sin pedir ni almacenar credenciales de SBS. Si un ISBN no está publicado en el catálogo público, la app abre el panel SBS como respaldo.

La consulta usa el endpoint público de búsqueda de productos de VTEX que utiliza la tienda SBS.
