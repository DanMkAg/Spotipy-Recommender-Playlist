# Spotipy-Recommender-Playlist
***INSTRUCCIONES***
Recomendador de canciones en Spotify creado con la librería Spotipy de python.
La idea principal de este sistema de recomendación es generarar una lista de reproducción (o playlist) que contenga canciones similares a los gustos musicales de un usuario de Spotify.
Usaremos la API de Spotify para acceder al listado de canciones más escuchadas por el usuario, así como para generar un listado de canciones similares, que posteriormente filtraremos para elaborar la lista de reproducción deseada.
Utilizaremos un filtrado basado en contenido, para crear la lista de reproducción de canciones recomendadas, y finalmente subiremos la playlist a la plataforma de Spotify.
Para ello en primer lugar tendremos que loguearnos con nuestro usuario habitual de Spotify, en la web de desarrolladores de Spotify https://developer.spotify.com/ y crear una nueva API, donde nos facilitarán nuestro 'Client ID' y el 'Secret Token' para poder conectar con la API de Spotify, y ahí mismo deberemos especificar una 'URI', que es una dirección de respuesta, donde Spotify nos mandará unos términos de seguridad que tendremos que aceptar. Esta dirección que no es necesario que sea en la nube, puede ser local por ej. 'http://localhost:8080/'
Luego crearemos un ususario dentro de la API con una verificación de nuestro email, y ya tendremos lista nuestra API de Spotify, para conectarla con nuestro código python.
***INSTRUCTIONS***
Spotify Playlist Recommender created with Spotipy Python Library
The main idea of this recommender system is to generate a playlist that contains similar songs to the most listened music of a Spotify user.
We will use the Spotify API to access to the list of songs most listened by the user, as well as to generate a list of similar songs, which we will later filter to create the desired playlist.
We will use content-based filtering to create the playlist of recommended songs, and finally we will upload the playlist to the Spotify platform.
To do this, first of all we will have to log in with our regular Spotify user password, on the Spotify developers website https://developer.spotify.com/ and create a new API, where it will provide us our 'Client ID' and the 'Secret Token' to be able to connect with the Spotify API, and there we must specify a 'URI', which is a response address, where Spotify will send us some security terms that we will have to accept. This address, does not need to be in the cloud, could be a local address, for example. 'http://localhost:8080/'
After this we will have to create a user inside the API with a verification of our email, and we will have our Spotify API ready, to connect it with our python code.
