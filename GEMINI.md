# Reglas del Proyecto (Workspace Rules)

## Política de Verificación y Pruebas

- **Cambios pequeños o iterativos:**
  - **NO** ejecutar suites pesadas de pruebas automatizadas (Playwright end-to-end, `node e2e/run.js`) ni procesos largos de compilación nativa (`./gradlew assemble*`).
  - Aplicar las modificaciones directamente, cuidando la sintaxis y estilo de código de forma rápida y eficiente.
  - Responder de inmediato para agilizar el flujo de desarrollo.

- **Nuevas versiones o lanzamientos (Releases):**
  - La verificación exhaustiva (ejecución de pruebas e2e completas, verificación estática y compilación de APK) se realizará **únicamente** cuando se esté preparando una **nueva versión** formal del proyecto (release, versión mayor/menor, etc.).

