# **Presentacion ANT**
**Alumno:** Antonel, Gino

**Profesor:** Javier Guignard
***
# VUE JS

Vue.js es un framework progresivo, que sirve para construir interfaces de usuario. Es progresivo porque esta diseñado para ser cada vez mas adaptable, lo que hace mas facil su uso y la integracion de diferentes frameworks y librerias.
 
Caracteristicas: 
- Accesible
- Versatil y Escalable:
- Reactivo
- Optimizado
- Comunidad Muy Grande
***
# Instalacion:

```sh
$ npm install -g @vue/cli
$ vue create my-app
$ cd my-app
$ vue add vuetify      ---> En el caso que quieran usar este popular framework
```
> [Vuetify](https://vuetifyjs.com/es-MX/) 
***
# Tutorial:
1) Luego de instalar vuejs, el proyecto nos deberia quedar algo asi:

![](https://raw.githubusercontent.com/GinoAntonel/tutorialANT/master/imagenesTutorial/estructura.png)

2) Para empezar, tenemos que saber que Vuejs consta de componentes, cualquier cosa que le quieras agregar a tu pagina tiene que ser creado como un componente. Supongamos que queremos crear en nuestra pagina una Toolbar. Para hacer esto, primero tenemos que crear, adentro de la carpeta components, un archivo.vue. En este caso Toolbar.vue

![](https://raw.githubusercontent.com/GinoAntonel/tutorialANT/master/imagenesTutorial/crearArchivo.png)

3) Antes de empezar a programar nuestra Toolbar vamos a dejar en claro como funciona un archivo.vue. 
Este contiene 3 partes:

    **Template:** 
En el template nosotros vamos a poner lo que querramos que se vea en la pagina.
    **Script:**
En el script va la parte de JavaScript (funciones, etc).
    **Style:**
En el Style va la parte de CSS (Colores, fuentes, alineacion, etc).

![](https://raw.githubusercontent.com/GinoAntonel/tutorialANT/master/imagenesTutorial/archivoVue.png)

4) Una vez que ya tenemos en claro esto, vamos a empezar a hacer nuestra Toolbar. Para ahorrar tiempo, voy a utilizar una Toolbar pre-diseñada de nuestro plugin Vuetify.

![](https://raw.githubusercontent.com/GinoAntonel/tutorialANT/master/imagenesTutorial/toolbar.png)

5) Luego de guardar nuestra Toolbar, tenemos que registrar nuestro nuevo componente en nuestra app (App.vue). Este archivo va a ser el "Componente Padre", debido a que este es el componente renderizado.

![](https://raw.githubusercontent.com/GinoAntonel/tutorialANT/master/imagenesTutorial/app.png)

6) Para poder usar nuestra Toolbar primero vamos a tener que importar en la parte del Script nuestro componente que queremos utilizar.

![](https://raw.githubusercontent.com/GinoAntonel/tutorialANT/master/imagenesTutorial/import.png)

7) Una vez importado, tenemos que agregar en la parte dedl script nuestro componente Toolbar

![](https://raw.githubusercontent.com/GinoAntonel/tutorialANT/master/imagenesTutorial/componente.png)

8) Ahora, tenemos que agregar nuestro componente ya importado en la parte del template de nuestra app.

![](https://raw.githubusercontent.com/GinoAntonel/tutorialANT/master/imagenesTutorial/content.png)

9) Por ultimo, en nuestro archivo main.js tenemos que indicarle que tiene que renderizar nuestro App.

![](https://raw.githubusercontent.com/GinoAntonel/tutorialANT/master/imagenesTutorial/main.png)

10) Ahora para correr nuestra pagina, tenemos que ir a la terminar y ejecutar el siguiente comando:

![](https://raw.githubusercontent.com/GinoAntonel/tutorialANT/master/imagenesTutorial/run.png)
![](https://raw.githubusercontent.com/GinoAntonel/tutorialANT/master/imagenesTutorial/run2.png)

11) Entramos a localhost:8080 Y listo, ya tenemos nuestra Pagina Web.

![](https://raw.githubusercontent.com/GinoAntonel/tutorialANT/master/imagenesTutorial/local.png)

