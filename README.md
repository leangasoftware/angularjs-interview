# Entrevista AngularJS

![](http://1.bp.blogspot.com/-uNfuY3pPyQs/VKcqR1SFGvI/AAAAAAAAEkU/VnkEmnk0s_k/s1600/AngularJS_logo.svg.png)

Bienvenido a tu prueba de __AngularJS__, a continuación encontrarás una serie de requerimientos con los cuales deberás realizar un ejercicio práctico.

La prueba general se divide en pequeños ejercicios con los cuales se evaluará en práctica:
- Pensamiento lógico.
- Resolución de problema.
- Tiempo de desarrollo.
- Entre otros.


Finalizada la prueba recuerda enviar link del proyecto o tu repositorio a [desarrollo@leangasoftware.es](mailto:desarrollo@leangasoftware.es) con tu información de contacto y en el asunto colocar: 
__ANGULAR-JS-INTERVIEW__


> Recomendación: No importa terminar todos los ejercicios, lo más importante es la funcionalidad del ejercicio resuelto(s).

### Contexto:
Vamos a construir una app que contara con tres(3) vistas, la primera vista "Home" contendrá una lista de top canciones más escuchadas. También obtendremos una vista de "detalle" con su ruta amigable donde mostraremos la información del artista de la canción y una vista "mi perfil" donde tendremos guardado nuestros artistas favoritos, para facilitar la prueba usaremos "localStorage" del navegador para almacenar esta información.

### Antes de empezar:
- La data a consumir proviene de [Last.fm](https://www.last.fm/)
- Ver claves de conexión [Ver](https://gist.github.com/leifermendez/7f58f09792b0893982155a7fcfa4d9be)
- Endpoints disponiles [Ver](https://www.last.fm/api/)
- EndPoint [getTopTracks](https://www.last.fm/api/show/geo.getTopTracks)

# Ejercicios

### 1. Home.
![](https://i.imgur.com/fdo6hTM.png)

__REQUERIMIENTO:__
Se requiere una vista "HOME" donde muestre en cuadrícula las canciones TOP por país pueden usar el país de su preferencia.

- Vista principal  __TOP_TRACKS_LIST__ 
	- RUTA: `/home` 
- Vista detalle __ARTIST_DETAIL__
	- RUTA: `/artis/{id}`
- Vista __404__
	- RUTA: `/404`
	- HTML: A tu gusto.
	- __NOTA:__ Debes poder re-direccionar rutas que no existan a `404`

___
### 2. Componentes.
![](https://i.imgur.com/Y6tU5up.png)

__REQUERIMIENTO:__
Se requiere hacer un componente que se use en la vista de detalle realizada en el ejercicio #1, en el cual mostremos los artistas similares:
Ejemplo `  <similar-artist artis="id"></similar-artist>`
___

### 3. LocalStorage
![](https://i.imgur.com/IVdbZJv.png)

__REQUERIMIENTO:__
Como no estamos usando una base de datos, vamos a usar el localStorage del navegador, cuando estemos en la pantalla de "detalle" tendremos la opción de guardar en mis favoritos para posteriormente ven en la pantalla de "mi perfil"

### 4. Vista (Mi Perfil)

![](https://i.imgur.com/nV1w1du.png)

__REQUERIMIENTO:__
En la pantalla "mi perfil" debemos mostrar todos los artistas que marcamos como "favoritos" y colocar una opción para poder borrarlos.

### Extra.
Si has llegado hasta este punto, y consideras que tienes tiempo se valora el hecho de que puedas desplegar tu proyecto en [Heroku](https://www.heroku.com/) o en cualquier servidor de tu gusto.

Gracias por participar! 
