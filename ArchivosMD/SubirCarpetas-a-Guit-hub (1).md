## Este es un repositorio donde encontrarás información sobre como documentar tu proyecto en Github.

#### Contenido

** 1. Crear un espacio en Github**

**2. Generando SSH Keys y agregarlo**

** 3. Subír carpetas a GitHub usando la terminal virtual Git Bash en Windows**

** 4. Subir carpetas a GitHub usando la terminal en Linux**

** 5. Usar MEditor, página para crear documentos en intérprete Markdown, en sustitución de documentos PDF y Word para editarlos fácilmente**

** 6. Crear carpetas en nuestro equipo para subirlas Github siguiendo el repositorio de prueba**

** 7. Poner hipervínculos, en sustitución de links completos en el documento de Markdown**

** 8. Insertar imagénes en el documento de Markdown**

** 9. Usar Dillinger, página web para poder guardar el documento creado con MEditor en Markdown, directo a nuestro equipo**

** 10. Subir archivos desde la terminal en Windows, cuando ya tenemos carpetas en repositorio**

** 11. Subir archivos desde la terminal en Linux, cuando ya tenemos carpetas en repositorio**

** 12. Subir archivos desde la web en Github, cuando ya tenemos carpetas en el repositorio**


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
	
	![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/CrearNewRepo.PNG?raw=true)
	
	3.2 Nos llevará al siguiente espacio
	
	![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/CrearNewRepo1.PNG?raw=true)
	
	- En el espacio indicado por el número 1 ponemos el nombre del repositorio o el de su proyecto.
	- En el espacio indicado por el número 2 podemos poner una breve descripción de lo que trata el repositorio.
	- En el espacio indicado por el número 3 debemos elegir entre la opción de privado o público, según lo más conveniente para la etapa en la que se encuentra el proyecto.
	- En el espacio número 4 elegimos que al momento de crear nuestro nuevo repositorio se agregue el archivo README.md, que es un archivo de texto, donde, por lo regular se describe mas a detalle de lo que trata el proyecto y lo que encontrarás en las carpetas y es editable.

	3.3 A continuación se encuentra una imagen para nuestro ejemplo con los espacios completos.

![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/CrearNewRepo2.PNG?raw=true)

3.4 Después de haber llenado los espacios, debemos darle en la sección verde.

![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/CrearNewRepo3.PNG?raw=true)

Y tendremos nuestro repositorio creado, resaltaré 3 puntos básicos de nuestro repositorio creado.

1. Nuestro nombre de usuario.
2. El nombre de nuestro repositorio.
3. El README.md que nos servirá para describir a detalle lo que hay en el repositorio, es como la introducción de un libro. 

![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/NewRepo.PNG?raw=true)

#### 2. Generando SSH Keys y agregarlo

**1.** En la esquina superior derecha desplegamos el siguiente recuadro.
	En el número 1 nos dirigimos al círculo donde está nuestra cuenta
	En el número 2 nos dirigimos a la sección **Settings**

![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/Settings.PNG?raw=true)

**2.** Al momento de darle clic en **Settings** nos desplegará otro recuadro.
En el número 1 nos dirigimos a una sección donde encontraremos información para crear la conexión **SSH** y la llave (**Keys**).

![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/SshAndKeys.PNG?raw=true)

**3.** Posteriormente nos saldrá otro recuadro.
Para mi caso ya tengo agregada una llave, por eso aparece una.
En el número 1 nos dirigimos a las letras celestes **generating SSH Keys**, ahí nos llevará directamente a la documentación donde está descrito paso a paso el proceso de crear una llave y agregarla.

![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/SshKeys.PNG?raw=true)

También está la opción de elegir el idioma español, si se nos complica la lectura en inglés.
En el número 1 damos clic y elegimos el idioma español.
![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/Idioma.PNG?raw=true)

**4.** En la página desplegada nos dirigimos al punto **Generar una nueva clave SSH y agregarla al ssh-agent**.
En el número 1 está la opción para hacer el proceso si usamos **Mac**
En el número 2 está la opción para hecer el proceso si usamos **Windows** (nuestro caso)
En el número 3 está la opción para hacer el proceso si usamos **Linux** (que será su caso)

![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/MacWindLinux.PNG?raw=true)

### Nota:
**Para el proceso de la llave deberán seguir los pasos de esa sección, no lo pondré porque sería repetir los pasos que están ahí, está todo muy bien explicado, es imposible que se pierdan en el paso a paso.**

### Hasta este punto, crearon un repositorio, crearon una llave y la agregaron.

