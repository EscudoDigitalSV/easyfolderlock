# 🔐 EasyFolderLock

**Protege tus carpetas mediante cifrado seguro y conviértelas en archivos `.lock`.**

EasyFolderLock es una herramienta para Windows diseñada para proteger carpetas de forma sencilla y segura. La aplicación comprime la carpeta, cifra su contenido y genera un único archivo `.lock` protegido mediante contraseña.

EasyFolderLock está disponible en dos ediciones:

* 🆓 **EasyFolderLock Free** — protección esencial de carpetas.
* ⭐ **EasyFolderLock Pro** — protección avanzada y funciones adicionales.

> 🌐 **Sitio web oficial:** https://escudodigitalsv.com

## ✨ Características principales

EasyFolderLock ofrece un conjunto de herramientas para proteger, administrar y restaurar carpetas mediante archivos `.lock`.

### 🔐 Seguridad

* 🔐 Cifrado mediante **AES-GCM**
* 🔑 Protección mediante contraseña
* 🧂 Salt aleatorio para la derivación de claves
* 🔢 Nonce aleatorio para cada operación de cifrado
* 🛡️ Verificación de integridad mediante AES-GCM
* 📦 Compresión ZIP antes del cifrado
* 🗃️ Formato de archivo **EFL1**
* 🛡️ Protección contra sobrescrituras accidentales
* 💾 Verificación antes de eliminar la carpeta original
* 📂 Restauración segura de archivos

### 📂 Administración

* 🔒 Bloqueo de carpetas
* 🔓 Desbloqueo de archivos `.lock`
* 📁 Desbloqueo de varios archivos
* 🔎 Búsqueda de archivos `.lock`
* 📂 Restauración en la ubicación original o en otra ubicación
* 🖱️ Arrastrar y soltar
* 👻 Ocultar archivos `.lock` en Windows
* 💾 Mantener una copia de seguridad de la carpeta original
* 📊 Barra de progreso
* 📝 Registro de operaciones

## 🆓 EasyFolderLock Free

**Protección esencial para tus carpetas.**

EasyFolderLock Free está diseñada para usuarios que necesitan una herramienta sencilla para proteger sus carpetas mediante cifrado y almacenarlas como archivos `.lock`.

La versión Free incluye las funciones esenciales necesarias para bloquear, proteger y restaurar carpetas.

### ✨ Características de EasyFolderLock Free

#### 🔐 Protección

* 🔐 Cifrado **AES-GCM**
* 🔑 Protección mediante contraseña
* 🧂 Salt aleatorio
* 🔢 Nonce aleatorio
* 📦 Compresión ZIP antes del cifrado
* 🛡️ Formato interno **EFL1**
* 🔒 Verificación de integridad
* 🛡️ Protección contra sobrescrituras accidentales
* 💾 Verificación del archivo protegido antes de eliminar la carpeta original
* 📂 Restauración segura

#### 📂 Bloqueo de carpetas

Puedes seleccionar cualquier carpeta compatible y protegerla mediante una contraseña.

El proceso es:

```text
Carpeta
   ↓
Compresión ZIP
   ↓
Cifrado AES-GCM
   ↓
Archivo protegido .lock
```

Por ejemplo:

```text
Documentos
     ↓
Documentos.lock
```

#### 🔓 Desbloqueo

Para recuperar una carpeta:

```text
Archivo .lock
   ↓
Contraseña
   ↓
Verificación
   ↓
Descifrado
   ↓
Descompresión
   ↓
Carpeta restaurada
```

#### 🖱️ Arrastrar y soltar

Puedes arrastrar directamente:

* 📂 Una carpeta → para prepararla para el bloqueo.
* 🔒 Un archivo `.lock` → para iniciar su desbloqueo.

#### 🔎 Buscar archivos `.lock`

La aplicación permite seleccionar una carpeta y buscar archivos `.lock`, incluyendo archivos ocultos en Windows.

Puedes seleccionar uno o varios archivos para desbloquearlos.

#### 👻 Ocultar archivos `.lock`

En Windows puedes ocultar el archivo protegido para evitar que aparezca normalmente en el Explorador de archivos.

