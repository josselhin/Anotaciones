# Nuevo Curso Definitivo de JavaScript

Quiero darte la bienvenida a este nuevo Curso Definitivo de JavaScript. Esta será la segunda vez que hacemos este curso y, con el que podrás hacer Desarrollo JavaScript full-stack. Cuando hacemos un Curso Definitivo quiere decir que te enseñamos todos lo que necesitas saber para trabajar con una herramienta en el mundo real.

En este nuevo curso tendrás a **Mike McNeil**, creador de **Sails.js**, como tu profesor. Con Mike estructuramos el siguiente temario pensando en qué es lo que él le enseñaría a alguien que va a entrar a trabajar en su equipo.

## Con este curso podrás:
* Construir una aplicación con Node.js y Sails.js
* Integrar tu app con Vue.js
* Incorporar Stripe y Mailgun a tu app
* Aprender a trabajar con equipos de desarrollo y propiedad de código.

## Temas:

* Node.js, usos del día a día
* Async/Await
* Buenas prácticas en el manejo de errores
* Sails.js 1.0
* Forms y Ajax
* Arquitectura UI moderna basada en Vue.js
* Auth y permisos
* Integración con Stripe para pagos
* Integración con Mailgun para emails automatizados
* Deploy con Heroku
* Cuándo usar Single Page Apps
* Seguridad web con CSRS/XSS
* Server-side reder seguro
* Uso de frameworks Frontend con Node.js y Sails.js
* Promesas, callbacks y flujo de control
* Cómo pasar de requerimientos, a casos de uso y a código

## Requerimientos previos:

