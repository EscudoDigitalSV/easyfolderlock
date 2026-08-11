# <img src="https://escudodigitalsv.com/favicon.ico" width="32" height="32"> EasyFolderLock Free

> ## 🔐 Cifrado Seguro de Carpetas y Generación de Archivos .lock para Windows
>
> **EasyFolderLock Free** es una herramienta para Windows diseñada para proteger carpetas de forma sencilla. La aplicación comprime la carpeta, cifra su contenido y genera un único archivo `.lock` protegido mediante contraseña.
>
> Ideal para usuarios que necesitan una forma rápida, eficiente y segura de proteger su información personal o profesional sin complicaciones.

---

# ✨ Características Principales

EasyFolderLock Free incluye las funciones esenciales de bloqueo, cifrado y restauración de carpetas:

* 🔐 **Cifrado AES-GCM:** Protección robusta de alta seguridad para tu información.
* 🔑 **Protección mediante Contraseña:** Acceso restringido únicamente mediante clave definida por el usuario.
* 🧂 **Salt Aleatorio:** Utilizado para la derivación segura de claves de cifrado.
* 🔢 **Nonce Aleatorio:** Generado de forma única para cada operación de cifrado.
* 📦 **Compresión ZIP:** Reduce el tamaño de la carpeta antes de iniciar el proceso de cifrado.
* 🗃️ **Formato .lock (EFL1):** Estructura de archivo interna *EasyFolderLock Format 1*.
* 🔄 **Bloqueo y Desbloqueo Flexibles:** Restauración en la ubicación original o en una nueva carpeta.
* 🖱️ **Soporte Drag & Drop:** Arrastrar y soltar carpetas y archivos `.lock` para operar rápidamente.
* 🔎 **Búsqueda Integrada:** Localiza archivos `.lock` fácilmente en tu sistema.
* 📁 **Desbloqueo Múltiple:** Procesamiento de varios archivos protegidos.
* 👻 **Ocultar Archivos `.lock`:** Opción para invisibilizar archivos protegidos en Windows.
* 💾 **Copia de Seguridad:** Opción para conservar la carpeta original tras el bloqueo.
* 📊 **Barra de Progreso y Registro:** Monitoreo visual y *log* detallado de operaciones.
* 🇪🇸 **Interfaz en Español:** Diseñada para ser clara, intuitiva y fácil de usar.

---

# 🔒 ¿Cómo funciona?

### 📥 Proceso de Bloqueo
Aquí tienes los dos archivos `README.md` actualizados según todas tus indicaciones.

Se ha eliminado todo lo referente a **licencias**, **lenguajes de programación/librerías** (Python, PyQt5, cryptography), se ha adaptado la **tabla de requisitos del sistema** idéntica a la plantilla de referencia, se mantiene la **tabla comparativa con los botones visuales**, y se incorporaron las secciones de **Nota de Seguridad** e **Instalación y Advertencia de Windows SmartScreen** adaptadas a EasyFolderLock.

---

# 1. `README.md` — EasyFolderLock Free

```markdown
# <img src="https://escudodigitalsv.com/favicon.ico" width="32" height="32"> EasyFolderLock Free

> ## 🔐 Cifrado Seguro de Carpetas y Generación de Archivos .lock para Windows
>
> **EasyFolderLock Free** es una herramienta para Windows diseñada para proteger carpetas de forma sencilla. La aplicación comprime la carpeta, cifra su contenido y genera un único archivo `.lock` protegido mediante contraseña.
>
> Ideal para usuarios que necesitan una forma rápida, eficiente y segura de proteger su información personal o profesional sin complicaciones.

---

# ✨ Características Principales

EasyFolderLock Free incluye las funciones esenciales de bloqueo, cifrado y restauración de carpetas:

* 🔐 **Cifrado AES-GCM:** Protección robusta de alta seguridad para tu información.
* 🔑 **Protección mediante Contraseña:** Acceso restringido únicamente mediante clave definida por el usuario.
* 🧂 **Salt Aleatorio:** Utilizado para la derivación segura de claves de cifrado.
* 🔢 **Nonce Aleatorio:** Generado de forma única para cada operación de cifrado.
* 📦 **Compresión ZIP:** Reduce el tamaño de la carpeta antes de iniciar el proceso de cifrado.
* 🗃️ **Formato .lock (EFL1):** Estructura de archivo interna *EasyFolderLock Format 1*.
* 🔄 **Bloqueo y Desbloqueo Flexibles:** Restauración en la ubicación original o en una nueva carpeta.
* 🖱️ **Soporte Drag & Drop:** Arrastrar y soltar carpetas y archivos `.lock` para operar rápidamente.
* 🔎 **Búsqueda Integrada:** Localiza archivos `.lock` fácilmente en tu sistema.
* 📁 **Desbloqueo Múltiple:** Procesamiento de varios archivos protegidos.
* 👻 **Ocultar Archivos `.lock`:** Opción para invisibilizar archivos protegidos en Windows.
* 💾 **Copia de Seguridad:** Opción para conservar la carpeta original tras el bloqueo.
* 📊 **Barra de Progreso y Registro:** Monitoreo visual y *log* detallado de operaciones.
* 🇪🇸 **Interfaz en Español:** Diseñada para ser clara, intuitiva y fácil de usar.

---

# 🔒 ¿Cómo funciona?

### 📥 Proceso de Bloqueo
```text
Carpeta ➔ Compresión ZIP ➔ Cifrado AES-GCM ➔ Archivo protegido (.lock)

