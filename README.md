# Recargas Castor Park (Android)

Aplicación Android nativa que abre `https://recargas.castorpark.com/app/` en un WebView.

## Funciones

- JavaScript, almacenamiento web y cookies.
- Navegación atrás dentro del historial web.
- Selector de archivos, permisos de cámara/micrófono/ubicación y descargas.
- Apertura de enlaces externos (`tel:`, `mailto:`, aplicaciones, etc.).
- Conserva el estado del WebView al girar o recrear la actividad.
- No implementa vídeo a pantalla completa.
- No mantiene la pantalla encendida ni altera el tiempo de apagado.

## Compilar

Abre la carpeta raíz en Android Studio (JDK 17) y usa **Build > Build APK(s)**.
El APK se generará en `app/build/outputs/apk/debug/app-debug.apk`.
