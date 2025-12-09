# Estructura del curso

## __1) ¿Qué es VSCode? ¿Para qué sirve? ¿Cómo se maneja...?__

Visual Studio Code, comúnmente conocido como VS Code, es un IDE (Entorno de Desarrollo Integrado), es decir, es una aplicación que sirve para crear código y que automatiza y facilita múltiples funciones.

Visual Studio Code es un programa desarrollado por Microsoft. Es gratuito y de código abierto y funciona en Windows, MacOS y Linux.

Se ha convertido en uno de los IDEs más populares gracias a su ligereza, flexibilidad y capacidades de customización. Entre otras cosas permite:

1. Escribir y editar código

Admite una enorme cantidad de lenguajes que pueden personalizarse con extensiones: JavaScript, Python, Java, C#, PHP, HTML/CSS, Go, C/C++, Rust, etc.

2. Ejecutar, depurar y probar aplicaciones

VSCode integra la terminal y permite correr código, ver errores en tiempo real y depurar proyectos paso a paso.

3. Gestionar proyectos

Facilita la navegación por carpetas, archivos, módulos, etc.

4. Integración con GIT y GitHub

Incluye herramientas para gestionar las versiones de un proyecto.

5. Personalizar el entorno de desarrollo

Permite instalar extensiones, cambiar temas de color, atajos, iconos, configuraciones avanzadas, etc.

6. Trabajar con contenedores, entornos remotos y Dev Containers

VS Code integra extensiones que permiten trabajar con contenedores.



## __2) Instalación__

### Windows

1. Entra en la página oficial: https://code.visualstudio.com/

2. Haz clic en Download for Windows.

3. Ejecuta e instala el archivo descargado, aceptando los términos de uso y dejando las opciones por defecto (especialmente "Add to PATH").

### MacOS

1. Entra en https://code.visualstudio.com/

2. Descarga el archivo para la versión de Mac que estés usando ARM o Intel.

3. Abre el archivo y arrastra el icono de VS Code a la carpeta Applications.

### Linux

#### Ubuntu / Debian

Se puede descargar el archivo .deb de instalación desde [la web oficial](https://code.visualstudio.com/) o se puede instalar usando la terminal:

```
sudo apt update
sudo apt install software-properties-common apt-transport-https wget
wget -qO- https://packages.microsoft.com/keys/microsoft.asc | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main"
sudo apt update
sudo apt install code
```

#### Fedora / Red Hat / CentOS

Se puede descargar el archivo .rpm de instalación desde [la web oficial](https://code.visualstudio.com/) o se puede instalar usando la terminal:

```
sudo rpm --import https://packages.microsoft.com/keys/microsoft.asc
sudo sh -c 'echo -e "[code]\nname=Visual Studio Code\nbaseurl=https://packages.microsoft.com/yumrepos/vscode\nenabled=1\ngpgcheck=1\ngpgkey=https://packages.microsoft.com/keys/microsoft.asc" > /etc/yum.repos.d/vscode.repo'
sudo dnf check-update
sudo dnf install code
```

## __3) La extensión GitHub Copilot__

### ¿Qué es GitHub Copilot?

GitHub Copilot es una herramienta de asistencia de código basada en inteligencia artificial (IA) desarrollada por GitHub y Microsoft. 

Ésta funciona interpretando lo que escribe y sugiriendo líneas de código.

Tiene versiones para diferentes IDEs (VSCode, Eclipse, XCode, etc.) en los que se integra como una extensión.

### ¿Para qué sirve GitHub Copilot?

GitHub Copilot ayuda al desarrollador a:

* Autocompletar código automáticamente mientra se escribe, sugiriendo como continuar por lo que acelera la escritura de código y la productividad.

* Generar estructuras estándar (boilerplates). Es ideal para crear plantillas, bases de proyecto, configuraciones, etc.

* Funciona para múltiples lenguajes y tecnologías.

* Da sugerencias inteligentes contextualizadas. Teniendo en cuenta el contexto del archivo, proyecto, lenguaje, código escrito, etc... 


### Qué tener en cuenta

* Es necesario tener una cuenta de GitHub.

* No es un copia y pega de código sino que genera sugerencias mediante modelos probabilísticos

* El usuario tiene siempre el control y puede aceptar, modificar o descartar la sugerencia que hace Copilot

* __HAY QUE REVISAR SIEMPRE LAS SUGERENCIAS__


## __4) Funciones__

### 1. Autocompletado

Crear archivo py y crear una función que haga la suma de dos números

### 2. Chat inline

Control/Command + i en editor y consola

### 3. Chat

Barra lateral derecha
Modo ask
Modo agente
/explain

### 4. Instrucciones

# Biblografía

Visual Studio Code: Tutorial para principiantes. Mouredev. https://www.youtube.com/watch?v=CxF3ykWP1H4

¡Así te Ayuda GitHub Copilot a programar MÁS RÁPIDO en VS Code!. Mouredev. https://www.youtube.com/watch?v=XpQ7uUXuPHg