Ejemplo:

```text
Documentos.lock
```

puede quedar marcado como archivo oculto.

La aplicación también permite localizar archivos `.lock` ocultos mediante su función de búsqueda.

#### 💾 Mantener una copia

Puedes elegir conservar la carpeta original después de crear el archivo `.lock`.

Esto permite mantener una copia adicional de los datos.

#### 📂 Restauración personalizada

Al desbloquear un archivo `.lock`, puedes restaurarlo:

* En la misma ubicación.
* En otra carpeta seleccionada por el usuario.

#### 📊 Progreso y registro

EasyFolderLock muestra el progreso de las operaciones y mantiene un registro de las acciones realizadas durante el proceso.

## ⭐ EasyFolderLock Pro

**Protección avanzada y herramientas adicionales para usuarios que necesitan más control.**

EasyFolderLock Pro incluye todas las funciones principales de EasyFolderLock Free y añade herramientas avanzadas para facilitar la protección y administración de archivos y carpetas.

### ✨ Características de EasyFolderLock Pro

#### 🔐 Todo lo incluido en Free

EasyFolderLock Pro incluye las funciones de la versión Free:

* AES-GCM
* Formato EFL1
* Bloqueo de carpetas
* Desbloqueo de `.lock`
* Drag & Drop
* Búsqueda de `.lock`
* Desbloqueo múltiple
* Restauración personalizada
* Ocultar `.lock`
* Copia de seguridad
* Verificación de integridad
* Protección contra sobrescrituras
* Manejo seguro de errores

#### 🖱️ Integración con Windows

EasyFolderLock Pro está diseñado para integrarse más profundamente con Windows.

Funciones Pro:

* 🔒 Bloquear una carpeta desde el menú contextual.
* 🔓 Desbloquear un archivo `.lock` desde el menú contextual.
* ⚡ Bloqueo rápido.
* 📁 Integración con Windows Explorer.
* 🔗 Asociación de archivos `.lock` con EasyFolderLock Pro.

El objetivo es poder realizar las operaciones principales sin necesidad de abrir manualmente la aplicación.

#### ⚡ Bloqueo rápido

El bloqueo rápido permite proteger carpetas con menos pasos utilizando las preferencias configuradas previamente.

Esta función está diseñada para usuarios que realizan operaciones de protección frecuentemente.

#### 📦 Bloqueo y desbloqueo masivo

EasyFolderLock Pro amplía las operaciones múltiples para facilitar la gestión de grandes cantidades de carpetas y archivos protegidos.

Ejemplo:

```text
☑ Documentos
☑ Fotos
☑ Proyectos
☑ Facturas
☑ Trabajo

[ 🔒 Bloquear seleccionadas ]
```

También permite seleccionar múltiples archivos:

```text
☑ Documentos.lock
☑ Fotos.lock
☑ Proyectos.lock

[ 🔓 Desbloquear seleccionados ]
```

#### 🔍 Verificación avanzada

La versión Pro puede proporcionar herramientas para comprobar el estado de un archivo protegido antes de restaurarlo.

Ejemplo:

```text
Archivo: Documentos.lock

Formato EFL1          ✅
Archivo válido        ✅
Integridad            ✅
Datos cifrados        ✅
```

#### 🔐 Cofres seguros

EasyFolderLock Pro incorpora herramientas orientadas a crear y administrar espacios protegidos para almacenar archivos privados.

Los cofres están diseñados para facilitar la administración de múltiples archivos protegidos desde una interfaz centralizada.

#### 🗝️ Recuperación

La edición Pro está orientada a incorporar mecanismos adicionales de recuperación para usuarios que necesiten una alternativa segura para gestionar sus credenciales de protección.

La recuperación no permite obtener una contraseña perdida de forma directa y debe estar diseñada para mantener la seguridad criptográfica de los datos.

#### 📋 Historial

EasyFolderLock Pro puede incluir un historial de operaciones para facilitar el seguimiento de las acciones realizadas.

Ejemplo:

