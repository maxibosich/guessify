# guessify
Trabajo práctico PROG3 - SPA

### Objetivo
Desarrollar un juego con formato de una aplicación de una sola página (Single Page Application), en el que a través del catálogo de Spotify se reproduzcan treinta segundos de una canción aleatoria y haya que elegir la portada del álbum al que corresponde de entre cuatro opciones posibles. Los aciertos y los errores se contabilizarán mientras dure la sesión de juego.

La aplicación utilizará las herramientas de desarrollo provistas por Spotify (https://developer.spotify.com/), principalmente la Spotify Web API, basada en principios REST y cuyo formato de intercambio de datos es JSON. 
La idea es que en cada partida del juego, se genere aleatoriamente una canción y su correspondiente álbum, más tres álbumes aleatorios que no contengan la canción. Esta información será obtenida del catálogo de Spotify.
Además, se guardará el número de respuestas correctas o incorrectas mientras el usuario se mantenga jugando con la aplicación.
