#Ingenieria Web A3
## Este repositorio de github corresponde a la asignatura ingenieria web 1
 
GUIA 1
Cómo clonar y visualizar el proyecto desde GitHub
¿Qué significa clonar un repositorio?
Clonar un repositorio es el proceso de copiar todo el contenido de un proyecto desde GitHub a tu computador local. Esto te permite:

Ver, modificar y ejecutar los archivos del proyecto
Trabajar localmente sin conexión permanente a internet
Enviar cambios al repositorio remoto (si tienes permisos)
Requisitos previos
Tener Git instalado:

Verifica con git --version
Si no lo tienes, descárgalo desde https://git-scm.com
Acceso a internet y navegador para obtener la URL del repositorio

Un editor de código recomendado: Visual Studio Code (https://code.visualstudio.com)

Cómo clonar el repositorio en Linux
Abre la terminal (Ctrl + Alt + T o búscala en el menú de aplicaciones)

Verifica si Git está instalado:

git --version

Si no lo esta, instala con: sudo apt update sudo apt install git

Elige una carpeta para clonar el proyecto: cd Documentos Si no sabes como ver las carpetas desde el terminal utiliza el comando ls el cual visualiza las carpetas

Copia la URL del repositorio desde GitHub:

Entra a https://github.com/OFabian-Diaz/Ingenieria_Web
Haz clic en el botón "Code" y copia el enlace HTTPS
Clona el repositorio: git clone https://github.com/OFabian-Diaz/Ingenieria_Web.git

Accede a la carpeta del proyecto: cd IngeWebA3

Abre el archivo index.html en el navegador: xdg-open index.html

Cómo clonar el repositorio en Windows
Instala Git desde: https://git-scm.com/download/win
Abre el programa Git Bash (viene incluido con Git)
Elige una carpeta de destino, por ejemplo: cd /c/Users/TuUsuario/Documentos
Copia la URL del repositorio desde GitHub:
Entra a https://github.com/OFabian-Diaz/Ingenieria_Web
Haz clic en "Code" y copia el enlace HTTPS
Clona el repositorio: git clone https://github.com/OFabian-Diaz/Ingenieria_Web.git
Accede al proyecto: cd IngeWebA3
Abre index.html en tu navegador con doble clic o usa Visual Studio Code: code .
Guia 1 ingenieria web:
Tema del proyecto
Construcción de una Web Informativa Semántica

Este repositorio contiene una página principal informativa sobre los Fundamentos de la Web Moderna, elaborada con HTML5 siguiendo las buenas prácticas de semántica y accesibilidad. Está dividida en secciones sobre:

Historia de la ingeniería web (en index.html)
¿Qué es la ingeniería web? (ingenieriaweb.html)
Arquitectura cliente-servidor (clienteservidor.html)
Semántica y accesibilidad en HTML5 (html5.html)
Reflexión individual
Durante el desarrollo de esta actividad entendi que organizar de manera semantica me ayuda a tener una mejor estructura y orden en el codigo, ademas de esto entendi que esto me facilita la accesibilidad, el posicionamiento web, y la comprensión del sitio por parte de otros desarrolladores.

Aprendi el uso y la importacia de utilizar algunas etiquetas como <header>, <main>, <section> y <footer> ya que no solo es una cuestión estética, sino que responde a una necesidad de mantener el orden y la lógica de los componentes en el desarrollo de una pagina web.

También aprendí a organizar archivos y carpetas dentro de un proyecto web, y a subirlos correctamente a un repositorio GitHub con control de versiones, lo cual es fundamental para trabajar de forma profesional.



Explicación:

index.html: Página principal con la historia de la ingeniería web.
Los demás archivos .html contienen explicaciones específicas según el tema.
Las carpetas /css/, /js/ y /docs/ permiten separar estilos, scripts y documentación gráfica.
El archivo README.md documenta todo el proyecto, su estructura y cómo ejecutarlo.
Reflexión en equipo
¿Por qué organizar de forma semántica los contenidos facilita el trabajo colaborativo y el mantenimiento del sitio?
Porque permite que cualquier miembro del equipo entienda fácilmente la estructura y el propósito de cada parte del documento. Las etiquetas semánticas describen el contenido de manera clara y hacen que el código sea más legible, tanto para personas como para máquinas.

##Tres ventajas observadas del uso de HTML5 moderno:

Mejora la accesibilidad para todos los usuarios, incluyendo personas con discapacidad.
Facilita el posicionamiento en buscadores gracias a su estructura clara.
Hace el código más limpio, ordenado y fácil de mantener.

