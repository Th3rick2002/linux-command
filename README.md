# Introducción a la Terminal de Linux

## 📚 Conceptos Básicos

### 1. **Terminal**
La **terminal** es una interfaz de texto que permite a los usuarios interactuar con el sistema operativo. A través de la terminal, puedes ejecutar comandos, gestionar archivos, instalar software, y realizar muchas otras tareas.

### 2. **Shell**
El **shell** es un programa que interpreta los comandos que introduces en la terminal y los ejecuta. El shell más común en Linux es **Bash** (Bourne Again Shell).

### 3. **Comando**
Un **comando** es una instrucción que le das al sistema operativo para realizar una tarea específica. Por ejemplo, `ls` es un comando que lista los archivos en un directorio.

### 4. **Prompt**
El **prompt** es la línea de texto que aparece en la terminal y que indica que el sistema está listo para recibir comandos. Normalmente, el prompt muestra información como el nombre del usuario, el nombre del sistema, y el directorio actual.

### 5. **Directorio (Carpeta)**
Un **directorio** es similar a una carpeta en otros sistemas operativos. Es un contenedor que puede almacenar archivos y otros directorios.

### 6. **Ruta (Path)**
La **ruta** es la dirección de un archivo o directorio en el sistema de archivos. Puede ser **absoluta** (comienza desde el directorio raíz, por ejemplo `/home/usuario/documentos`) o **relativa** (relativa al directorio actual, por ejemplo `documentos/archivo.txt`).

### 7. **Archivo**
Un **archivo** es un conjunto de datos almacenados en el sistema de archivos. Puede ser un documento de texto, una imagen, un programa ejecutable, etc.

### 8. **Permisos**
Los **permisos** controlan quién puede leer, escribir o ejecutar un archivo. Los permisos se dividen en tres categorías: **usuario** (dueño del archivo), **grupo** (grupo de usuarios), y **otros** (todos los demás).

### 9. **Script**
Un **script** es un archivo que contiene una serie de comandos que se ejecutan secuencialmente. Los scripts son útiles para automatizar tareas repetitivas.

---

## 📌 Guía de Comandos Básicos de Linux

### 📂 Navegación por el Sistema de Archivos

| Comando | Descripción |
|---------|-------------|
| `pwd` | Muestra la ruta del directorio actual. |
| `ls` | Lista archivos y directorios en el directorio actual. |
| `ls -a` | Lista archivos, incluyendo los ocultos. |
| `ls -l` | Lista archivos con detalles (permisos, propietario, tamaño, fecha). |
| `cd <ruta>` | Cambia al directorio especificado. |
| `cd ..` | Retrocede un nivel en la jerarquía de directorios. |
| `cd /` | Va al directorio raíz. |
| `tree` | Muestra la estructura de archivos en forma de árbol. |
| `clear` | Limpia la terminal. |

---

### 📁 Gestión de Archivos y Directorios

| Comando | Descripción |
|---------|-------------|
| `touch <archivo>` | Crea un archivo vacío. |
| `mkdir <nombre>` | Crea un directorio. |
| `rm <archivo>` | Elimina un archivo. |
| `rm -r <directorio>` | Elimina un directorio y su contenido. |
| `cp <origen> <destino>` | Copia un archivo o directorio. |
| `cp -r <origen> <destino>` | Copia un directorio de forma recursiva. |
| `mv <origen> <destino>` | Mueve o renombra archivos y directorios. |
| `cat <archivo>` | Muestra el contenido de un archivo. |

---

### 📝 Edición de Archivos con Nano y Vim

📌 Nano
| Comando | Descripción |
|---------|-------------|
| `nano <archivo>` | Abre un archivo en el editor Nano. |
| `CTRL + X` | Salir de Nano. |
| `CTRL + S` | Guardar cambios. |
| `CTRL + K` | Cortar una línea. |
| `CTRL + U` | Pegar una línea. |

📌 Vim
| Comando | Descripción |
|---------|-------------|
| `vim <archivo>` | Abre un archivo en el editor Vim. |
| `i` | Modo de inserción. |
| `ESC` | Salir del modo de inserción. |
| `:w` | Guardar cambios. |
| `:q` | Salir de Vim. |
| `:wq` | Guardar y salir. |
| `:q!` | Salir sin guardar cambios. |

---

### 📌 Notas
- Para obtener más información sobre un comando, usa `man <comando>`.
- Algunos comandos requieren permisos de superusuario (`sudo`).