```

### 📤 Proceso de Desbloqueo

```text
Archivo .lock ➔ Contraseña ➔ Descifrado ➔ Descompresión ➔ Carpeta restaurada

```

---

# 🛡️ Formato Interno EFL1

Los archivos generados por EasyFolderLock utilizan una estructura interna protegida:

$$\text{EFL1} + \text{Salt} + \text{Nonce} + \text{Datos cifrados}$$

* **`EFL1`**: Identificador exclusivo de formato (*EasyFolderLock Format 1*).
* **Extensión de archivo:** `.lock` (Ejemplos: `Documentos.lock`, `Fotos.lock`, `Proyectos.lock`).

---

# 💎 Comparativa y Descarga

---

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
> Debido a este comportamiento técnico y al uso de algoritmos de cifrado de bajo nivel, algunos antivirus o soluciones de seguridad pueden mostrar alertas preventivas o falsos positivos.

> [!NOTE]
> EasyFolderLock es un proyecto independiente en constante evolución.
> Esta primera versión oficial aún no cuenta con una firma digital de código (Code Signing Certificate), por lo que Windows SmartScreen puede mostrar advertencias preventivas al ejecutar el archivo descargado.
> Estas advertencias forman parte de las medidas de seguridad estándar de Windows y no indican la presencia de software malicioso.
> La incorporación de firma digital se encuentra prevista para futuras versiones del proyecto.

---

# 📥 Instalación y Advertencia de Windows SmartScreen

> [!IMPORTANT]
> Al descargar EasyFolderLock, Windows puede mostrar la advertencia **"Windows protegió tu PC"**.
> Este comportamiento es normal cuando una aplicación descargada desde Internet aún no dispone de una firma digital reconocida por Microsoft.

### Pasos para continuar

1. Haz clic en **Más información**.
2. Haz clic en **Ejecutar de todas formas**.
3. Continúa con la instalación normalmente.

> [!TIP]
> Este procedimiento generalmente solo es necesario la primera vez que se ejecuta el instalador.

---

# 📦 Requisitos del Sistema

| Requisito | Mínimo |
| --- | --- |
| Sistema Operativo | Windows 10 / 11 |
| Arquitectura | x64 |
| RAM | 2 GB |
| Espacio en Disco | 100 MB |
| Almacenamiento | Unidad Local (NTFS / FAT32) |
| Internet | No requerido |

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

## 🌐 Escudo Digital SV

Desarrollado por **Escudo Digital SV**

🌐 Sitio web oficial: [escudodigitalsv.com](https://escudodigitalsv.com)

© 2026 Escudo Digital SV. Todos los derechos reservados.

---

# 2. `README.md` — EasyFolderLock Pro

```markdown
# <img src="https://escudodigitalsv.com/favicon.ico" width="32" height="32"> EasyFolderLock Pro

> ## 🔐 Protección Avanzada de Carpetas mediante Cifrado Seguro para Windows
>
> **EasyFolderLock Pro** es la versión avanzada de EasyFolderLock, diseñada para usuarios y entornos profesionales que necesitan funciones adicionales de seguridad, integraciones con el sistema operativo y herramientas avanzadas para proteger, administrar y restaurar sus carpetas de forma ágil y cómoda.
>
> Comprime, cifra y empaqueta tus directorios en un archivo único `.lock` protegido mediante cifrado de grado militar.

---

# ✨ Características Principales

EasyFolderLock Pro incluye todas las funciones de la versión Free y añade herramientas avanzadas de administración e integración:

### 🔐 Protección Criptográfica
* **Cifrado AES-GCM:** Protección simétrica de alta seguridad para la confidencialidad e integridad de tus datos.
* **Derivación Robusta:** Uso de **Salt** y **Nonce** aleatorios por cada operación de cifrado.
* **Formato EFL1:** Estructura de contenedor propia (*EasyFolderLock Format 1*) con verificación de integridad.
* **Protección Anti-sobrescritura:** Previene pérdidas accidentales durante el proceso de restauración.
* **Compresión ZIP Integrada:** Optimiza el espacio comprimiendo los archivos antes de cifrarlos.

