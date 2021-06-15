# Pasos para subir carpetas a Github

**Como sugerencia, cada vez que les pida crear una contraseña o algo como eso, donde ustedes tengan que pensar en alguna palabra, anoten esa palabra en una libreta o en un archivo de texto en la computadora para que no se les olvide y ponerle un título o una indicación de que trata o para que sirve dicha frase o palabra, así llevan un control de lo que van haciendo sin olvidarse, porque en algunos pasos es necesario regresar al link anterior o salir y volver**
##### 1. Hacer una cuenta y crear un espacio en Github
#### Crear la llave para trabajar sin problemas el repositorio de manera local

Es una forma de trabajar el repositorio de manera local sin tener que pedir permisos y sin tener que insertar contraseñas cada vez que se usa el repositorio o cuando se trabaja uno nuevo, solo es necesario hacer esta conexión ssh cuando se crea una nueva cuenta en Github o si se quiere trabajar el repositorio de manera local desde otra equipo de cómputo y se hace una sola vez.
##### 2. Lo primero que debe realizarse es ir al siguiente link.

https://docs.github.com/es/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/#generating-a-new-ssh-key
Que como dice el texto al entrar al link, es para generar una nueva clave SSH y agregarla al ssh-agent, está la opción para Mac, Windows y Linux, de preferencia deberá hacerse en Linux, para mi caso, lo que les presenté en la videollamada fue todo en Windows porque para mi es mejor trabajar en ese sistema, debido a que el proyecto en el que estoy, prácticamente es todo sobre documentacion y uso mucho word, pdf, en general la paquetería office.
##### 3. Lo siguiente, después de hacer lo que dice en las instrucciones, será ir al siguiente link, que es el último punto (3) del link anterior.

Agregar la clave SSH a tu cuenta de Github.
https://docs.github.com/es/articles/adding-a-new-ssh-key-to-your-github-account
Aquí es donde se agrega la llave generada en el paso 2 a la cuenta de Github.
##### 4. Cuando ya se realizó los puntos anteriores sin ningún problema, prácticamente estamos listos para agregar carpetas a nuestro repositorio.

Lo primero, es crear una carpeta de manera local en la computadora, para este ejemplo lo haré en el escritorio **Desktop** sin crear carpeta, directamente el repositorio al escritorio, la carpeta puede llamarse como gusten, dentro de esa carpeta se clonará el repositorio que ya tenemos creado, hasta ahorita sin ningún archivo, solo el README, que el repositorio crea por default.
Entrar e su carpeta creada y clonar ahí el repositorio, de la siguiente manera,
en sus terminale Linux, básicamente son los mismos comandos:

