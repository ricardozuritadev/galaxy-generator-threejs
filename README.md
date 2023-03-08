<h1 align="center">Generador de galaxias con Three.js</h1>

![Screenshot_20230308_101523](https://user-images.githubusercontent.com/84975927/223684151-8ed253df-6051-4301-b664-b3726641a54c.png)


![JavaScript](https://img.shields.io/badge/JavaScript-20232A?style=for-the-badge&logo=javascript&logoColor=F0DB4F)
![TrheeJs](https://img.shields.io/badge/Threejs-20232A?style=for-the-badge&logo=trianglel&logoColor=F0DB4F)
![HTML5](https://img.shields.io/badge/html5-20232A?style=for-the-badge&logo=html5&logoColor=f06529)
![CSS3](https://img.shields.io/badge/css3-20232A?style=for-the-badge&logo=css3&logoColor=2965f1)

## Índice

* [Descripción del proyecto](#descripción-del-proyecto)

* [Instalación](#instalación)

* [Características del proyecto y demostración](#características-del-proyecto-y-demostración)

* [Tecnologías y librerías utilizadas](#tecnologías-y-librerías-utilizadas)

* [Autor](#autor)

## Descripción del proyecto
Este es mi primer proyecto utilizando WebGL con la librería Three.js.
Se trata de un generador de galaxias, el cual implementa un panel de control con el que se puede modificar sus distintos parámetros. Dependiendo de los parámetros se obtendrán diferentes tipos de galaxias.

## Instalación
El proyecto ha sido desplegado en Vercel y se puede acceder en la siguiente URL:

https://galaxy-generator-threejs-psi.vercel.app/

Para ejecutarlo en local, clonar el repositorio e instalar las dependencias con el comando:
~~~
npm i
~~~

Para lanzar el proyecto, utilizar el comando:
~~~
npm run dev
~~~

## Características del proyecto y demostración
![galaxy1](https://user-images.githubusercontent.com/84975927/223682216-9b7a3188-1b7b-4052-9bbf-8e87e8f94146.gif)
![galaxy2](https://user-images.githubusercontent.com/84975927/223682407-20726331-7158-452d-9de3-42e6a8eb9268.gif)
![galaxy3](https://user-images.githubusercontent.com/84975927/223682448-800fc606-ad03-49f7-bc5e-7291ebd05da8.gif)


## :hammer:Parámetros que se pueden controlar:

- `count`: Controla el número de estrellas de la galáxia (partículas).
- `size`: Controla el tamaño de las estrellas (partículas).
- `radius`: Controla la longitud de las ramas de la galaxia.
- `branches`: Controla la cantidad de ramas de la galaxia.
- `spin`: Controla la curvatura de las ramas de la galaxia.
- `randomness`: Controla la aleatoriedad de las estrellas.
- `randomnessPower`: Controla la dureza de la aleatoriedad. 
- `insideColor`: Controla el color interior de la galaxia.
- `outsideColor`: Controla el color exterior de la galaxia.

## Tecnologías y librerías utilizadas

* HTML5

* CSS3

* JavaScript

* WebGL

* Three.js

## Autor
[<img src="https://avatars.githubusercontent.com/u/84975927?v=4" width=115><br><sub>Ricardo Zurita</sub>](https://github.com/ricardozuritadev)

Proyecto realizado en el curso Three.js Journey de Bruno Simon
