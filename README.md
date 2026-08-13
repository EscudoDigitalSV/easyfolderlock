# <img src="https://i.servimg.com/u/f34/20/32/08/60/easyfo10.png" width="32" height="32"> EasyFolderLock

> ## 🔐 Cifrado Seguro de Carpetas y Generación de Archivos .lock para Windows
>
> **EasyFolderLock** es una herramienta para Windows diseñada para proteger carpetas de forma sencilla. La aplicación comprime la carpeta, cifra su contenido y genera un único archivo `.lock` protegido mediante contraseña.
>
> Ideal para usuarios que necesitan una forma rápida, eficiente y segura de proteger su información personal o profesional sin complicaciones.

---

# ✨ Características Principales

EasyFolderLock incluye las funciones esenciales de bloqueo, cifrado y restauración de carpetas:

* 🔐 **Cifrado AES-GCM:** Protección robusta de alta seguridad para tu información.
* 🔑 **Protección mediante Contraseña:** Acceso restringido únicamente mediante clave definida por el usuario.
* 🧂 **Salt Aleatorio:** Utilizado para la derivación segura de claves de cifrado.
* 🔢 **Nonce Aleatorio:** Generado de forma única para cada operación de cifrado.
* 📦 **Compresión ZIP:** Reduce el tamaño de la carpeta antes de iniciar el proceso de cifrado.
* 🗃️ **Formato .lock (EFL1):** Estructura de archivo interna EasyFolderLock Format 1.
* 🔄 **Bloqueo y Desbloqueo Flexibles:** Restauración en la ubicación original o en una nueva carpeta.
* 🖱️ **Soporte Drag & Drop:** Arrastrar y soltar carpetas y archivos `.lock` para operar rápidamente.
* 🔎 **Búsqueda Integrada:** Localiza archivos `.lock` fácilmente en tu sistema.
* 📁 **Desbloqueo Múltiple:** Procesamiento de varios archivos protegidos.
* 👻 **Ocultar Archivos `.lock`:** Opción para invisibilizar archivos protegidos en Windows.
* 💾 **Copia de Seguridad:** Opción para conservar la carpeta original tras el bloqueo.
* 📊 **Barra de Progreso y Registro:** Monitoreo visual y log detallado de operaciones.
* 🇪🇸 **Interfaz en Español:** Diseñada para ser clara, intuitiva y fácil de usar.

---

# 🔒 ¿Cómo funciona?

### 📥 Proceso de Bloqueo
Carpeta ➔ Compresión ZIP ➔ Cifrado AES-GCM ➔ Archivo protegido (.lock)

### 📤 Proceso de Desbloqueo
Archivo .lock ➔ Contraseña ➔ Descifrado ➔ Descompresión ➔ Carpeta restaurada

---

# 🛡️ Formato Interno EFL1

Los archivos generados por EasyFolderLock utilizan una estructura interna protegida:

EFL1 + Salt + Nonce + Datos cifrados

* **EFL1**: Identificador exclusivo de formato (EasyFolderLock Format 1).
* **Extensión de archivo:** `.lock` (Ejemplos: `Documentos.lock`, `Fotos.lock`, `Proyectos.lock`).

---

# 💎 Comparativa y Descarga

<table>
<tr>
<th>Funciones</th>
<th>🆓 Gratis (Free)</th>
<th>⭐ Versión Pro</th>
</tr>

<tr>
<td>Cifrado AES-GCM</td>
<td align="center">✅</td>
<td align="center">✅</td>
</tr>

<tr>
<td>Protección mediante contraseña</td>
<td align="center">✅</td>
<td align="center">✅</td>
</tr>

<tr>
<td>Salt y Nonce aleatorio</td>
<td align="center">✅</td>
<td align="center">✅</td>
</tr>

<tr>
<td>Compresión ZIP previa</td>
<td align="center">✅</td>
<td align="center">✅</td>
</tr>

<tr>
<td>Formato .lock (EFL1)</td>
<td align="center">✅</td>
<td align="center">✅</td>
</tr>

<tr>
<td>Ocultar archivos .lock</td>
<td align="center">✅</td>
<td align="center">✅</td>
</tr>

<tr>
<td>Soporte Drag & Drop y búsqueda</td>
<td align="center">✅</td>
<td align="center">✅</td>
</tr>

<tr>
<td>Integración con el Menú Contextual de Windows</td>
<td align="center">❌</td>
<td align="center">✅</td>
</tr>

