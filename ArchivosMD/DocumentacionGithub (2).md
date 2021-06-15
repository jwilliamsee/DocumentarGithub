## Este es un repositorio donde encontrarás información sobre como documentar tu proyecto en Github.

#### Contenido

**1. Crear un espacio en Github**

**2. Generando SSH Keys y agregarlo**

**3. Seguir el ejemplo del repositorio "Sensor H2O" para las carpetas y el README.md**

**4. Subír carpetas a GitHub usando la terminal virtual Git Bash en Windows**

**5. Subir carpetas a GitHub usando la terminal en Linux**

**6. Usar MEditor, página para crear documentos en intérprete Markdown, en sustitución de documentos PDF y Word para editarlos fácilmente**

**6.1** La página web que se usará es **MEditor.md**

**6.2** Poner imágenes en **MEditor.md** (intérprete de Markdown)

**6.3** Poner hipervínculos en sustitución de los links

**6.4** Algunas herramientas útiles

**7. Usar Dillinger, página web para poder guardar el documento creado con MEditor en Markdown, directo a nuestro equipo**

**8. Subir archivos desde la terminal en Windows, cuando ya tenemos carpetas en el repositorio**

**9. Subir archivos desde la terminal en Linux, cuando ya tenemos carpetas en el repositorio**

**10. Subir archivos desde la web en Github, cuando ya tenemos carpetas en el repositorio**


------------

#### 1. Crear un espacio en Github