![](https://github.com/jwilliamsee/Pruebadocumentacion/blob/main/GuitBashTerminal.PNG?raw=true)

![](https://github.com/jwilliamsee/Pruebadocumentacion/blob/main/CdDesktop.PNG?raw=true)

Entrar a la carpeta creada (si crearon una), en mi caso clonaré directamente el repositorio al escritorio.
Con el comando:
git clone seguido del link copiado de su repositorio, ejemplo:

![](https://github.com/jwilliamsee/Pruebadocumentacion/blob/main/LinkRepo.PNG?raw=true)

**git clone https://github.com/jwilliamsee/Pruebadocumentacion.git**

Presionar Enter y el respositorio será clonado, cuando se haya copiado podrán acceder a él.
**cd Pruebadocumentacion/**
Después, para verificar que no hay nada mas que el README.md, pueden listar con **ls** y aparecerá solo el README, en mi caso al mismo tiempo que voy haciendo este instructivo, voy agregando imagenes, por eso a mi me aparecen algunas, pero hasta el momento no tengo carpetas.

![](https://github.com/jwilliamsee/Pruebadocumentacion/blob/main/MainRepo.PNG?raw=true)

Como pueden ver en la imagen anterior cuando acceden al repositorio clonado, entran al original, se dan cuenta porque aparece (main) en color azul, anteriormente aparecía (máster), se ha actualizado.
Ahora se pueden ir a su escritorio y comprobar que efectivamente, el repositorio ya se encuentra en nuestro equipo.

![](https://github.com/jwilliamsee/Pruebadocumentacion/blob/main/RepoEscritorio.PNG?raw=true)

La carpeta que aparece señalada con la flecha no debe modificarse porque es la del repositorio "virtual"por llamarlo de alguna forma.

##### 4. Ahora deberán trabajar con las carpetas y sus archivos desde su computadora.

Deberán tener las carpetas que previamente ya vieron en mi repositorio de prueba (https://github.com/jwilliamsee/H2O-PRUEBA-JW), esas carpetas son las que debe llevar cada repositorio, en caso de no tener algo cuando su proyecto haya concluido, deberán dejar solo la carpeta para que posteriormente lo trabajen otras personas.
Lo que sigue es crear las carpetas en el repositorio local, de acuerdo a la estructura, con los nombres sin acentos o cualquier otro caracter.

![](https://github.com/jwilliamsee/Pruebadocumentacion/blob/main/CarpetasEnRepo.PNG?raw=true)

Cada carpeta debe contener un archivo para que pueda subirse al repositorio original en Github, en el ejemplo no tienen archivos del proyecto, solo tiene 1 archivo de texto cada carpeta para poder subirse.

##### 5. Ahora regresamos a la terminal para poder subir esas carpetas.

![](https://github.com/jwilliamsee/Pruebadocumentacion/blob/main/CarpetasLocal.PNG?raw=true)

Como pueden ver en la terminal al actualizar con el comando **git pull**
y después listar con **ls** aparecen las carpetas que previamente agregamos, hasta aquí, no hemos subido nada a nuestro repositorio en Github, solo agregamos carpetas de manera local.

Ahora con el comando git add seguido del nombre de la carpeta se agrega al repositorio en Github.
**git add CAD**
Se pueden agregar de manera individual o todo con:
**git add .**
De preferencia que sea individual seguido de lo que se indica a continuación.

![](https://github.com/jwilliamsee/Pruebadocumentacion/blob/main/AddCarpetas.PNG?raw=true)
Después hacemos un "punto de seguridad" o creamos un punto para poder recuperar en caso de requerirlo con:
git commit -m "primeros archivos", dentro de las comillas el texto que indique lo que hicimos.

**git commit -m "agregue carpetas"**

![](https://github.com/jwilliamsee/Pruebadocumentacion/blob/main/guitcommit.PNG?raw=true)

Nos aseguramos d "poner" lo que queremos subir a Github online, con:
**git push**

![](https://github.com/jwilliamsee/Pruebadocumentacion/blob/main/CarpetasSubidas.PNG?raw=true)

## ¿Cómo compruebo que realmente subí mis carpetas?

Se pueden ir al repositorio en Github y actualizar la página.

![](https://github.com/jwilliamsee/Pruebadocumentacion/blob/main/RepoActualizado.PNG?raw=true)

**Ahora que agregaron sus carpetas ya saben como agregar sus archivos, el procedimiento es prácticamente el mismo, de copiar y pegar desde su computadora y después ir agregando a su repositorio en la web**

Para eliminar la carpeta del repositorio que ha quedado en su computadora, se puede hacer con el comando rm -rf "nombre de la carpeta" sin comillas:
Antes de ejecutar el comando, deberán retroceder un paso, es decir, regresar al escritorio para poder borrar el repositorio, si lo hacen desde el repositorio les marcará error y no podrán borrarlo
Con el comando cd .. retroceden un paso.
**cd ..**
Ahora si pueden borrarlo.
**rm -rf Pruebadocumentacion"**
Para borrar archivos cuando se encuentren trabajando en el repositorio, no es necesario retroceder, solo para borrar la carpeta de manera local del repositorio.

![](https://github.com/jwilliamsee/Pruebadocumentacion/blob/main/BorrarCarpeta.PNG?raw=true)

# ¡¡Eso es todo!! Han agregado archivos a su repositorio.

