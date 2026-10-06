# Cufe Russell — descargas

Versiones publicadas de **Cufe Russell**, la aplicación de escritorio para consultar documentos electrónicos en la DIAN, extraer sus datos y generar los reportes de impuestos.

Este repositorio **solo contiene los ejecutables publicados** (en [Releases](../../releases)); el código fuente no está aquí.

## Descargar

Última versión (el enlace siempre apunta a la más reciente):

**https://github.com/AutomatizaRussell/cufe-russell-descargas/releases/latest/download/Cufe.Russell.Beta.exe**

- Requiere Windows 10/11 de 64 bits con Microsoft Edge WebView2 (incluido con Edge).
- La primera vez Windows puede mostrar "Windows protegió su PC": **Más información → Ejecutar de todas formas**.

## Actualizaciones

La aplicación revisa este repositorio al abrir. Si hay una versión más nueva, ofrece actualizar, la descarga, verifica que esté completa y se reemplaza sola. Nunca actualiza a mitad de una consulta.

## Publicar una versión (solo administradores)

Desde la carpeta del proyecto:

```powershell
.\publicar-version.ps1 -Version 1.0.7-beta -Notas "Descripción de los cambios"
```