Antes de poder crear un espacio en Github, es necesario tener una cuenta, haberse registrado para poder crear repositorios.
1. Tener una cuenta en Github, de lo contrario, crear una para poder empezar.
El link de la página de Github, lo encuentras al dar clic sobre el siguiente hipervínculo:
[**Github**](https://github.com/)

2. Si quieres evitar hacer lo de la llave para poder manejar los repositorios 
de manera local, tendrás que descargar la versión de escritorio de Github 
e instalarlo en tu equipo.
[**Github Desktop**](https://desktop.github.com/)

3. Cuando ya tienes una cuenta en Github debes crear un espacio o un repositorio con el nombre que haga referencia a tu proyecto, para éste
caso en especial, el repositorio se llamará **DocumentacionGithub** para desarrollarlo como ejemplo.

	3.1 Ir a nuestra cuenta creada en Github y darle clic sobre la sección **Repositories** y posterioemente darle clic en la sección **New** en color verde para crear un repositorio en Github.
	
	![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/ImagenesDocGit/CrearNewRepo.PNG?raw=true)
	
	3.2 Nos llevará al siguiente espacio
	
	![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/ImagenesDocGit/CrearNewRepo1.PNG?raw=true)
	
	- En el espacio indicado por el número 1 ponemos el nombre del repositorio o el de su proyecto.
	- En el espacio indicado por el número 2 podemos poner una breve descripción de lo que trata el repositorio.
	- En el espacio indicado por el número 3 debemos elegir entre la opción de privado o público, según lo más conveniente para la etapa en la que se encuentra el proyecto.
	- En el espacio número 4 elegimos que al momento de crear nuestro nuevo repositorio se agregue el archivo README.md, que es un archivo de texto, donde, por lo regular se describe mas a detalle de lo que trata el proyecto y lo que encontrarás en las carpetas y es editable.

	3.3 A continuación se encuentra una imagen para nuestro ejemplo con los espacios completos.

![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/ImagenesDocGit/CrearNewRepo2.PNG?raw=true)

3.4 Después de haber llenado los espacios, debemos darle en la sección verde.

![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/ImagenesDocGit/CrearNewRepo3.PNG?raw=true)

Y tendremos nuestro repositorio creado, resaltaré 3 puntos básicos de nuestro repositorio creado.

1. Nuestro nombre de usuario.
2. El nombre de nuestro repositorio.
3. El README.md que nos servirá para describir a detalle lo que hay en el repositorio, es como la introducción de un libro. 

![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/ImagenesDocGit/NewRepo.PNG?raw=true)

#### 2. Generando SSH Keys y agregarlo

**1.** En la esquina superior derecha desplegamos el siguiente recuadro.
	En el número 1 nos dirigimos al círculo donde está nuestra cuenta
	En el número 2 nos dirigimos a la sección **Settings**

![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/ImagenesDocGit/Settings.PNG?raw=true)

**2.** Al momento de darle clic en **Settings** nos desplegará otro recuadro.
En el número 1 nos dirigimos a una sección donde encontraremos información para crear la conexión **SSH** y la llave (**Keys**).

![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/ImagenesDocGit/SshAndKeys.PNG?raw=true)

**3.** Posteriormente nos saldrá otro recuadro.
Para mi caso ya tengo agregada una llave, por eso aparece una.
En el número 1 nos dirigimos a las letras celestes **generating SSH Keys**, ahí nos llevará directamente a la documentación donde está descrito paso a paso el proceso de crear una llave y agregarla.

![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/ImagenesDocGit/SshKeys.PNG?raw=true)

También está la opción de elegir el idioma español, si se nos complica la lectura en inglés.
En el número 1 damos clic y elegimos el idioma español.
![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/ImagenesDocGit/Idioma.PNG?raw=true)

**4.** En la página desplegada nos dirigimos al punto **Generar una nueva clave SSH y agregarla al ssh-agent**.
En el número 1 está la opción para hacer el proceso si usamos **Mac**
En el número 2 está la opción para hecer el proceso si usamos **Windows** (nuestro caso)
En el número 3 está la opción para hacer el proceso si usamos **Linux** (que será su caso)

![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/ImagenesDocGit/MacWindLinux.PNG?raw=true)

### Nota:
**Para el proceso de la llave deberán seguir los pasos de esa sección, no lo pondré porque sería repetir los pasos que están ahí, está todo muy bien explicado, es imposible que se pierdan en el paso a paso.**

### Hasta este punto, crearon un repositorio, crearon una llave y la agregaron. A continuación se encuentra un video del proceso desde Linux.

[**"Video" SSH And Key en Linux**](https://youtu.be/0P8YlYJO_DE)

#### 3. Seguir el ejemplo del repositorio "Sensor H2O" para las carpetas y el README.md

El repositorio **Sensor H2O** nos servirá como referencia para crear las carpetas de cada proyecto, en caso de que algún proyecto no cuente con algunos archivos, se recomienda subir las carpetas, aunque no tengan archivos para que posteriromente cuando le corresponda trabajar otra persona en el proyecto, trabaje en crear y subir los archivos faltantes, lo anterior, es con la intención de mantener los repositorios con la estructura del repositorio **Sensor H2O**.
Otra cosa que pudiese ayudar, es el **README.md** que ya tiene el repositorio, pueden seguir ese archivo para estructurar el suyo.
A continuación se encuentra el hipervínculo que nos dirige al repositorio de ejemplo para los otros proyectos:

[**Repositorio de ejemplo "Sensor H2O"**](https://github.com/AltamarMx/SensorH2O)

#### 4. Subír carpetas a GitHub usando la terminal virtual Git Bash en Windows

Para agregar carpetas a su repositorio creado, tendrán que seguir la guía que está en PDF, la podrán descargar e ir siguiendo los pasos sencillos pero tediosos.

[**PDF subir carpetas**](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/SubirCarpetas-a-Git-hub.pdf)

La guía en el hipervínculo de arriba es para poder descargarla en PDF, para poder trabajarla en su equipo, en Mac, Windows o Linux, según sea el caso, lo único que cambia es la terminal de cada sistema, pero básicamente los comandos son los mismos.
Además, si observas una opción de mejora en la guía del PDF, puedes aportar algo o modificar directamente en el archivo **SubirCarpetas-a-Guit-hub.md**, que básicamente es la misma guía pero en el intérprete Markdown, fácil de editar y la encontrarás en el siguiente hipervínculo.

[**.md subir carpetas**](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/SubirCarpetas-a-Guit-hub.md)

También, si tienes dudas en los pasos y seguramente alguna duda que no sea intuitiva de describir desde el PDF, he creado un video alojado en **Youtube** donde se realizan los pasos de la guía pero con algunos comentarios que seguramente te ayudarán, el video lo encontrarás en el siguiente hipervínculo.

[**"Video"Subir carpetas con la terminal en Windows**](https://youtu.be/nxXQTUPRClA)

#### 5. Subir carpetas a GitHub usando la terminal en Linux

Para subir carpetas a su repositorio desde la terminal de Linux, realicé un video y no describiré a detalle porque es básicamente lo mismo que en Windows, seguramente algo es diferente, pero se describe en el video de manera rápida. El video está en el siguiente hipervínculo:

[**"Video" Subir carpetas a Github desde Linux**](https://youtu.be/9z7DqhdOkKQ)

#### 6. Usar MEditor, página para crear documentos en intérprete Markdown, en sustitución de documentos PDF y Word para editarlos fácilmente.
La intención de crear la documentación en Markdown es para evitar usar los documentos en **PDF** y **Word** que puede resultar difícil al momento de querer editarlos, Markdown ofrece esa facilidad de poder modificar rápido y sin mayor complicaciones por la sencillez del editor que a continuación les presento. La principal ventaja es porque lo hace completamente compatible con la plataforma en Github y se puede editar directamente en la web, no es necesario que se descarguen los archivos para poder editarlos.
En donde se recomienda usar Markdown es en los siguientes documentos:
-  En manuales de operación de algún dispostitivo
-  En guías de algún proceso
-  Para hacer listas de materiales de algún dispositivo
-  Para describir procesos paso a paso
-  Instructivos
-  Tablas
- Entre otras cosas

**6.1** La página web que se usará es **MEditor.md**
Es una página web que nos ayuda a entender como funciona el intérprete en Markdown, yo lo relaciono a Word, es como el **"Word antiguo"**, yo digo que es como una versión de word muy básica, no tiene nada que ver pero así lo veo, es prácticamente lo mismo que editar el README de Github, sólo que en Github no está nada interactivo, si lo haces desde Github es porque ya conoces el intérprete o porque lo has usado anteriormente, pero considerando que no se ha usado, ni se conoce nada, considero que usar **MEditor.md** nos ayuda a entender como funciona.
La página web lo encontrarás en el siguiente hipervínculo.

[**MEditor.md**](https://pandao.github.io/editor.md/en.html)

Existen muchos editores en Markdown, pero creo que este es el más fácil de entender y de usar.
Viene ahí mismo en la web de MEditor un texto como ejemplo, de lo que se puede hacer con un documento o como crear uno.

La desventaja de usar **MEditor.md** es que no se pueden descargar los archivos o documentos que se van creando, mucho menos se pueden guardar, es por eso que se usa otra página web para poder guardar y descargar e incluso se pueden hacer otras cosas que se describirá mas adelante.

**6.2** Poner imágenes en **MEditor.md** (intérprete de Markdown).
Entre las cosas más importantes es poner imágenes, para eso se usa una línea de código, que es el siguiente:

![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/ImagenesDocGit/ComandoImagen.PNG?raw=true)

Para poder subir imágenes al documento que se está trabajando en Markdown, es necesario que nuestras imágenes se encuentren en la web, no importa en que sitio o página, pero sí deben estar sí o sí en la web, sobre todo porque se usa el link para poder poner imágenes, por ejemplo para poder usar las imágenes que están en este documento 
A continuación se muestra en un video el ejemplo:

[**"Video" Poner imagen en archivo de MEditor.md](https://youtu.be/AgF1dOBAX2U)

**6.3** Poner hipervínculos en sustitución de los links.
Otra de las cosas importantes y sobre todo por apariencia o estética de nuestro documento, es poner hipervínculos en los textos, para eso se usa la línea de cósdigo siguiente:

![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/ImagenesDocGit/ComandHipervin1.PNG?raw=true)

En las letras verdes se pone un nombre que haga referencia a lo que se quiera poner en hipervínculo, por ejemplo si es una carpeta, se pone el nombre de la carpeta, si es el nombre de alguna página en la web, se pondrá el nombre de lo que hay en la página o de lo que se quiera mostrar en dicha página, mientras mas corta sea la palabra, se verá mejor.
A continuación se encuentra un video como ejemplo:

[**"Video" Poner hipervínculo en un archivo de MEditor.md](https://youtu.be/C-dIVAyYkTc)

**6.4** Algunas herramientas útiles

![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/ImagenesDocGit/InterfazMEditor.PNG?raw=true)

- En el número 1 se encuentran las H´s que nos ayuda a elegir el tamaño de letra, el **H1** es el tamaño más grande y por lo regular se usan en los títulos y subtítulos, de izquierda a derecha el tamaño va disminuyendo hasta el **H6**.
- En el número 2 se encuentra solo unas viñetas para listar o para una serie de pasos, y son sólo círculos, pueden ser rellenos o vacíos, como en esta serie de indicaciones se está haciendo uso de ello.
- En el número 3 se encuentra la opción de poner números para una lista o para una serie de pasos donde el orden, sí es importante, es por eso que se puede enumerar dicha serie o indicaciones.
- El número 4 nos ayuda a realizar separaciones entre párrafos o se puede usar como indicador de fin e inicio de una hoja físicamente o una página.
- El número 5 nos da la opción de usar una tabla como en word, nosotros elegimos el número de columnas y filas, con la variente o desventaja que hay un límite de cuadros para poner en dicha tabla.

Entre las opciones que aparecen en el **MEditor.md** las que se encuentran señaladas arriba, son las que más usarán en algunos documentos que necesiten crear para sus proyectos.

** 7. Usar Dillinger, página web para poder guardar el documento creado con MEditor en Markdown, directo a nuestro equipo.**

El link de la página de **Dillinger** se encuentra en el siguiente hipervínculo.

[**Dillinger.io**](https://dillinger.io/)

![](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwp.notepm.jp%2Fwp-content%2Fuploads%2F2020%2F01%2Fdillinger1.png&f=1&nofb=1)

**Dillinger**, como se mencionó antes, nos ayudará a poder guardar el archivo que hemos creado en **MEditor.md**, después de haber terminado un archivo de texto en **MEditor.md** nos podemos ir a pegar el código de **MEditor.md** a **Dillinger**, es básicamente lo mismo, sólo que para empezar a entender como funciona un intérprete de Markdown, considero que es necesario hacerlo de esta forma, cuando dominen algunas cosas, ya no será necesario usar **MEditor.md** ni **Dillinger**, directamente podrán hacerlo en el archivo **README** que está en **Github**, a continuación se mostrarán algunas cosas interesantes de **Dillinger**.

- En el número 0 está la flecha que indica **name.md**, ahí nosotros podemos cambiar el nombre sin borrar el **.md**, depende de lo que se trate el texto, es el nombre que hará referencia a su archivo.
Justamente ahí debajo pegamos lo que hemos escrito en **MEditor.md** y del lado derecho nos mostrará el renderizado.

![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/Dillinger0PNG.PNG?raw=true)

- En el número 1 se encuentran opciones de previsualización del lado derecho, la que nos interesa es **Markdown**.

![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/ImagenesDocGit/Dillinger1.PNG?raw=true)

- En el número 2 (que no está indicado en la imagen) se encuentra la sección de exportar nuestro archivo en alguna de las 4 opciones que ahí aparecen. **Nosotros podemos hacer uso de esta sección para guardar localmente nuestro archivo**.

![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/ImagenesDocGit/Dillinger2.PNG?raw=true)

- En la sección número 3 podemos guardar nuestro archivo, de manera local.
**De la misma forma que la anterior, en esta sección podemos guardar nuestro archivo, se puede usar cualquiera de las 2**.

![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/ImagenesDocGit/Dillinger3.PNG?raw=true)

- En la sección número 4, podemos importar nuestros archivos, es decir podemos regresar a **Dillinger** para poder editarlo.

![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/ImagenesDocGit/Dillinger4.PNG?raw=true)

De **Dillinger**, las opciones mostradas arriba, son las más destacadas que estaremos usando en nuestros archivos **Markdown** o **.md**.
A continuación se muestra un video para usar **Dillinger** en nuestros archivos:

[**"Video" Usar Dillinger para guardar archivos creados en MEditor.md**](https://youtu.be/CVu9eHmeNpk)

** 8. Subir archivos desde la terminal en Windows, cuando ya tenemos carpetas en el repositorio**

Para subir archivos a tu repositorio cuando ya tienes carpetas, se puede hacer usando la terminal virtual en Windows de la siguiente forma:

[**"Video" Subir archivos a las carpetas de Github en Windows**](https://youtu.be/0T_jvGFOur0)

** 9. Subir archivos desde la terminal en Linux, cuando ya tenemos carpetas en el repositorio**

Para subir archivos a nuestras carpetas en Github, se puede hacer usando la terminal en Linux, el video de ejemplo es el siguiente:

[**"Video" Subir archivos a las carpetas de Github en Linux**](https://youtu.be/maWMFiRqe9k)

** 10. Subir archivos desde la web en Github, cuando ya tenemos carpetas en el repositorio**

En un video anteriormente se realizó el proceso usando Windows, en este video se muestra desde Linux, al ser desde la página web, no hay diferencia en el proceso entre los dos sistemas operativos, porque todo se realiza desde el repositorio en la web, el ejemplo se muestra a continuación:

[**"Video" Subir archivos a Github desde la web**](https://youtu.be/aZUFPbPD7BM)


------------

### ¡¡Están listos para crear el repositorio de su proyecto!!

------------

