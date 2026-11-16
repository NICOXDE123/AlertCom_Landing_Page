# AlertCom - Landing page

## Archivos
- `index.html`: estructura de la página y sección con capturas reales.
- `style.css`: estilos adaptables con la paleta oscura y dorada de AlertCom.
- `script.js`: menú móvil, animaciones y año automático.
- `assets/alertcom-mapa.jpeg`: captura de la pantalla principal y mapa.
- `assets/alertcom-seguridad.jpeg`: captura del aviso de seguridad vial.
- `assets/alertcom.apk`: aquí debes colocar el APK real cuando esté listo.

## Probar en tu computador
1. Descomprime el ZIP.
2. Abre `index.html` en Chrome o utiliza Visual Studio Code con Live Server.
3. Comprueba la sección “Vistas de la app” y el diseño en tamaño móvil.

## Agregar el APK
1. Copia el APK real de AlertCom dentro de `assets/`.
2. Renómbralo exactamente `alertcom.apk`.
3. La ruta debe quedar como `assets/alertcom.apk`.
4. Prueba el botón “Descargar aplicación”.

No publiques un APK de prueba ni compartas una compilación que no esté lista.

## Publicar en Render
1. Sube el contenido de esta carpeta a un repositorio de GitHub. Los archivos `index.html`, `style.css` y `script.js` deben quedar en la raíz del repositorio.
2. Entra a https://render.com/ e inicia sesión.
3. Selecciona **New + → Static Site** y conecta el repositorio.
4. Si los archivos están en la raíz, deja **Build Command** vacío y escribe `.` en **Publish Directory**.
5. Pulsa **Create Static Site** y espera que finalice la publicación.
6. Abre la URL `onrender.com` que entrega Render desde un computador y un celular.

## Importante
La landing page es independiente de la aplicación móvil. Publicar esta página no publica ni conecta automáticamente la app, la API Flask o la base de datos MySQL. Las capturas muestran pantallas de la aplicación, pero no son una conexión en vivo con ella.
