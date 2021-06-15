![](https://www.youtube.com/watch?v=Gn4EARNWdh0)

# Dispositivo medidor de caudal (H2O)
# 1.0 Introducción

El futuro de la humanidad y del planeta dependen de la manera en la que produzcamos energía: un sistema energético fiable, asequible y descarbonizado es fundamental.
Las energías renovables son fuentes de energía limpias, inagotables y crecientemente competitivas. Se diferencian de los combustibles fósiles principalmente en su diversidad, abundancia y potencial de aprovechamiento en cualquier parte del planeta, pero sobre todo en que no producen gases de efecto invernadero, causantes del cambio climático, ni emisiones contaminantes. Además, sus costes evolucionan a la baja de forma sostenida, mientras que la tendencia general de costes de los combustibles fósiles es la opuesta.
El crecimiento de las energías renovables es imparable, como queda reflejado en las estadísticas aportadas anualmente por la Agencia Internacional de la Energía (AIE): según las previsiones de la AIE, la participación de las renovables en el suministro eléctrico global pasará del 26% en 2018 al 44% en 2040, y proporcionarán 2/3 del incremento de demanda eléctrica registrado en este período, principalmente a través de las tecnologías eólica y fotovoltaica.
De acuerdo a la AIE, la demanda mundial de electricidad aumentará un 70% hasta 2040, elevando su participación en el uso de energía final del 18% al 24% en el mismo período, espoleada principalmente por regiones emergentes (India, China, África, Oriente Medio y el Sureste asiático).
Con lo anterior y compartiendo la idea de utilizar mas las energías limpias, se implementan nuevas formas de controlar los diferentes recursos que se utilizan en el día a día en el Instituto de Energías Renovables-UNAM, se implementarán dispositivos que puedan medir la cantidad de recursos que se consumen como lo son: el agua, la energía eléctrica, humedad, intensidad luminosa y temperatura de un edificio del instituto, con la intención de poder medir cada variable y posteriormente observar cuanto se consume para tratar de reducirlos en gran medida, lo anterior se lleva a cabo con dispositivos electrónicos que están integrados principalmente con sensores y haciendo uso de tecnologías abiertas para los programas y envío de datos a la plataforma Thingsboard para la visualización de gráficos.

### 1.1 Sobre los autores

|Nombre|Instituto/Organización|Email|
| ------------ | ------------ | ------------ |
|Guillermo Barrios del Valle|IER-UNAM|gbv@ier.unam.mx|
|Guillermo Ramírez Zúñiga|IER-UNAM|guraz@ier.unam.mx|
|Luis Fernando De Olarte Delgado|UTEZ|ferdeod16@gmail.com|
|Marco Antonio Morales Lagunes|UTEZ|marcostony001@gmail.com|
|Julio César Landa López|UTEZ|landajulioc@gmail.com|
|Miguel Ángel Gaspar|ITZ|miguel97gaz@gmail.com|
|Escobar Escobar José Williams|ITE|escobarescobarwilliams@gmail.com|

------------

# 2. Alcance

El dispositivo H2O tiene como alcance, en esta estapa, contar con toda la documentación necesaria para ser replicado de manera eficaz y eficientemente, después de ser trabajado por un grupo de personas se espera que el proyecto tenga todo lo que se necesesita para que otras personas puedan entender el funcionamiento y requisitos de operación.
La audiencia a la que está destinada es:
- Por el momento a personal del IER-UNAM que se encuentra trabajando en el proyecto "Edificios demostrativos de diseño bioclimático en clima cálido subhúmedo en el Instituto de Energías Renovables UNAM".
Proyecto número 291600 del Fondo de Sustentabilidad Energética.
- Compañeros que se interesen en aportar al proyecto para mejorar o para replicarlo directamente.

------------

# 3. Conceptos y definiciones

### 3.1 Saber como

Es necesario conocer algunas cosas antes de intentar entender muchos puntos del proyecto, como por ejemplo: lectura de planos electrónicos, diseño CAD, conocimiento medio de electrónica, programación, entre otras.

### 3.2 Diseño

Deberá manejar algún software de diseño por computadora, para modificar, replicar el diseño existente e incluso conocer la sección de ensamble de piezas en el software de su preferencia.

### 3.3 Hacer

Fabricar, construir, ensamblar, imprimir, configurar, programar y compilar códigos.

### 3.4 Open source

Por su traducción al español, "fuente abierta" durante el desarrollo del proyecto se busca que todos los programas a usar, sean de fuente abierta para evitar pagos costosos de Licencia, para cada necesidad existe un software de fuente abierta.

### 3.5 Thingsboard

Es una plataforma web que nos ayuda a visualizar gráficamente las variables que estamos midiendo para tener referencias de lo que se está haciendo.

### 3.6 Github

Plataforma web, que sirve como "bodega" para almacenar un proyecto con sus respectivas versiones o modificaciones que pueda sufirir durante el desarrollo, al mismo tiempo ayuda a documentar y a entender la estructura de su funcionamiento.

------------

# 4.0 Especificaciones de la estructura

### 4.1 Introducción

En esta sección se encuentra la estructura general del proyecto, de forma que sea entendible y que se le pueda dar seguimiento para la lectura del mismo y entender que lleva un orden.
Esta forma de estructurar el proyecto es un formato estándar de Open Know How, cabe mencionar que no es el ideal pero para entender de forma general un proyecto de electrónica es aceptable.
El almacenamiento en Github nos ayuda en todo momento a realizar modificaciones que creemos necesarias y sobre todo a tener control total de los cambios que va sufriendo el proyecto durante el desarrollo, si alguna no nos agrada o no es la correcta, podemos regresar sin ningún problema y dejarlo como antes.

### 4.2 Método de documentación

La documentación se realiza en lenguaje Markdown, es fácil de entender, práctico y cómodo, se recomienda que esta estructura se use para otros dispositivos solo para mostrar de manera general las partes que componen al proyecto, se puede usar como plantilla, los pasos que se siguieron para documentar son:

1. Utilizar el sitio web M Editor.md, es una web que nos ayuda a editar en Markdown, es Open source y muy fácil de entender para quienes no están familiarizados con editores de texto o crear páginas web para presentación de proyectos.

![](https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/Imagenes/M_Editor.PNG?raw=true)

	El sitio web está aquí:

https://pandao.github.io/editor.md/en.html

2. En la web M Editor.md no se pueden guardar dierectamente los archivos creados pero se puede copiar a otra web que si puede lo puede guardar en formato PDF, HTML, Markdown, entre otros, la ventaja de esta web, es que también se puede exportar directamente a Github, Google Drive, One Drive, Dropbox, etc., cualquiera de esas opciones lo hacen más completa. Por comodidad de la web y amigables con el usuario se usa primero M Editor.md y después la web de la que ya se describió, la se llama DILLINGER.
DILLINGER también es Open source y no es necesario crear cuenta para poder usarla.

![](https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/Imagenes/DILLINGER.PNG?raw=true)

	El sitio web de DILLINGER está aquí:

https://dillinger.io/

3. En este punto ya se puede guardar el archivo con extensión .md y guradar de manera local o directamente a Github.

### 4.3 Estructura

### 4.3.1 Formato

El formato de archivo para la documentación del dispositivo H2O es Markdown por su facilidad de uso.
Algunos archivos están en formato PDF pero es necesario para una mejor visualización de los esquemas que se muestran en ese formato.

### 4.3.2 Nombre del archivo

Para los nombres de los archivos, es necesario que no se usen comas, virgulilla o tilde de la ñ, las separaciones de las palabras pueden ser usadas con guiones o sin espacios, pero con una lestra mayúscula para saber donde termina e inicia otra palabra, por ejemplo: ArchivoEstructura".
Las extensiones de los archivos pueden ser:
- .json | Para los archivos que se realizaron con EasyEDA.
- .md | Para los archivos que son creados en formato de texto Markdown, M Editor, DILLINGER e incluso el archivo README de Github.
- .fzz | Para los archivos que fueron creados en el software de Fritzing, pictogramas de conexiones.
- .ESTEP | Para los archivos de diseño CAD, que pueden ser visualizados en cualquier software de diseño, es formato general.
- .STL | Para los archivos de impresión, para que el diseño de la carcasa del dispositivo pueda ser visualizado al momento de imprimirlo en 3D.
- .zip | Para los archivos de impresión de la placa o PCB, están comprimidos porque son varios archivos.
- .PDF | Para los archivos que si se guardan en otro formato, posiblemente se moverían mucho las líneas, formas, tablas, imagenes, etc. Los archivos que se encontrarán en el repositorio en este formato serán los planos para el diseño de la carcasa.

### 4.3.3 Vínculos

En algunas secciones de la documentación es necesario nombrar o hacer referencias a rutas externas, pueden ser a imagenes, páginas web entre otras, simplemente se hace uso de los links originales de la web en cuestión, copiando y posteriormente pegando en la sección correspondiente para no tener que buscar de manera externa, deberán dejar espacios entre título o texto para que no existan errores de posición en el archivo de texto final.
Para hacer vínculos a imagenes se deberá hacer de la siguiente forma:
Primero el signo de admiración, después los corchetes y al final los paréntesis, entre éstos últimos se debe poner la dirección web de la imagen.
![](Aquí va la dirección de la imagen)

#### 4.3.4 Ubicación del repositorio

El repositorio de todo el proyecto se encuentra en Github, para esta versión de prueba y antes de ser almacenado en el repositorio original, las diferentes carpetas y archivos están alojadas en un un solo repositorio, no existe una carpeta raíz, pero sí existe una dirección raíz y es la siguiente:
**Esta dirección web cambiará cuando los archivos pasen al repositorio original.**

![](https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/Imagenes/LogoGithub.jpg?raw=true)

https://github.com/jwilliamsee/H2O-PRUEBA-JW

### 4.4 Información de la web

La página de presentación del proyecto, por el momento está en la sección de Github llamada Wiki, para dejar en claro el formato de documentación de manera más amigable con el usuario que desea agregar información.
Existe un sitio web para documentar pero en formato json o XML, un nivel de formatos avanzados y que requieren conocimiento del tema para usarlo, es un formato estándar con una estructura sencilla para proyectos electrónicos.
La web se llama OManual.

![](https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/Imagenes/OManual.PNG?raw=true)

El link del sitio web es el siguiente:

https://www.omanual.org/standard.php

Existe otro sitio llamado Open Know-How, que se usa para darle una presentación a un proyecto, no es específicamente para proyectos electrónicos o similares, pero tiene una estrutura completa para documentar cualquier proyecto, el formato usado es yml y también es necesario conocer del tema para aprovechar todo lo que ofrece.
Cabe mencionar que al ser Open source, también está alojado en Github con las diferentes versiones y colaboradores.

![](https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/Imagenes/OpenKnow-How.PNG?raw=true)

El sitio web del formato estándar para documentar es el siguiente:

https://app.standardsrepo.com/MakerNetAlliance/OpenKnowHow/wiki

### 4.5 Propiedades descriptivas

### 4.5.1 Título

##### Dispositivo H2O
##### Medidor del consumo de agua

### 4.5.2 Descripción

##### Energías renovables
##### Dispositivo pensado para el uso de medición del consumo de agua y preservar el cuidado del recurso en edificaciones, donde existe gran demanda del mismo

### 4.5.3 Uso previsto

##### Control de variable
###### Informa al usuario el consumo de agua de un lugar donde existe gran consumo del recurso, puede ser cuantificado para conocer exactamente en que momento se ha consumido mas y con base a esa información pueden aplicarse estrategias para mantener un consumo menor o aplicar ciertas medidas que ayuden a disminuirlo.

### 4.5.4 Palabras clave

##### H2O
##### Electrónica
##### Dispositivo
##### Medidor de caudal

### 4.5.5 Precauciones y recomendaciones
Son recomendaciones para operar el dispositivo H2O, pueden existir más, pero eso depende del usuario, pueden surgirle diferentes dudas, a unos más que a otros.
En este link hay algunos que pueden ayudar:

https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/ErroresAndSoluciones/ErroresAndSoluciones.md

### 4.5.6 Contacto primario

**Inv. A tiempo completo:** Dr. Guillermo Barrios del Valle
**Email:** gbv@ier.unam.mx

**Posdoc.:** Dr. Guillermo Ramírez Zuñiga
**Email:** guraz@ier.unam.mx

### 4.5.7 Colaboradores

**Nombre:** Luis Fernando De Olarte Delgado
**Instituto:** Universidad Tecnológica Emiliano Zapata (UTEZ)
**Email:** ferdeod16@gmail.com

**Nombre:** Marco Antonio Morales Lagunes
**Instituto:** Universidad Tecnológica Emiliano Zapata (UTEZ)
**Email:** marcostony001@gmail.com

**Nombre:** Julio César Landa López
**Instituto:** Universidad Tecnológica Emiliano Zapata (UTEZ)
**Email:** landajulioc@gmail.com

**Nombre:** Miguel Ángel Gaspar
**Instituto:** Instituto Tecnológico de Zacatepec (ITZ)
**Email:** miguel97gaz@gmail.com

**Nombre:** Escobar Escobar José Williams
**Instituto:** Instituto Tecnológico de Ensenada (ITE)
**Email:** escobarescobarwilliams@gmail.com

### 4.5.7 Imagen

Representación gráfica del dispositivo H2O

![](https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/Imagenes/LOGO-H2O.png?raw=true)

### 4.5.8 Etapa de desarrollo

La estapa en la que se encuentra el desarrollo del dispositivo H2O, es la de documentación, se espera que sea la penúltima etapa, para poder ser replicado de forma eficiente y eficaz.

### 4.5.9 Fue hecho físicamente

El dispositivo si se ha hecho de forma práctica, es decir, se ha llevado a la práctica para comprobar el funcionamiento del mismo, solo como pruebas de funcionamiento, el dispositivo completo y funcionando durante largos períodos de tiempo no se ha realizado, falta montarlo completo, que mida hasta en 8 conexiones de agua y con su respectiva carcasa de protección.

### 4.5.10 Se ha comprobado la documentación

La réplica del dispositivo usando la estrutura aquí mostrada y siguiendo la documentación no se ha realizado, aún está en revisión de estructura de documentación y de archivos factibles para el desarrollo eficiente.

### 4.5.11 Estándares usados

El estándar de documentación completo, no se ha seguido, pero si se ha usado el estándar para esta documentación de Open Know-How, algunos puntos se han omitdo porque al no ser la estructura para documentar proyectos electrónicos, existen puntos que salen sobrando o que definitivamente no aplican para este tipo de proyectos.
El link del estándar usado es el siguiente:

https://app.standardsrepo.com/MakerNetAlliance/OpenKnowHow/src/branch/master/1#a40dfa47-8bff-4e28-9338-3f808ddfe6ae

### 4.6 Documentación

### 4.6.1 Punto de entrada de la documenatación:

https://github.com/jwilliamsee/H2O-PRUEBA-JW

### 4.6.2 Archivo de documentación

https://github.com/jwilliamsee/H2O-PRUEBA-JW/wiki

### 4.6.3 Archivos de diseño

Carpeta **CAD**
En esta carpeta se encuentran los diseños CAD en formato general (.STEP).

![](https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/Imagenes/CarcasaH2O.PNG?raw=true)

https://github.com/jwilliamsee/H2O-PRUEBA-JW/tree/main/CAD

Carpeta **pcb**
En esta carpeta se encuentra el diseño del PCB en el software EasyEDA con extensión (.json).
Cabe mencionar que será necesario descargarlo localmente y así visualizarlo en la versión online de EasyEDA.

![](https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/pcb/DimensionesPCBH2O.PNG?raw=true)

https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/pcb/PCB_H2O.json

### 4.6.4 Esquemas

Carpeta **Diagramas**
El diagrama esquemático del dispositivo H2O se encuentra en formato (PDF).

https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/Diagramas/Dispositivo_H2O_Esquem%C3%A1ticoA.pdf

En la misma carpeta se encuentra el esquemático realizado en EasyEDA en formato (.json).
También es necesario descargarlo localmente y abrirlo desde la versión online.

https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/Diagramas/Dispositivo%20H2O%20Esquem%C3%A1tico%23.json

### 4.6.5 Pictogramas

### Pictogramas de conexión

Carpeta **Pictogramas_1S_8S**
En esta carpeta se encuentran los archivos de los pictogramas.
Para 1 sensor:

![](https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/Pictogramas_1S_8S/Pictograma_1S_H2O.PNG?raw=true)

El software usado es Fritzing, se puede usar la versión online y no es necesario crear cuentas, el archivo se encuentra con extensión (.fzz).

https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/Pictogramas_1S_8S/YF-S201.fzz

Para 8 sensores:

![](https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/Pictogramas_1S_8S/Pictograma_8S%20H2O.PNG?raw=true)

Es necesario usar Fritzing para poder visualizarlo y poder editar.

https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/Pictogramas_1S_8S/SensorH2O-PCB.fzz

### 4.6.7 Materiales

### Lista de materiales

Carpeta **Materiales**
En esta carpeta se encuentra un archivo con extensión (.md).
Se encuentra una tabla con la lista de materiales.

https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/Materiales/Lista_de_materiales_H2O.md

### Lista de costos de materiales

Carpeta **MaterialesCostos**
En esta carpeta existe un archivo con entensión (.md).
Se encuentra una tabla con la lista de costos unitario y total de los materiales.

https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/MaterialesCostos/Lista_de_costos_H2O.md

### 4.6.8 Herramientas

### Lista de herramientas
No es necesario contar con muchas herramientas para el uso del dispositivo H2O, pero se menciona de manera general en el Manual de ensamble, algunas herramientas se omiten porque son obvias que deben usarse.
En el punto 3 del manual de ensamble se hace mención: **Herramientas necesarias**.

### 4.6.9 Instrucciones de operación

Carpeta **Manuales**
En esta carpeta existe un archivo con extensión (.md), en la que se encuentra el Manual de operación, donde hay información como por ejemplo: instalar python, diagrama para montar el dispositivo y hacer pruebas, hacer uso del ESP8266, cargar los códigos para el funcionamiento del dispositivo, crear espacio de visualización gráfica de la variable a medir (agua), calibrar el sensor con cantidades establecidas, entre otras cosas.
Este manual debe ser el primero en leer.

https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/Manuales/ManualDeOperacion.md

También en esta carpeta se encuentra otro archivo con extensión (.md), en la que se encuentra el Manual de montaje o ensamble del dispositivo H2O.

https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/Manuales/Manual%20de%20Montaje.md

### 4.6.10 Archivos de fabricación

Carpeta **ARCHIVO_GERBER_PCB**
En esta carpeta se encuentra el archivo gerber para la fabricación del PCB del dispositivo, se encuentra con extensión (.zip).

![](https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/Imagenes/VsuperiorPCBH2O.PNG?raw=true)

![](https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/Imagenes/VinferiorH2OPCB.PNG?raw=true)

https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/ARCHIVO_GERBER_PCB/Gerber_PCB_H2O.zip

Carpeta **STL**
En esta carpeta se encuentran los archivos con extensión (.STL).
Son necesarios para poder visualizar el diseño al momento de fabricar la carcasa del dispositivo H2O.

https://github.com/jwilliamsee/H2O-PRUEBA-JW/tree/main/STL

Carpeta **Planos**
En esta carpeta se encuentran archivos con extensión (.PDF).
Son los planos para el diseño de las tres partes que conforman la carcasa del dispositivo H2O.
**1. Base de la carcasa**

![](https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/Imagenes/BaseCarcasa.PNG?raw=true)

https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/Planos/BASE_CARCASA_H2O_PLANO.PDF

**2. Base media de la carcasa**

![](https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/Imagenes/BaseMediaCarcasa.PNG?raw=true)

https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/Planos/BASE_MEDIA_H2O_PLANO.PDF

**3. Tapa de la carcasa**

![](https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/Imagenes/TapaCarcasa.PNG?raw=true)

https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/Planos/TAPA_H2O_PLANO.PDF

### 4.6.11 Software

Carpeta **SCR**
En esta carpeta se encuentra el código para operar hasta 8 sensores del dispositivo H2O.
El único archivo a reemplzar de todos los códigos es el **main.py**, al momento de cargar los códigos al ESP8266, los otros códigos se cargan completos.

https://github.com/jwilliamsee/H2O-PRUEBA-JW/tree/main/SRC

### 4.7 Lenguaje

**4.7.1 General**
El lenguaje de la presentación y desarrollo del proyecto es:
***Español-latinoamérica***

**4.7.2 Idioma de la documentación**
***Español-latinoamérica***

# 5.0 Bibliografía

[1] Open Know-How
https://app.standardsrepo.com/MakerNetAlliance/OpenKnowHow/src/branch/master/1#a40dfa47-8bff-4e28-9338-3f808ddfe6ae

[2] Github
https://github.com/

[3] EasyEDA
https://easyeda.com/editor

[4] Fritzing
https://fritzing.org/

[5] DILLINGER
https://dillinger.io/

[6] M Editor.md
https://pandao.github.io/editor.md/en.html

