```text
10/08/2026  15:42  🔒 Documentos
10/08/2026  15:45  🔒 Fotos
10/08/2026  15:50  🔓 Documentos
10/08/2026  16:03  🔒 Trabajo
```

El historial no debe almacenar contraseñas ni información sensible de los archivos protegidos.

#### 💾 Modo portable

EasyFolderLock Pro está orientada a ofrecer una modalidad portable para usuarios que necesiten ejecutar la aplicación desde diferentes ubicaciones, como:

* USB
* Disco externo
* Carpeta portátil

#### ⚙️ Configuración avanzada

La versión Pro puede ofrecer opciones adicionales para personalizar el comportamiento de la aplicación.

Entre ellas:

* Carpeta predeterminada de restauración.
* Preferencias de confirmación.
* Comportamiento después del bloqueo.
* Ocultar archivos `.lock`.
* Preferencias de operaciones.
* Opciones de interfaz.
* Otras configuraciones avanzadas.

Las funciones disponibles pueden variar según la versión de EasyFolderLock Pro.

## 🔒 Formato EFL1

EasyFolderLock utiliza un formato interno denominado:

```text
EFL1
```

**EFL** significa:

> **EasyFolderLock Format**

El número `1` identifica la primera versión del formato.

La estructura básica del archivo protegido es:

```text
EFL1
+ Salt
+ Nonce
+ Datos cifrados
```

Los archivos utilizan la extensión:

```text
.lock
```

Por ejemplo:

```text
Documentos.lock
Fotos.lock
Proyectos.lock
Facturas.lock
```

El formato `EFL1` permite que EasyFolderLock identifique los archivos generados por la aplicación independientemente del nombre que tengan.

### 🔄 Compatibilidad Free y Pro

Las versiones compatibles de EasyFolderLock Free y EasyFolderLock Pro utilizan el mismo formato base **EFL1**.

Esto permite que los archivos `.lock` creados con una versión compatible puedan ser utilizados con la otra edición, siempre que la versión del formato sea compatible.

> **EFL1 corresponde al formato interno del archivo y no a la versión de la aplicación.**

Por ejemplo:

```text
EasyFolderLock 1.5
        ↓
      EFL1

EasyFolderLock Free 2.0
        ↓
      EFL1

EasyFolderLock Pro 2.0
        ↓
      EFL1
```

El formato solamente cambiaría a `EFL2` si en el futuro fuera necesario realizar un cambio incompatible en la estructura del archivo.

## 🛡️ Seguridad y protección de datos

EasyFolderLock utiliza cifrado autenticado **AES-GCM** para proteger los datos almacenados dentro del archivo `.lock`.

Cada operación utiliza valores criptográficos aleatorios, incluyendo:

* Salt.
* Nonce.

La contraseña del usuario se utiliza para derivar la clave criptográfica utilizada para cifrar y descifrar los datos.

### 🔑 Contraseña

La contraseña es esencial para recuperar los datos.

**No existe una contraseña universal de recuperación.**

Si pierdes la contraseña correcta, es posible que no puedas recuperar el contenido del archivo `.lock`.

Por este motivo:

> ⚠️ **Conserva tu contraseña en un lugar seguro.**

También se recomienda utilizar contraseñas largas, únicas y difíciles de adivinar.

### 💾 Copias de seguridad

El cifrado protege los datos, pero no sustituye una estrategia de copias de seguridad.

Para información importante se recomienda mantener copias adicionales en un medio seguro.

## 🔑 Licencias de EasyFolderLock Pro

EasyFolderLock Free no requiere licencia.

EasyFolderLock Pro utiliza un sistema de licenciamiento para gestionar sus funciones avanzadas.

### 🧪 Prueba gratuita

EasyFolderLock Pro ofrece un período de prueba de:

**15 días**

Durante este período puedes probar las funciones Pro antes de adquirir una licencia.

Una vez finalizado el período de prueba será necesario activar una licencia válida para continuar utilizando las funciones Pro.

### 📅 Tipos de licencia

La versión Pro puede ofrecer:

* 🧪 Prueba de 15 días
* 📅 Licencia anual
* ♾️ Licencia vitalicia

