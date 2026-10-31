PROYECTO ANDROID — streamingcolombiasm

Incluye:
- app/src/main/assets/index.html: panel web empaquetado dentro de la app.
- Proyecto Android WebView que abre file:///android_asset/index.html.
- .github/workflows/build-apk.yml: compilación automática de APK de prueba con GitHub Actions.

COMPILAR DESDE GITHUB USANDO SOLO ANDROID:
1. Crea un repositorio nuevo en GitHub, por ejemplo streamingcolombiasm-apk.
2. Descomprime este ZIP en el teléfono usando el administrador de archivos.
3. Sube TODO el contenido y carpetas del proyecto al repositorio, conservando la estructura (incluida la carpeta oculta .github/workflows). No subas el ZIP como único archivo.
4. Cuando el proyecto esté en la rama main, abre la pestaña Actions del repositorio.
5. Abre "Build streamingcolombiasm APK" y pulsa "Run workflow".
6. Espera a que termine con marca verde.
7. En la ejecución, baja a Artifacts y descarga "streamingcolombiasm-apk".
8. Extrae el ZIP del artefacto; dentro estará app-debug.apk. Toca el APK para instalarlo.

IMPORTANTE:
- Es una APK debug para pruebas, no una APK firmada para publicación en Play Store.
- Los datos se guardan localmente en el celular. Exporta copias desde Ajustes.
- El bloqueo por clave es básico; no cifra ni sincroniza los datos.
- Los avisos de WhatsApp se preparan para envío manual; no se envían solos.
