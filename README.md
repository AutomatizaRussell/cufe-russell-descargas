# Cufe Russell — versiones publicadas (privado)

Versiones publicadas de **Cufe Russell**, la aplicación de escritorio para consultar documentos electrónicos en la DIAN, extraer sus datos y generar los reportes de impuestos.

Este repositorio es **privado** y **solo contiene los ejecutables publicados** (en Releases); el código fuente no está aquí.

## Cómo llegan las versiones a los usuarios

- Nadie descarga desde aquí. La aplicación inicia sesión con el usuario de **Conecta** y es Conecta quien consulta este repositorio con un token de solo lectura que vive únicamente en el servidor (`CUFE_RUSSELL_GITHUB_TOKEN`).
- Al abrir, si hay una versión más nueva, la app la ofrece, la descarga con un enlace temporal, verifica tamaño y SHA-256 y se reemplaza sola.
- Solo pueden usarla empleados activos de Conecta, con su primer ingreso hecho y con el permiso **"Puede usar Cufe Russell"**.

## Publicar una versión (solo administradores)

Desde la carpeta del proyecto:

```powershell
.\publicar-version.ps1 -Version 1.0.7-beta -Notas "Descripción de los cambios"
```

O desde la web: **Releases → Draft a new release**, etiqueta `v1.0.7-beta`, adjuntar el `.exe` y dejar marcado **Set as the latest release** (no marcar *pre-release*: la app solo ve la última versión marcada como *latest*).