El sistema de licencias puede gestionar:

* Activación.
* Validación.
* Expiración.
* Estado de la licencia.
* Identificación del equipo cuando sea necesario.

La licencia controla el acceso a las funciones Pro y no sustituye el sistema de cifrado utilizado para proteger los archivos.

## 🆚 EasyFolderLock Free vs Pro

| Característica                   | 🆓 Free | ⭐ Pro |
| -------------------------------- | :-----: | :---: |
| Cifrado AES-GCM                  |    ✅    |   ✅   |
| Protección mediante contraseña   |    ✅    |   ✅   |
| Salt aleatorio                   |    ✅    |   ✅   |
| Nonce aleatorio                  |    ✅    |   ✅   |
| Compresión ZIP                   |    ✅    |   ✅   |
| Formato EFL1                     |    ✅    |   ✅   |
| Bloquear carpetas                |    ✅    |   ✅   |
| Desbloquear `.lock`              |    ✅    |   ✅   |
| Arrastrar y soltar               |    ✅    |   ✅   |
| Buscar `.lock`                   |    ✅    |   ✅   |
| Archivos `.lock` ocultos         |    ✅    |   ✅   |
| Desbloqueo múltiple              |    ✅    |   ✅   |
| Restauración personalizada       |    ✅    |   ✅   |
| Mantener copia de seguridad      |    ✅    |   ✅   |
| Verificación de integridad       |    ✅    |   ✅   |
| Protección contra sobrescrituras |    ✅    |   ✅   |
| Restauración segura              |    ✅    |   ✅   |
| Menú contextual de Windows       |    ❌    |   ✅   |
| Asociación `.lock`               |    ❌    |   ✅   |
| Bloqueo rápido                   |    ❌    |   ✅   |
| Bloqueo masivo avanzado          |    ❌    |   ✅   |
| Verificación avanzada            |    ❌    |   ✅   |
| Cofres seguros                   |    ❌    |   ✅   |
| Funciones de recuperación        |    ❌    |   ✅   |
| Historial avanzado               |    ❌    |   ✅   |
| Modo portable                    |    ❌    |   ✅   |
| Configuración avanzada           |    ❌    |   ✅   |
| Sistema de licencias             |    ❌    |   ✅   |
| Prueba de 15 días                |    ❌    |   ✅   |
| Licencia anual                   |    ❌    |   ✅   |
| Licencia vitalicia               |    ❌    |   ✅   |

## 💻 Requisitos

### EasyFolderLock Free

* Windows 10 o superior.
* Python 3.10+ si se ejecuta desde el código fuente.
* PyQt5.
* cryptography.

Instalación de dependencias:

```bash
pip install PyQt5 cryptography
```

### EasyFolderLock Pro

* Windows 10 o superior.
* Python 3.10+ si se ejecuta desde el código fuente.
* PyQt5.
* cryptography.
* Conexión a Internet para las funciones que requieran validación de licencia.

Los requisitos pueden variar según la versión distribuida.

## 🚀 Uso

### 🆓 Free — Bloquear una carpeta

1. Selecciona una carpeta.
2. Introduce una contraseña.
3. Confirma la contraseña.
4. Decide si quieres conservar una copia de la carpeta original.
5. Configura las opciones disponibles.
6. Pulsa **Bloquear**.
7. EasyFolderLock creará el archivo `.lock`.

Ejemplo:

```text
Mis documentos
      ↓
Mis documentos.lock
```

### 🔓 Free — Desbloquear

1. Selecciona un archivo `.lock`.
2. Introduce la contraseña.
3. Elige la ubicación de restauración.
4. Confirma la operación.
5. EasyFolderLock restaurará el contenido.

### ⭐ Pro — Operaciones avanzadas

Además de los métodos disponibles en Free, Pro permite utilizar las funciones adicionales disponibles en la versión instalada, incluyendo la integración con Windows y las herramientas avanzadas.

## 📦 Archivo `.lock`

Los archivos `.lock` son archivos protegidos generados por EasyFolderLock.

Ejemplos:

```text
Documentos.lock
Fotos.lock
Trabajo.lock
Facturas.lock
```

