# Latam-Puzzle

Latam Puzzle es un juego donde existe varios rompecabezas de diferentes países, donde el objetivo es resolver los distintos puzzles que representan un lugar icónico de un país, además de ofrecer un dato curioso respecto a este.

Para modificar el programa es necesario del software de desarrollo:

- GDevelop

## Instalación GDevelop desktop

Para instalar GDevelop es necesario ir al Link oficial, donde descargamos el software de acuerdo a nuestro Sistema Operativo 

[Descargar | GDevelop](https://gdevelop.io/es-es/download)

> "La versión en la que se desarrolló el juego es GDevelop 5.4.211. Se espera que sea compatible con versiones posteriores.”
> 

## Estructura

Dentro del proyecto encontramos las siguientes carpetas y archivos

![image.png](image.png)

Obviando el archivo .gitignore por razones obvias, tenemos otros 2 archivos 

### Rompecabezas

Este archivo es el archivo principal del proyecto. Contiene todos los datos relacionados con el juego, como escenas, objetos, eventos, configuraciones, etc. Es decir ess la representación estructurada del juego en formato JSON, que GDevelop utiliza para cargar y trabajar con el proyecto.

### Rompecabezas.json.autosave

Este es un archivo de respaldo que GDevelop genera automáticamente. Contiene una copia del archivo principal del proyecto `Rompecabezas.json` El propósito de este archivo es permitir la recuperación de tu trabajo en caso de que algo salga mal. GDevelop hace un autoguardado cada ciertos intervalos de tiempo

### layouts

Esta carpeta  contiene los archivos relacionados con las escenas del juego. En GDevelop, una escena es un espacio donde ocurre una parte del juego, como un nivel o una pantalla específica . Cada archivo dentro de esta carpeta representa una escena diferente, y puede incluir configuraciones específicas de los objetos, su posición inicial, capas, cámaras, y otros elementos relacionados con la disposición de la escena.

### eventsFunctionsExtensions

Aquí es donde se almacenan las extensiones de funciones de eventos que hayas creado o añadido a tu proyecto. Las extensiones de funciones en GDevelop te permiten agrupar eventos en funciones reutilizables, lo que facilita la organización y reutilización de lógica en diferentes partes del juego. 

### assets

La carpeta `assets` está organizada en subdirectorios que clasifican los distintos recursos utilizados para el desarrollo y la ejecución del juego. Estos recursos incluyen imágenes para botones, animaciones, elementos gráficos, sonidos, fuentes, y más.

![image.png](image%201.png)

## Inicialización

Para poder trabajar, solo debemos abrir nuestro GDevelop y en Archivo, seleccionamos abrir, lo que abrirá nuestro explorador de Windows, vamos a el lugar donde hayamos clonado este repositorio y abrimos la carpeta Creada, finalmente solo seleccionamos el Archivo Rompecabezas y podremos iniciar a modificar

![image.png](image%202.png)

## Escenas

> "Cada escena se compone de dos partes: una dedicada a los eventos y otra a los elementos gráficos.”
> 

En la pestaña dedicada a los elementos gráficos podemos colocar nuevos elementos con diferentes comportamientos o características

![image.png](image%203.png)

Por el otro lado en la pestaña de los eventos colocamos triggers que disparan una acción concretra de alguno de los elementos existentes. Los eventos se puede ordenar y juntar para formar eventos mucho más complejos y elaborados.

![image.png](image%204.png)
