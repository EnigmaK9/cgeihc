# cgeihc
Este repositorio contiene ejemplos básicos de OpenGL del laboratorio de computación gráfica.

## Requisitos
Para compilar y ejecutar el programa es necesario tener instalados los siguientes paquetes:

g++
freeglut3-dev
En sistemas basados en Debian/Ubuntu se pueden instalar con el siguiente comando:

csharp

sudo apt-get install g++ freeglut3-dev

## Compilación y ejecución
Para compilar el programa, se puede utilizar el siguiente comando:

g++ -c -o main.o main.cpp -Iinclude
g++ -o main main.o -L/usr/lib -lglut -lGLU -lGL

El primer comando compila el archivo main.cpp y genera un archivo objeto main.o. El segundo comando enlaza los archivos objeto y genera el archivo ejecutable main.

Para ejecutar el programa, simplemente hay que ejecutar el archivo main:

./main

## Referencias
Documentación de OpenGL
Documentación de GLUT
Tutorial de OpenGL y GLUT en C++

## Licencia
Este programa se distribuye bajo la licencia MIT. Puedes ver los detalles en el archivo LICENSE.
