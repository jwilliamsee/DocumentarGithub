# H2O-PRUEBA-JW

Este repositorio es una prueba de documentación del dispositivo H2O.

![](https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/Imagenes/LOGO-H2O.png?raw=true)

## Introducción

Compartiendo la idea de utilizar mas las energías limpias, se implementan nuevas formas de controlar los diferentes recursos que se utilizan durante el día en el Instituto de Energías Renovables (IER-UNAM), se implementarán dispositivos que puedan medir la cantidad de recursos que se consumen como lo son: el agua, la energía eléctrica, humedad, intensidad luminosa y temperatura de un edificio del instituto, con la intención de poder medir cada variable y posteriormente observar cuanto se consume para tratar de reducirlos en gran medida, lo anterior se lleva a cabo con dispositivos electrónicos que están integrados principalmente con sensores y haciendo uso de tecnologías abiertas para los programas y envío de datos a la plataforma Thingsboard para la representación gráfica de las variables.

## Estructura de los archivos

### Carpeta [CAD](https://github.com/jwilliamsee/H2O-PRUEBA-JW/tree/main/CAD)

En la carpeta CAD se encuentran los archivos .STEP del diseño de la carcasa realizado, hasta el momento en SolidWorks, la carcasa está diseñada en 3 partes: 1. La base de la carcasa, 2. La base media y 3. La tapa, para poder visualizar éstos archivos es necesario tener instalado algún software de diseño.

En la misma carpeta se encuentran planos de la carcasa en formato PDF y los archivos .STL para visualización.

### Carpeta [Diagramas](https://github.com/jwilliamsee/H2O-PRUEBA-JW/tree/main/Diagramas)

En la carpeta de Diagramas se encuentra el esquemático en .json, para visualizarlo o editarlo es necesario clonar el repo localmente, ir al software en versión online, sin crear cuenta, abrir el archivo desde la versión online.
También se encuentra el esquemático en PDF.

Se encuentran el dieño de PCB en .json, para editarlo es necesario abrirlo con el software EasyEDA, primero descargarlo y después abrirlo desde el software.

Para la representación gráfica de los componentes del dispositivo y conexión de los sensores, se encuentran los archivos con extensión .fzz, son los esquemas de conexión realizados en el software Open source Fritzing para conexión de 1 sensor y otro de 8 sensores.

En la carpeta también se encuentra un archivo .zip con lo necesario para maquinar el pcb.

### Carpeta [Imagenes](https://github.com/jwilliamsee/H2O-PRUEBA-JW/tree/main/Imagenes)

En esta carpeta están todas las imagenes que se usaron en los archivos de los manuales y otras imagenes necesarias para el complemento del dispositivo H2O, que en todas se mencionan en algún archivo existente en el repositorio.

### Carpeta [Manuales](https://github.com/jwilliamsee/H2O-PRUEBA-JW/tree/main/Manuales)

En esta carpeta se encuantran 3 archivos, 2 manuales y uno de errores:
1. El manual de operación, necesario consultarlo antes de iniciar con la replica del dispositivo.
2. El manual de ensamble, de manera gráfica (ilustrativa), se describe de forma general como realizar el ensamble de los componentes del dispositivo.
3. El otro archivo tiene algunas sugerencias de operación para operar el dispositivo H2O.

### Carpeta [Materiales](https://github.com/jwilliamsee/H2O-PRUEBA-JW/tree/main/Manuales)

En la carpeta "Materiales" se encuentran dos archivos con extensión md y otros en PDF.
1. En el archivo Lista_de_materiales_H2O se encuentran los materiales que ne necesitan para el pcb.
2. En el archivo ListaCostosH2O se encuentran los costos unitarios y total de los componentes.
3. Los archivos en PDF son hojas de datos de algunos componentes que se usan en el dipositivo H2O.

### Carpeta [SRC](https://github.com/jwilliamsee/H2O-PRUEBA-JW/tree/main/SRC)

En esta carpeta está el código para 8 sensores de agua, complemento de los otros códigos necesarios del dispositivo.

### Archivo [ChecklistH2O](https://github.com/jwilliamsee/H2O-PRUEBA-JW/blob/main/ChecklistH2O.md)

En este archivo se encuentra en forma de lista los documentos que el dispositivo H2O debe tener para su correcta operación.