#### 3. Subír carpetas a GitHub usando la terminal virtual Git Bash en Windows

Para agregar carpetas a su repositorio creado, tendrán que seguir la guía que está en PDF, la podrán descargar e ir siguiendo los pasos sencillos pero tediosos.

[**PDF subir carpetas**](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/SubirCarpetas-a-Git-hub.pdf)

La guía en el hipervínculo de arriba es para poder descargarla en PDF, para poder trabajarla en su equipo, en Mac, Windows o Linux, según sea el caso, lo único que cambia es la terminal de cada sistema, pero básicamente los comandos son los mismos.
Además, si observas una opción de mejora en la guía del PDF, puedes aportar algo o modificar directamente en el archivo **SubirCarpetas-a-Guit-hub.md**, que básicamente es la misma guía pero en el intérprete Markdown, fácil de editar y la encontrarás en el siguiente hipervínculo.

[**.md subir carpetas**](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/SubirCarpetas-a-Guit-hub.md)

También, si tienes dudas en los pasos y seguramente alguna duda que no sea intuitiva de describir desde el PDF, he creado un video alojado en **Youtube** donde se realizan los pasos de la guía pero con algunos comentarios que seguramente te ayudarán, el video lo encontrarás en el siguiente hipervínculo.

[**Video subir carpetas**](https://youtu.be/nxXQTUPRClA)

#### 4. Subir carpetas a GitHub usando la terminal en Linux

#### 5. Usar MEditor, página para crear documentos en intérprete Markdown, en sustitución de documentos PDF y Word para editarlos fácilmente.
La intención de crear la documentación en Markdown es para evitar usar los documentos en **PDF** y **Word** que puede resultar difícil al momento de querer editarlos, Markdown ofrece esa facilidad de poder modificar rápido y sin mayor complicaciones por la sencillez del editor que a continuación les presento. La principal ventaja es porque lo hace completamente compatible con la plataforma en Github y se puede editar directamente en la web, no es necesario que se descarguen los archivos para poder editarlos.
En donde se recomienda usar Markdown es en los siguientes documentos:
-  En manuales de operación de algún dispostitivo
-  En guías de algún proceso
-  Para hacer listas de materiales de algún dispositivo
-  Para describir procesos de paso a paso
-  Instructivos
-  Tablas
- Entre otras cosas

**5.1** La página web que se usará es **MEditor.md**
Es una página web que nos ayuda a entender como funciona el intérprete en Markdown, yo lo relaciono a Word, es como el **"Word antiguo"**, yo digo que es como una versión de word muy básica, no tiene nada que ver pero así lo veo, es prácticamente lo mismo que editar el README de Github, sólo que en Github no está nada interactivo, si lo haces desde Github es porque ya conoces el intérprete o porque lo has usado anteriormente, pero considerando que no se ha usado, ni se conoce nada, considero que usar **MEditor.md** nos ayuda a entender como funciona.
La página web lo encontrarás en el siguiente hipervínculo.

[**MEditor.md**](https://pandao.github.io/editor.md/en.html)

Existen muchos editores en Markdown, pero creo que éste es el más fácil de entender y de usar.
Viene ahí mismo en la web de MEditor un texto como ejemplo, de lo que se puede hacer con un documento o como crear uno.

La desventaja de usar **MEditor.md** es que no se pueden descargar los archivos o documentos que se van creando, mucho menos se pueden guardar, es por eso que se usa otra página web para poder guardar y descargar e incluso se pueden hacer otras cosas que se describirán en el siguiente punto.

**5.2**

**5.3** Poner imágenes en **MEditor.md** (intérprete de Markdown).
Entre las cosas más importantes es poner imágenes, para eso se usa una línea de código, que es el siguiente:

![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/ComandoImagen.PNG?raw=true)

Para poder subir imágenes al documento que se está trabajando en Markdown, es necesario que nuestras imágenes se encuentren en la web, no importa en que sitio o página, pero sí deben estar sí o sí en la web, sobre todo porque se usa el link para poder poner imágenes, por ejemplo para poder usar las imágenes que están en este documento 

**5.4** Poner hipervínculos en sustitución de los links.
Otra de las cosas importantes y sobre todo por apariencia o estética de nuestro documento, es poner hipervínculos en los textos, para eso se usa la línea de cósdigo siguiente:

![](https://github.com/jwilliamsee/DocumentacionGithub/blob/main/ComandHipervin1.PNG?raw=true)

En las letras verdes se pone un nombre 

