# TEST EXAMEN



API para obtener datos de Tareas.

  - Desarrollado con Javascript
  - NodeJS
  - MongoDB Atlas

# Publicacion de la API!

  - Se publicó en Heroku.
  - Se agrega reposotorio GIT
### Repositorio:
Repositorio [Git](https://github.com/gilhdez79/apitareas)  | Repositorio [Heroku][PlHe]


### Cracion entorno de desarrollo

```sh
Test API Postman
```
## 1. Instalación y preparación del entorno (ejemplo)
Lo primero que tenemos que hacer es descargarnos el ejecutable de   de la web oficial [https://nodejs.org](http://nodejs.org) para proceder con la instalación.

 Una vez terminado tendremos disponibles los siguientes elementos en nuestra máquina:

    nodejs. 
    
Core a través del cual podremos ejecutar nuestras aplicaciones en servidor escritas en `javascript npm`. Gestor de paquetes a través del cual gestionaremos nuestras dependencias
Para verificar que la instalación se ha realizado de forma correcta bastará con hacer
```    sh
    node -v
    v6.11.0
```
##2. Creación del proyecto
Utilizamos las conocidos módulos `express y express-generator `  para generar la estructura de nuestro proyecto web.

Los instalamos de forma global.

    npm install -g express
    npm install -g express-generator

Finalmente creamos nuestro proyecto que denominamos     **NodeJsMongoDBHelloWorld**
    
    express NodeJsMongoDBHelloWorld
Quedando una estructura de carpetas tal que así:



En el fichero `package.json` se defines los módulos que vamos a necesitar en nuestra aplicación.

     {
       "name": "nodejsmongodbhelloworld",
       "version": "0.0.0",
       "private": true,
       "scripts": {
    	"start": "node ./bin/www"
       },
     "dependencies": {
     "body-parser": "~1.17.1",
     "cookie-parser": "~1.4.3",
     "debug": "~2.6.3",
     "express": "~4.15.2",
     "jade": "~1.11.0",
     "morgan": "~1.8.1",
     "serve-favicon": "~2.4.2"
       }
     }

Dichas dependencias deben ser instaladas para que se puedan ser utilizadas en tiempo de compilación. Para ello bastará con hacer:

    npm install
Una vez finalizado el comando anterior deberíamos ver los diferentes módulos descargados en el directorio `node_modules`



## 3. Arranque del proyecto
Para arrancar nuestra primera aplicación node es suficiente con ejecutar el siguiente comando desde un terminal situándonos en la raiz del proyecto.

    npm start
y entrar en la url [http://localhost:3000](http://localhost:3000)