# LOLA

Arena de héroes en pixel art medieval para jugar desde el celular o el PC, contra bots o con amigos online.

## Cómo jugar con amigos

1. Uno abre el juego, escribe su nombre y toca **Crear sala**. Aparece un código de 4 letras.
2. Elige el modo: **1v1**, **2v2** o **Todos contra todos**. Si faltan jugadores, puede agregar bots.
3. Los demás abren el mismo link, escriben su nombre y el código y tocan **Unirse**. También pueden entrar directo con **Compartir enlace**.
4. El anfitrión toca **Empezar partida**.

El celular del anfitrión calcula la partida, así que conviene que sea el que tenga mejor señal y lo dejen con la pantalla encendida.

## Archivos

- `index.html`: el juego completo, en un solo archivo.
- `manifest.webmanifest` e `icon.svg`: para instalarlo como app ("Agregar a pantalla de inicio").

Para la conexión online usa PeerJS (conexión directa entre navegadores). No necesita servidor propio.