El contenido está protegido mediante cifrado y no debe modificarse manualmente.

No se recomienda editar, truncar o modificar un archivo `.lock` fuera de EasyFolderLock.

## ⚠️ Advertencias importantes

### 🔑 No pierdas tu contraseña

EasyFolderLock no puede garantizar la recuperación de datos si se pierde la contraseña correcta.

### 💾 Mantén copias de seguridad

El archivo `.lock` debe considerarse un archivo importante y debe respaldarse cuando contenga información crítica.

### 🛑 No interrumpas operaciones importantes

Evita apagar el equipo o cerrar la aplicación mientras se está realizando una operación de bloqueo o restauración.

### 🔒 Protege tus archivos `.lock`

Un archivo `.lock` puede contener información personal o confidencial. Almacénalo en ubicaciones seguras.

### 🚫 No compartas tus contraseñas

Nunca publiques contraseñas, claves de licencia ni archivos `.lock` privados al solicitar soporte.

## 📥 Descargas

Las versiones oficiales de EasyFolderLock están disponibles en nuestro sitio web.

### 🆓 EasyFolderLock Free

Descarga la versión gratuita desde:

🌐 [**https://escudodigitalsv.com**](https://escudodigitalsv.com)

### ⭐ EasyFolderLock Pro

Consulta las opciones de descarga, prueba y licencia desde:

🌐 [**https://escudodigitalsv.com**](https://escudodigitalsv.com)

La información sobre precios y licencias se encuentra disponible en el sitio web oficial.

## 💰 EasyFolderLock Pro

¿Necesitas más funciones?

EasyFolderLock Pro está diseñada para usuarios que necesitan herramientas avanzadas para administrar y proteger sus carpetas.

Consulta:

* Características Pro.
* Prueba gratuita de 15 días.
* Licencias anuales.
* Licencias vitalicias.
* Actualizaciones.
* Información de soporte.

🌐 **Sitio web oficial:**

https://escudodigitalsv.com

## 🐛 Reportar un problema

Si encuentras un error o comportamiento inesperado, puedes abrir un **Issue** en este repositorio.

Al reportar un problema, incluye cuando sea posible:

* Versión de EasyFolderLock.
* Edición utilizada: Free o Pro.
* Versión de Windows.
* Pasos para reproducir el problema.
* Mensaje de error.
* Captura de pantalla.
* Información adicional relevante.

### 🚨 Información que nunca debes publicar

No incluyas:

* ❌ Contraseñas.
* ❌ Claves de licencia.
* ❌ Claves privadas.
* ❌ Archivos `.lock` con información personal.
* ❌ Datos confidenciales.
* ❌ Tokens o credenciales.

## 📄 Licencia

EasyFolderLock es desarrollado por **Escudo Digital SV**.

La versión Free y la versión Pro pueden estar sujetas a diferentes condiciones de distribución y uso.

Consulta el archivo `LICENSE` incluido en este repositorio para conocer los términos aplicables al código y los archivos distribuidos.

La versión Pro puede estar sujeta adicionalmente a los términos de licencia comercial correspondientes.

## 🌐 Escudo Digital SV

EasyFolderLock es desarrollado por **Escudo Digital SV**.

🌐 **Sitio web oficial:**

https://escudodigitalsv.com

Desde el sitio web oficial puedes consultar:

* EasyFolderLock Free.
* EasyFolderLock Pro.
* Otros productos de Escudo Digital SV.
* Descargas.
* Precios.
* Licencias.
* Soporte.
* Actualizaciones.

## 📌 Resumen

**EasyFolderLock Free** proporciona una forma sencilla de proteger carpetas mediante cifrado y archivos `.lock`.

**EasyFolderLock Pro** incorpora las funciones de Free y añade herramientas avanzadas para usuarios que necesitan mayor comodidad, administración e integración con Windows.

Ambas ediciones utilizan el formato **EFL1** para los archivos protegidos compatibles.

> 🔐 **EasyFolderLock — Protege lo que más importa.**

© 2026 Escudo Digital SV. Todos los derechos reservados.
