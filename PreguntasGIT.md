# Preguntas acerca de GIT

<pre>**¿Qué es git?**  
Git es un sistema de control de versiones, es decir un sistema o programa que controla o administra las distintas versiones de un programa.
Es un sistema de control distribuido ya que permite trabajar con un repositorio de código, donde múltiples desarrolladores podrán alterar el código, pero todos ellos tendrán una copia local de él. 
Es una herramienta que interactúa directamente con el sistema operativo.<pre>

<pre>**¿Por qué queremos utilizar git?**  
Queremos utilizar git para controlar nuestro proyecto a medida que se van realizando cambios, ya que a medida que el proyecto va creciendo nosotros vamos cambiando archivos, se va cambiando la configurado de la aplicación, modificamos el código, etc.
De esta forma vamos a obtener un listado de los cambios que iremos haciendo.
Además, nos permitirá colaborar con múltiples desarrolladores desde cualquier parte del mundo y coordinar el trabajo en el mismo proyecto.
También queremos usarlo para poder navegar entre cualquier versión del programa, ya que con él se puede ver que día y a qué hora se modificó el código, quién lo modificó, que línea de código fue modificada y poder revertir cualquier cambio que hayamos hecho.<pre>

<pre>**¿Qué es el bash que instala git?**  
El bash es una consola, pero con mejores funcionalidades que trae todos los conceptos de Unix, de Linux y de Mac.<pre>

<pre>**Describa los estados (working directory, staging area, repository)**  
*Working directory* es donde se trabaja con todos los archivos.  
*Staging area* es dónde se agregan todos los archivos qué se preparan para el guardado.  
Por último, *repository* es donde se van a pasar los archivos cuando se esté decidido a guardar el cambio.<pre>

<pre>**Describa el flujo para crear un nuevo repositorio git.**  
1. Crear una carpeta para el proyecto
2. En un editor, abrir esa carpeta y crear un archivo. Por ejemplo: En la carpeta proyecto el archivo app.js
3. Abrir Git Bash (consola)
4. Ubicarme en la carpeta. Por ejemplo: cd Desktop/proyecto
5. Escribir el comando git init<pre>

<pre>**Describa el flujo para agregar un archivo simple al repositorio.**  
1. Escribir el comando git add seguido del nombre del archivo. Por ejemplo: git add app.js
2. Escribir el comando git config –global user.email seguido de tu email.*
3. Escribir el comando git config –global user.name seguido de tu nombre.*
4. Escribir el comando git commit. Se abrirá el editor predeterminado (Vim), aquí hay que escribir un mensaje. Para empezar a escribir se presiona “i” para salir esc y luego :wq  
*Los pasos 2 y 3 se realizan si el usuario no está logueado y por única vez.*<pre>

<pre>**Describa el flujo para cambiar el archivo agregado y guardar los cambios en el repositorio.**  
1. Modifico el archivo.Por ejemplo: el archivo app.js
2. Para ver las diferencias en el archivo, escribo el comando git diff seguido del nombre del archivo.
3. Para agregar los cambios, nuevamente git add seguido del nombre del archivo
4. Por último, git commit y al abrirse el editor escribo un nuevo mensaje<pre>

<pre>**¿Cómo hago para ignorar un archivo o carpeta?**  
1. Creo un nuevo archivo llamado “.gitignore”
2. En este archivo, escribo el nombre del archivo o carpeta que quiero ignorar
3. En la consola, escribo el comando git add .gitignore
4. Escribo git commit -m “El mensaje que quiera poner” (De esta forma evito entrar al editor de texto)<pre>

<pre>**Explique qué es un branch. Dé un pequeño ejemplo de cómo haría uno.**  
Branch es una rama nueva, es decir, una nueva versión alternativa del código.
Para hacer un nuevo Branch, debo escribir el comando git branch nombre del Branch. Por ejemplo: git branch login<pre>

<pre>**¿Qué hago con git add .?**  
Con este comando logro agregar todos los archivos que quiero subir de una sola vez.<pre>

<pre>**¿Cómo cambiamos de un branch a otro?**  
Mediante el comando git checkout nombre de otra rama. Por ejemplo: gitcheckout login<pre>

<pre>**Investigue qué es Markdown y responda todas las preguntas anteriores en este lenguaje (con el nombre de archivo RESPUESTAS.md). Súbalo al repositorio.**  
Markdown es un lenguaje de marcado que facilita la aplicación de formato a un texto empleando una serie de caracteres de una forma especial.
Es decir, por un lado, es el lenguaje; por otro, una herramienta de software que convierte el lenguaje en HTML válido.<pre>