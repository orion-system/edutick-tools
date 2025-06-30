# EdutickUpdater

**EdutickUpdater** es una herramienta de actualización automática basada en manifiestos, desarrollada en C# (.NET). Permite verificar versiones remotas, validar integridad mediante hash y actualizar archivos locales desde fuentes definidas en un archivo de configuración JSON.

## Características

- Verificación de versión (`manifest_version`) y hash (`manifest_hash`)
- Consulta de versión remota vía API (`version_endpoint`)
- Descarga de archivos `.zip` y reemplazo de archivos locales (`target_path`)
- Modo seguro de ejecución (`--from-launcher`)
- Argumento opcional `--config` para utilizar archivos de configuración personalizados

## Uso

### Ejecución estándar

```
EdutickUpdater.exe --from-launcher
```

Utiliza `launcher_config.json` por defecto.

### Ejecución con configuración personalizada

```
EdutickUpdater.exe --from-launcher --config otro_config.json
```

## Nota

Si se ejecuta sin `--from-launcher`, la herramienta se cerrará automáticamente por seguridad.
