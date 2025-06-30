# 📦 CHANGELOG – EdutickUpdater

Todas las versiones listadas siguen el formato semver: `MAJOR.MINOR.PATCH`.

---

## [0.0.1] - 2025-06-27

🎉 Primer pre-release funcional de EdutickUpdater.

### Agregado:

- Validación de `manifest_version` y `manifest_hash` comparando contra manifest remoto.
- Verificación contra API externa para determinar versión actual (`version_endpoint`).
- Descarga y extracción de `.zip` desde URL definida.
- Reemplazo del ejecutable o archivo destino (`target_path`).
- Argumento `--from-launcher` para evitar ejecución directa indebida.
- **Nuevo argumento `--config`** para utilizar un archivo de configuración personalizado, permitiendo usar la herramienta en múltiples contextos y no solo como updater de launchers.

---

## 📁 Carpeta: `/EdutickUpdater/`

Este changelog solo cubre esta herramienta. Otras herramientas del repositorio deben incluir su propio `CHANGELOG.md` dentro de su respectiva carpeta.

📦 Release disponible en:  
🔗 [https://github.com/orion-system/edutick-tools/releases/tag/edutick-updater-v0.0.1](https://github.com/orion-system/edutick-tools/releases/tag/edutick-updater-v0.0.1)