### 📂 Administración de Archivos y Menú Contextual
* **Integración con Windows:** Opción para bloquear carpetas y desbloquear archivos `.lock` directamente desde el menú contextual del Explorador de Windows.
* **Asociación de Archivos:** Apertura directa e integración nativa con archivos `.lock`.
* **Arrastrar y Soltar (Drag & Drop):** Soporte intuitivo para cargar carpetas y contenedores al instante.
* **Operaciones Múltiples:** Bloqueo y desbloqueo simultáneo de varios archivos `.lock`.
* **Modo Invisible:** Opción para ocultar archivos `.lock` en el Explorador de Windows.

### ⚡ Funciones Avanzadas Pro
* **Bloqueo Rápido:** Procesa y protege tus datos con un solo clic.
* **Cofres Seguros y Historial:** Monitoreo y registro detallado de operaciones realizadas.
* **Verificación Avanzada:** Comprobación de integridad del archivo antes de la extracción.
* **Modo Portable:** Ejecución flexible en unidades extraíbles.

---

# 🔒 ¿Cómo funciona?

### 📥 Proceso de Bloqueo
```text
Carpeta ➔ Compresión ZIP ➔ Cifrado AES-GCM ➔ Archivo protegido (.lock)

```

### 📤 Proceso de Desbloqueo

```text
Archivo .lock ➔ Contraseña ➔ Verificación ➔ Descifrado ➔ Carpeta restaurada

```

---

# 🛡️ Formato Interno EFL1

Los archivos protegidos por EasyFolderLock Pro utilizan una estructura de contenedor estructurada:

$$\text{EFL1} + \text{Salt} + \text{Nonce} + \text{Datos cifrados}$$

* **`EFL1`**: Cabecera identificadora de formato (*EasyFolderLock Format 1*).
* **Extensión nativa:** `.lock` (Ejemplos: `Documentos.lock`, `Proyectos.lock`, `Fotos.lock`).

---

# 💎 Comparativa y Descarga

---

---

# 🚀 Modo de Uso

### Bloquear una Carpeta

1. Haz clic derecho sobre una carpeta y selecciona **Bloquear con EasyFolderLock Pro** (o ábrela desde la app).
2. Ingresa y confirma tu contraseña.
3. Configura las opciones avanzadas (conservar copia, ocultar `.lock`, etc.).
4. Presiona **Bloquear**.

### Desbloquear una Carpeta

1. Haz doble clic en el archivo `.lock` o selecciónalo en la aplicación.
2. Ingresa tu contraseña.
3. Elige la carpeta de destino para restaurar los archivos y confirma.

---

# ⚠️ Nota de Seguridad

> [!CAUTION]
> EasyFolderLock Pro interactúa directamente con el sistema de archivos de Windows para realizar el cifrado en tiempo real y la protección de datos.
> Debido a este comportamiento técnico y al uso de algoritmos de cifrado de bajo nivel, algunos antivirus o soluciones de seguridad pueden mostrar alertas preventivas o falsos positivos.

> [!NOTE]
> EasyFolderLock Pro es un proyecto independiente en constante evolución.
> Esta versión oficial aún no cuenta con una firma digital de código (Code Signing Certificate), por lo que Windows SmartScreen puede mostrar advertencias preventivas al ejecutar el archivo descargado.
> Estas advertencias forman parte de las medidas de seguridad estándar de Windows y no indican la presencia de software malicioso.
> La incorporación de firma digital se encuentra prevista para futuras versiones del proyecto.

---

# 📥 Instalación y Advertencia de Windows SmartScreen

> [!IMPORTANT]
> Al descargar EasyFolderLock Pro, Windows puede mostrar la advertencia **"Windows protegió tu PC"**.
> Este comportamiento es normal cuando una aplicación descargada desde Internet aún no dispone de una firma digital reconocida por Microsoft.

### Pasos para continuar

1. Haz clic en **Más información**.
2. Haz clic en **Ejecutar de todas formas**.
3. Continúa con la instalación normalmente.

> [!TIP]
> Este procedimiento generalmente solo es necesario la primera vez que se ejecuta el instalador.

---

# 📦 Requisitos del Sistema

| Requisito | Mínimo |
| --- | --- |
| Sistema Operativo | Windows 10 / 11 |
| Arquitectura | x64 |
| RAM | 2 GB |
| Espacio en Disco | 100 MB |
| Almacenamiento | Unidad Local (NTFS / FAT32) |
| Internet | No requerido |

---

# 🐛 Reportar un Problema

Si encuentras un error o comportamiento inesperado, puedes abrir un **Issue** indicando:

* Versión de EasyFolderLock Pro
* Versión de Windows
* Pasos para reproducir el problema
* Mensaje de error
* Captura de pantalla, si es necesario

> [!IMPORTANT]
> Nunca publiques contraseñas ni archivos `.lock` que contengan información personal.

---

## 🌐 Escudo Digital SV

Desarrollado por **Escudo Digital SV**

🌐 Sitio web oficial: [escudodigitalsv.com](https://escudodigitalsv.com)

© 2026 Escudo Digital SV. Todos los derechos reservados.
```text
Carpeta ➔ Compresión ZIP ➔ Cifrado AES-GCM ➔ Archivo protegido (.lock)
