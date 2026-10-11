# Leon Edits – Compresor de video (APK)

Cómo obtener tu APK sin instalar nada en tu PC:

1. Crea una cuenta gratis en github.com y un repositorio nuevo (privado o público).
2. Sube TODO el contenido de esta carpeta (incluida la carpeta oculta .github).
3. Ve a la pestaña Actions > "Build APK" > Run workflow. Si ya subiste a la rama main, arranca solo.
4. Espera unos 5-8 minutos. Al terminar, abre la ejecución y descarga "LeonEdits-APK" (un zip con app-debug.apk).
5. Pasa el APK al teléfono, ábrelo y permite "Instalar apps desconocidas".

Alternativa: con Android Studio, ejecuta
  npm install
  (copia react.production.min.js, react-dom.production.min.js y htm.umd.js a www/vendor)
  npx cap add android && npx cap sync android && npx cap open android
