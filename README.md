#  EasyFolderLock Free

> ## 🔐 Cifrado Seguro de Carpetas y Generación de Archivos .lock para Windows
> 
> 
> **EasyFolderLock Free** es una herramienta para Windows diseñada para proteger carpetas de forma sencilla. La aplicación comprime la carpeta, cifra su contenido y genera un único archivo `.lock` protegido mediante contraseña.
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

# 💎 Comparativa de Versiones

| Función | 🆓 EasyFolderLock Free | ⭐ EasyFolderLock Pro |
| --- | --- | --- |
| Cifrado AES-GCM | ✅ | ✅ |
| Formato `.lock` (EFL1) | ✅ | ✅ |
| Compresión ZIP previa | ✅ | ✅ |
| Ocultar archivos `.lock` | ✅ | ✅ |
| Herramientas avanzadas adicionales | ❌ | ✅ |
| Soporte técnico prioritario | ❌ | ✅ |
| **Precio** | **GRATIS** | **CONSULTAR WEB** |
| **Enlace** | [sitio web oficial](https://escudodigitalsv.com) | [Ver Versión Pro](https://escudodigitalsv.com) |

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

# ⚠️ Importante / Notas de Seguridad

> [!CAUTION]
> **No pierdas tu contraseña:** EasyFolderLock **NO** puede recuperar el contenido de un archivo `.lock` si se pierde la contraseña.

> [!WARNING]
> Se recomienda mantener una copia de seguridad de los datos importantes antes de eliminar la carpeta original. La seguridad general depende directamente de utilizar contraseñas fuertes.

---

# 📦 Requisitos del Sistema

| Requisito | Especificación |
| --- | --- |
| **Sistema Operativo** | Windows 10 o superior |
| **Entorno de Ejecución** | Python 3.10+ (si se ejecuta desde código fuente) |
| **Librerías Requeridas** | `PyQt5`, `cryptography` |

### Instalación de dependencias (Código fuente)

```bash
pip install PyQt5 cryptography

```

---

# 🐛 Reportar un Problema

Si encuentras un error o comportamiento inesperado, abre un **Issue** indicando:

* Versión de EasyFolderLock
* Versión de Windows
* Pasos para reproducir el problema
* Mensaje de error / Captura de pantalla

> [!IMPORTANT]
> **Seguridad:** Nunca me publiques ni adjuntes contraseñas o archivos `.lock` que contengan información personal sensible.

---

# 📄 Licencia

Consulta el archivo `LICENSE` incluido en este repositorio para conocer los términos completos de distribución y uso.

---

## 🌐 Escudo Digital SV

Desarrollado con ❤️ por **Escudo Digital SV**

🌐 Sitio web oficial: [escudodigitalsv.com](https://escudodigitalsv.com)

© 2026 Escudo Digital SV. Todos los derechos reservados.
