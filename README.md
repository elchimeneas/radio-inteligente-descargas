# Radio Inteligente — SARP.es

Descargas de las ediciones **LSPD** y **LSSD** para Windows 10/11.
Cada ZIP contiene la aplicación portable, los sonidos y WebView2 local.
No hace falta instalar Python ni iniciar sesión en GitHub para usarla.

## Instalar

1. Abre las [descargas](https://github.com/elchimeneas/radio-inteligente-descargas/releases) y despliega **Assets**.
2. Descarga el ZIP completo de tu agencia: **Radio-Inteligente-LSPD-SARP.es-<versión>.zip** o **Radio-Inteligente-LSSD-SARP.es-<versión>.zip**.
3. Cierra cualquier radio abierta desde **Salir** en su icono de la bandeja de iconos de Windows, incluida la zona de iconos ocultos.
4. Extrae la carpeta completa donde prefieras; **recomiendo el Escritorio**. No ejecutes desde dentro del ZIP ni mezcles archivos de versiones distintas.
5. Abre **rintel-lspd.exe** o **rintel-lssd.exe**, según la edición. Conserva junto al ejecutable todas las carpetas incluidas. Sigue el tutorial para configurar tu indicativo y avisos; los cambios se guardan automáticamente.

Incluye la guía PDF, LEEME y licencias. No necesita instalador. Las versiones **beta / Pre-release** son entregas de prueba.

## Actualizar

- **Desde la aplicación:** la búsqueda automática avisa en Central; también puedes buscar desde Ajustes. Cierra GTA para descargar y actualizar/reiniciar. Solo descarga los componentes que cambian; tú decides cuándo instalar.
- **Mediante ZIP:** utiliza **Salir** en la bandeja y extrae la nueva carpeta completa. Puedes borrar la antigua tras conservar cualquier archivo personal añadido dentro. Ajustes e historiales se guardan por separado y se conservan. Si cambias la ubicación, actualiza los accesos directos y vuelve a aplicar Iniciar con Windows.
- Las versiones anteriores sin actualizador y las betas 2.2.0-beta1/beta2 necesitan el ZIP completo para pasar directamente a 2.2.0. Beta3 puede recibir la definitiva desde la aplicación.

## Qué es cada archivo

| Archivo | Uso |
|---|---|
| `Radio-Inteligente-LSPD-SARP.es-<versión>.zip` | Paquete completo para jugadores de LSPD. |
| `Radio-Inteligente-LSSD-SARP.es-<versión>.zip` | Paquete completo para jugadores de LSSD. Descarga solo la agencia que utilices. |
| `app-<hash>.zip` | Componente de aplicación para el actualizador; no se instala por separado. |
| `webview-<hash>.zip` | WebView2 local para el actualizador; ya está incluido en el ZIP completo. |
| `Source code (zip/tar.gz)` | Archivos automáticos de GitHub del repositorio de descargas. No contienen el proyecto privado ni una aplicación instalable. |
| `rintel-lspd.exe` / `rintel-lssd.exe` | Ejecutable principal de la agencia, dentro del ZIP completo. Es el único que abre el jugador. |
| `WebView2Runtime/.../msedgewebview2.exe` y auxiliares | Dependencias de Microsoft para mostrar la interfaz. No se abren manualmente. |
| Archivos `.dll` | Bibliotecas utilizadas por la aplicación y su interfaz; no se ejecutan por separado. |
| `ARCHIVOS.sha256` | Huellas de integridad de los archivos distribuidos. No es un programa ni hace falta abrirlo para jugar. |

`<hash>` identifica el contenido de un componente. No mezcles componentes ni los extraigas manualmente sobre otra versión. LSPD y LSSD conservan perfiles separados; solo puede ejecutarse una radio a la vez.

Este repositorio se dedica a la distribución; no contiene el proyecto de desarrollo.
Los catálogos de actualización están firmados. No se suben registros de jugadores.
Incidencias: mensaje por Discord a **elchimeneas**, indicando edición y versión.

## Aclaración de soporte del 27 de septiembre de 2026

El 27 de septiembre de 2026, el usuario confirma que los cierres al spectear procedían del servidor, no de Radio Inteligente ni de Dispatch. La incidencia queda cerrada sin cambios en la lógica de la radio. Las advertencias sobre esa investigación en los ZIP preparados previamente quedan sin efecto. Los archivos distribuidos se conservan con sus hashes originales.
