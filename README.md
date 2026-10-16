# VDO Cntrl - Mellado

Developed by DhaxArts.

Control multicámara para OBS con VDO.Ninja, cámara local opcional y layouts exclusivos de Mellado.

## Descargar y actualizar

Descarga el archivo **VDO-Cntrl-Mellado-Actualizacion.zip** desde [Releases](https://github.com/dhaxarts/VDO-Cntrl/releases/latest).

Para una instalación Mellado existente: cierra OBS, extrae el ZIP completo y ejecuta **ACTUALIZAR.cmd**. Se verifican los archivos, se crea una copia de seguridad y se conservan ajustes y cámaras. Este ZIP es una actualización: requiere tener instalada la herramienta Mellado.

La versión 2026.10.16 incorpora las actualizaciones automáticas. Los usuarios anteriores deben instalar este primer paquete manualmente; las siguientes versiones firmadas se descargarán en segundo plano y se instalarán al cerrar OBS, si las opciones están activadas en Configuración > Actualizaciones. Windows puede solicitar autorización para sustituir una DLL protegida.

## Publicación

Cada release estable contiene tres archivos:

- `VDO-Cntrl-Mellado-Actualizacion.zip`: actualización acumulativa.
- `vdo-mellado-release.json`: versión, compatibilidad y hash del paquete.
- `vdo-mellado-release.sig`: firma Ed25519 verificada por el plugin.

No es necesario descargar los dos últimos archivos para actualizar manualmente. No se necesitan cuentas ni tokens de GitHub en los equipos de los usuarios.

Requiere OBS x64 31.1–32.x ya instalado. El actualizador no instala ni actualiza OBS. Esta distribución corresponde al fork Mellado.
