
# Estilización de Imágenes (Demostración)
Para esta demostracion se necesitaron varias cosas:
1. Entrenar el modelo de redes convolucionales con pytorch para la estilización de imagenes
https://github.com/pytorch/examples/tree/master/fast_neural_style

2. Guardar estos modelos pre-entrenados en formato .pt

3. Uso de nodejs y expressjs para el montaje de un mini servidor y despligue de una aplicacion web

4. La integracion de libtorchjs para utilizar pytorch mediante el uso de javascript en el navegador

## Uso
![Image Style Transfer with Node.js](/docs/screenshot.png?raw=true "Image Style Transfer with Node.js")

Demostracion: https://nodejs-style-transfer.herokuapp.com

## Meritos 
se agradece al trabajo realizado por el usuario Vova Manannikov.
gracias por sentar las bases y la inspiracion para llevar acabo este proyecto.

## Ejecucion
### Linux or Windows
descargar o clonar el repositoro para despues ejecutar los siguientes comandos dentro de la carpeta del proyecto 
```
$ npm i
$ npm run start
```
abrir en tu navegador la siguiente direccion: http://localhost:3000/