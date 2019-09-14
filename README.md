# Repositorio para PRY

Este repositorio contiene la memoria, información extra y documentos ipynb a modo de prototipo, pruebas y resolución de problemas que se presentaron en la asignatura PRY.

## Instrucciones

Hay varias formas de visualizar el contenido extra de este repositorio. 

### A través del navegador, en github.

Esta forma, que podríamos decir estática, está fundamentada en la integración que ofrece Github con los archivos ipynb. Gracias a esta característica, se puede ir navegando archivo a archivo, en función de la necesidad y/o curiosidad.

### A través del navegador, con un servidor en local

Se puede instalar un servidor local que nos proporcione un entorno de trabajo interactivo. 
 
***Instalación del entorno:***

* Descargar e instalar “miniconda”  de [aquí](http://conda.pydata.org/miniconda.html).
* Abrir la consola de miniconda. Instalamos git escribiendo en la misma
```
conda install git
```
* Clona el repositorio con los archivos del proyecto escribiendo en consola 
```
git clone https//
```
* Navega hasta el directorio donde se encuentran los archivos
```
cd momoriaLCB\recursos\demos
```
* Crea y activa un nuevo entorno de trabajo. Escribe en consola
``` 
conda create -n pry_lcb python=3.6
activate pry_lcb
```
* Si todo va bien, el prompt (base) deberá ser sustituido por (pry_lcb)
* Instala los paquetes pytorch y torchvision
```
conda install pytorch-cpu -c pytorch
pip install torchvision
```
* Instala el resto de librerías necesarias usando el archivo de texto extra-libs.txt
```
pip install -r extra-libs.txt
```
Ahora ya está instalado todo lo necesario para que funcionen correctamente los ejemplos.
Si no has obtenido ningún error en la instalación ya deberías poder jugar con el código del prototipo. Para ello usa los siguientes comandos.
```
cd electro
jupyter notebook
```
A partir de aquí se debería de abrir el navegador y con el entorno de trabajo listo.
Una vez acabes de jugar con el código, para salir, y no dejar funcionando el servidor, pusla CNTRL+C sobre la ventana de la consola o simplemente cierrala.
Recuerda que cada vez que quieras experimentar con el código, debes activar el entorno de trabajo y navegar hasta el directorio electro. Ya no necesitarás hacer ninguno de los otros pasos.