<tr>
<td>Bloqueo rápido & Herramientas avanzadas</td>
<td align="center">❌</td>
<td align="center">✅</td>
</tr>

<tr>
<td><b>Duración / Acceso</b></td>
<td align="center"><b>GRATIS</b></td>
<td align="center"><b>PARA SIEMPRE</b></td>
</tr>

<tr>
<td><b>Acción</b></td>

<td align="center">
<a href="https://escudodigitalsv.com">
<img src="https://img.shields.io/badge/PROBAR_GRATIS-blue?style=for-the-badge&logo=windows11&logoColor=white">
</a>
</td>

<td align="center">
<a href="https://escudodigitalsv.com">
<img src="https://img.shields.io/badge/🛒_COMPRAR_AHORA-escudodigitalsv.com-blue?style=for-the-badge">
</a>
</td>

</tr>

</table>

---

<p align="center">
  <a href="https://escudodigitalsv.com">
    <img src="https://img.shields.io/github/downloads/escudodigitalsv/easyfolderlock/total?style=for-the-badge&color=28a745&logo=github" alt="Descargas">
  </a>
</p>

---

# 🚀 Modo de Uso

### Bloquear una Carpeta
1. Selecciona una carpeta en la aplicación (o arrástrala).
2. Introduce y confirma tu contraseña.
3. Decide si deseas conservar una copia de la carpeta original.
4. Presiona **Bloquear**. Se generará un archivo `.lock`.

### Desbloquear una Carpeta
1. Selecciona o arrastra el archivo `.lock`.
2. Introduce la contraseña correcta.
3. Elige la ruta de destino donde deseas restaurar los datos.
4. Presiona **Desbloquear**.

---

# ⚠️ Nota de Seguridad

> [!CAUTION]
> EasyFolderLock interactúa directamente con el sistema de archivos de Windows para realizar el cifrado en tiempo real y la protección de datos.
>
> Debido a este comportamiento técnico y al uso de algoritmos de cifrado de bajo nivel, algunos antivirus o soluciones de seguridad pueden mostrar alertas preventivas o falsos positivos.

> [!NOTE]
> EasyFolderLock es un proyecto independiente en constante evolución.
>
> Esta primera versión oficial aún no cuenta con una firma digital de código (Code Signing Certificate), por lo que Windows SmartScreen puede mostrar advertencias preventivas al ejecutar el archivo descargado.
>
> Estas advertencias forman parte de las medidas de seguridad estándar de Windows y no indican la presencia de software malicioso.
>
> La incorporación de firma digital se encuentra prevista para futuras versiones del proyecto.

---

# 📥 Instalación y Advertencia de Windows SmartScreen

> [!IMPORTANT]
> Al descargar EasyFolderLock, Windows puede mostrar la advertencia **"Windows protegió tu PC"**.
>
> Este comportamiento es normal cuando una aplicación descargada desde Internet aún no dispone de una firma digital reconocida por Microsoft.

### Pasos para continuar

1. Haz clic en **Más información**.
2. Haz clic en **Ejecutar de todas formas**.
3. Continúa con la instalación normalmente.

<div align="center">

<img src="https://github.com/escudodigitalsv/applockerpro/blob/aea72c6f141e471c3751d2afb4370da7f3b25cf3/img/SmartScreen.gif" alt="Cómo ejecutar EasyFolderLock" width="250">

</div>

> [!TIP]
> Este procedimiento generalmente solo es necesario la primera vez que se ejecuta el instalador.

---

# 📦 Requisitos del Sistema

| Requisito         | Mínimo          |
| :---------------- | :-------------- |
| Sistema Operativo | Windows 10 / 11 |
| Arquitectura      | x64             |
| RAM               | 2 GB            |
| Espacio en Disco  | 100 MB          |
| Almacenamiento    | Unidad Local (NTFS / FAT32) |
| Internet          | No requerido    |

---

# 🐛 Reportar un Problema

Si encuentras un error o comportamiento inesperado, puedes abrir un **Issue** indicando:
* Versión de EasyFolderLock
* Versión de Windows
* Pasos para reproducir el problema
* Mensaje de error
* Captura de pantalla, si es necesario

> [!IMPORTANT]
> Nunca publiques contraseñas ni archivos `.lock` que contengan información personal.

---

<div align="center">

## 🌐 Escudo Digital SV

Desarrollado por **Escudo Digital SV**  
🌐 Sitio web oficial: [escudodigitalsv.com](https://escudodigitalsv.com)

© 2026 Escudo Digital SV. Todos los derechos reservados.

</div>
