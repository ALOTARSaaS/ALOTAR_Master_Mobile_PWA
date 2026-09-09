ALOTAR MASTER MOBILE · PWA V1
==============================

ESTADO
- Prototipo independiente.
- Datos demostrativos.
- No conecta ni escribe en producción.

PARA PROBARLA COMO APP EN IPHONE
1. Publica esta carpeta completa en cualquier hosting HTTPS estático.
2. Abre la URL publicada en Safari (no desde el visor de archivos de ChatGPT).
3. Toca Compartir.
4. Selecciona "Añadir a pantalla de inicio".
5. Confirma "ALOTAR Master".
6. Abre el nuevo icono desde la pantalla de inicio.

ARCHIVOS
- index.html               Interfaz móvil V2.1 preparada para standalone.
- manifest.webmanifest     Configuración PWA.
- sw.js                    Caché/app shell.
- icons/                   Iconos para iPhone/PWA.

IMPORTANTE
- Para que service worker/manifest funcionen correctamente, debe servirse por HTTPS (o localhost durante desarrollo).
- Apps Script se mantendrá después como backend/API; esta PWA no incluye aún las credenciales ni acciones reales.

============================================================
ESTRUCTURA RECOMENDADA
============================================================

Mantén esta carpeta completa y separada del proyecto ALOTAR Booking System 1+.

ALOTAR_Master_Mobile_PWA/
  index.html
  manifest.webmanifest
  service-worker.js
  icons/
  README_INSTALAR.txt
  VERSION.txt

No mezcles estos archivos con Admin.html, Master.html ni archivos .gs de producción.

Para futuras versiones, conserva carpetas independientes:
  ALOTAR_Master_Mobile_PWA_V1
  ALOTAR_Master_Mobile_PWA_V2
  ALOTAR_Master_Mobile_PWA_V3

Esta V1 utiliza datos demostrativos y no ejecuta escrituras en producción.
