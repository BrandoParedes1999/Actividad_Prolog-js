Aquí tienes el archivo README.md que solicitaste, detallando cómo descargar, instalar y ejecutar el proyecto del sistema de selección de cursos utilizando Prolog y Tau-Prolog (JavaScript):

Sistema de Selección de Cursos con Seriación (Prolog y Tau-Prolog)
Este proyecto implementa una base de conocimiento en Prolog para gestionar la selección de cursos de un alumno, respetando las seriaciones y los requisitos de aprobación previos. La lógica principal se ejecuta en el navegador utilizando la biblioteca Tau-Prolog (JavaScript).

🚀 Tecnologías Utilizadas
Prolog: Para la lógica de seriación y validación de prerrequisitos, definida en knowledge_base.pl.

JavaScript (JS): Para la interfaz de usuario y la interacción con el motor Prolog.

Tau-Prolog: El motor Prolog en JavaScript que permite ejecutar la lógica directamente en el navegador sin instalaciones de software de escritorio.

HTML/CSS: Para la estructura (index.html) y el estilo de la interfaz.

⬇️ Descarga del Proyecto
Para obtener una copia local de este proyecto, clona el repositorio de GitHub usando el siguiente comando:

Bash

git clone https://github.com/TuUsuario/NombreDelRepositorio.git
Luego, navega al directorio del proyecto:

Bash

cd NombreDelRepositorio
⚙️ Instalación
El proyecto es completamente autocontenido y no requiere instalaciones de software adicionales como SWI-Prolog, Node.js ni la ejecución de comandos npm o maven.

La biblioteca Tau-Prolog ya está incluida en la carpeta de scripts, lo que permite que el proyecto se ejecute directamente en cualquier navegador web moderno.

▶️ Ejecución del Código
Sigue estos sencillos pasos para iniciar la aplicación:

Opción 1: Apertura Directa (Recomendada)
Esta es la forma más fácil de ejecutar el programa.

Abre el explorador de archivos en la carpeta donde clonaste el proyecto.

Localiza el archivo principal de la interfaz: index.html.

Haz doble clic en index.html para abrirlo en tu navegador predeterminado (Chrome, Firefox, Edge, etc.).

La interfaz cargará la base de conocimiento Prolog automáticamente y te permitirá ingresar o modificar el estado de un alumno (cursos aprobados) y consultar si puede seleccionar un nuevo curso.

Opción 2: Usando un Servidor Local (Si el navegador restringe la carga de scripts)
En raras ocasiones, los navegadores pueden restringir la ejecución de scripts locales por motivos de seguridad. Si la Opción 1 no funciona correctamente, puedes usar un servidor local simple:

Instala un servidor web simple (si no tienes uno). Si tienes Node.js instalado, puedes usar http-server:

Bash

npm install -g http-server
Inicia el servidor desde la carpeta raíz del proyecto:

Bash

http-server
Abre tu navegador y navega a la dirección que te proporcione el servidor (típicamente http://127.0.0.1:8080/ o http://localhost:8080/).
