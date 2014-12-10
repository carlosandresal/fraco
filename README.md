#Blog Francisco Coronel
Trabajo Grupal 2 - Desarrolladores Frontend

###Scaffolding

Generado con Yeoman - [webapp generator](https://github.com/yeoman/generator-webapp)

Dependencias
- Node
  - [sitio de descarga](http://nodejs.org/)
- Bower
  - npm install -g bower
- Grunt
  - npm install -g grunt-cli 
- Sass

**Nota:** en mac siempre que se usa el comando npm se debe agregar el comando sudo por delante para dar permisos desuper usuario

Ej: sudo npm install


###Empezando

Clonar el repositorio

> git clone https://github.com/CoderHouse/fraco.git

Instalar las dependencias

> cd fraco

> npm install

> bower install

###Corriendo el proyecto

> grunt serve

Crea un servidor y abre una nueva pestaña en el navegador con la url: *http://localhost:3000*

**Nota:** La carpeta *app* contiene codigo fuente del sitio

###Compilando el proyecto

> grunt build

Crea una nueva carpeta en el root del proyecto con el nombre **dist**, dejando aquí la versión final para deployar en cualquier hosting