* [Programación Básica](https://platzi.com/clases/programacion-basica/) (Conceptos de programación)
* [Desarrollo web online](https://platzi.com/clases/html5-css3/) (HTML, CSS, JS)
* [Git y GitHub](https://platzi.com/clases/git-github/) (npm)

Si quieres puedes [ver la parte Frontend versión pasada del curso](https://platzi.com/clases/javascript-pro-2016/), y la parte de [Backend también](https://platzi.com/clases/node-2016/).

Pronto anunciaremos la fecha de lanzamiento de este nuevo curso.

# Introducción y generalidades del curso


Hola soy Mike McNeil, vamos a hablar sobre JavaScript, no solo el lenguaje, pero sobre cómo crear aplicaciones con él.

Soy el creador de Sails, que es como un Ruby on Rails pero para JavaScript.
Tengo un negocio de creación de aplicaciones para diversas empresas.

El enfoque de este curso es precisamente crear aplicaciones para JavaScript. Vamos a utilizar las últimas tecnologías en JS y terminaremos con el desarrollo de una app desde el diseño hasta su producción.

Los prerequisitos para este curso son:

* Fundamentos de programación
* Conocimientos en HTML, CSS, and experiencia con JS
* Conocimientos básicos de cómo usar NPM and GitHub

# Las tecnologías que vamos a usar
Hablemos un poco acerca de las tecnologías que vamos a usar en este curso y por qué vamos a usarlas. JavaScript es un lenguaje que vamos a usar por la capacidad que tiene de adaptarse a distintos proyectos.

En este curso vamos a usar:

* ECMA Script
* NodeJS
* Stripe
* VueJS
* Mailgun
* Heroku

[Repositorio de clonacion](https://github.com/mikermcneil/ration) 


# Lo que vamos a construir
En este curso vamos a desarrollar un proyecto para facilitar rentar elementos de amigos. Nos concentraremos en crear la parte técnica de una aplicación desarrollada a través de JavaScript.

Overview del curso:

* Configuración
* Los esenciales
* Creando funcionalidades a la medida
* Crecimiento y monetización
* Yendo a producción

# Evitando errores en tu código
En este material te enseño acerca de cómo evitar bugs en nuestro código y para eso te muestro cuáles son las configuraciones para el entorno.

Lo primero que hacemos es usar folder_exclude_patterns para evitar perder los cambios que realicemos. Además, te muestro las mejores formas de configurar tu entorno para evitar cualquier tipo de contratiempo.

# Usando la terminal en este proyecto

Ahora vamos a ir a la Terminal, aquí te voy a mostrar cómo usarla para nuestro proyecto.

A muchas personas que están aprendiendo código les recomiendo que cambien el color de la terminal para que la luz no lastime sus ojos.

# Usando GitHub en nuestro proyecto
Cuando hablamos sobre las versiones de código podemos enfocarnos en usar Git para guardarlas.

En este material te enseño cómo usar GitHub para nuestro proyecto, sus configuraciones básicas. Te muestro cómo crear una repo y por qué es mejor trabajar con repos en lugar de la terminal.

Les recomiendo bajar la aplicación web de GitHub con la que podremos guardar nuestras verisones.


# Instalando nuestras plataformas y dependencias

```
npm install eslint -g
```

```
npm install sails -g

sails new ration //nombre de la aplicacion

cd ration //ingresas a la carpeta

```
Ejecutas:
```
sails lift
```
[Abres el navegador](http://localhost:1337)

[Curso de JavaScript Full Stack con Sails.js: configuraciones - extensiones](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20JavaScript%20Full%20Stack%20con%20Sails.js#configuraci%C3%B3n-de-vs-code)

[ration:repositorio](https://github.com/mikermcneil/ration)

[Curso de JavaScript Full Stack con Sails.js](https://github.com/MineiToshio/CursosPlatzi/tree/master/Curso%20de%20JavaScript%20Full%20Stack%20con%20Sails.js)

[commits](https://github.com/MineiToshio/CursosPlatzi/commits?author=MineiToshio)

[nano-chat](https://github.com/stackbuilders/nano-chat)

[developers.google](https://developers.google.com/web/updates/2019/01/devtools)

[Fragmentos de Sails.js](https://marketplace.visualstudio.com/items?itemName=OsirisFrik.sails-js-snippets)

# Arquitectura Backend
En esta sección vamos a ver arquitectura, autentificación y las configuraciones generales de la plataforma de Sails.

Comenzamos con la exploración de la plataforma, te muestro las opciones que tienes para configurar la internacionalización de tu aplicación.

Dentro del Homepage de la plataforma vas a encontrar todas las funcionalidades que tienes dentro de Sails. Comandos, la API, redirects, etc.

[sails.config.session
](https://sailsjs.com/documentation/reference/configuration/sails-config-session)


# Arquitectura Frontend
El frontend que tenemos por defecto en nuestra aplicación. Por defecto tienes todo desactivado, pero de acuerdo con las necesidades de tu aplicación podrás hacer cambios y configuraciones específicas.

Exploramos todos los folders disponibles para que hagas modificaciones en el frontend de tu app.

# Parasails.js
Lo que hace es darnos un empaque para el uso de VueJS.

Te muestro algunas de las funcionalidades que tiene SailsJS para que las configures de acuerdo con lo que necesitas en tu app.

# Como subir un proyecto local a github.

```
git init

git add .

git commit -m "first commit"

git remote add origin https://github.com/NOMBRE_USUARIO/NOMBRE_PROYECTO.git

git push -u origin master

//ERROR FATAL: Solution
$ git remote set-url origin git@github.com:ppreyer/first_app.git


```
# Parasails (by Mike McNeil)
En este video vamos a ver qué es Parasails y cómo funciona para la creación de apps. Lo que hace es darnos un empaque para el uso de VueJS.

Te muestro algunas de las funcionalidades que tiene SailsJS para que las configures de acuerdo con lo que necesitas en tu app.

Estructuras livianas para aplicaciones con más de una página. Construido encima de Vue.js .

Si bien se puede usar con cualquier sistema de módulos, esta biblioteca no depende de Webpack, Babel, Gulp, Grunt, Brunch o cualquier otro sistema de compilación o transpiler. Es 2.96KB minificado y comprimido gzip (o 27KB sin comprimir).

Uso
Fuera de la caja, parasails admite:

páginas
componentes
utilidades
constantes
Además de algunas integraciones opcionales:

Vue Router (para enrutamiento del lado del cliente / “páginas virtuales”)
jQuery (para this.$get(), this.$find()y this.$focus())

``` javascript 
< div  id = " página de inicio "  v-cloak >
  < h1 > {{welcomeMessage}} </ h1 >
  < botón  autofocus @ click = " clickButton () " > Haga clic en mí </ button >
</ div >

```

``` javascript
parasails.registerPage('página de inicio',{
  datos:{
    welcomeMessage: ' '
  },
  beforeMount: function(){
     this.welcomeMessage = '¡Hola mundo!';
  },
  montado: función(){
     esto.$focus('[enfoque automático]');
  },
  métodos:{
     clickButton: function(){
       this.welcomeMessage = '¡Ow que duele!';
    }
  }
});
```

dependen
assets, js , pages 
veras cada vista en cada accion de vista hay un archivo page .js

assets, dependecies.parasails.js
nos da cierta estructura para las paginas, renderizadas del servidor, caracteristicas de la aplicacion que son nuevas.

Paginas virtuales: enrutamiento del lado del cliente.
