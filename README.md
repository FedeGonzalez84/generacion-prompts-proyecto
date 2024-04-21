# Proyecto final Generación de Prompts - (CoderHouse)

## Titulo del proyecto

Generación de playlist con contenido educativo en Spotify utilizando a OpenAI como sistema de recomendación.

## Presentación de la idea

La idea de este proyecto surge de la necesidad de proporcionar a los niños un acceso fácil y divertido a contenido educativo a través de plataformas de streaming de música como Spotify.

Muchos padres y educadores enfrentan el desafío de encontrar contenido adecuado y educativo para los niños, y esta iniciativa busca abordar esta necesidad utilizando tecnologías de inteligencia artificial.

## Propuesta de la solución
**Selección de contenido educativo:** Utilizare OpenAI, específicamente gpt, para sugerir una lista de canciones infantiles con propósitos educativos específicos, cómo aprender el abecedario, los colores, números, entre otros.

**Comunicación con la API de Spotify:** Una vez que tengamos la lista de canciones sugeridas, nos comunicaremos con la API de Spotify para crear una nueva playlist y agregar estas canciones a ella.

**Generación de un logo para la playlist**: Utilizare DALL-E, una red neuronal generativa desarrollada por OpenAI, para crear un logo único y atractivo para la playlist. 
Este logo será diseñado teniendo en cuenta el tema educativo de la playlist y se generará automáticamente.

#### Prompts a utilizar:

**Obtener lista de canciones**
- **system:** `Vas a asumir el rol de experto en educación para niños con vastos conocimientos en contenido educativo y multimedial.`
  
- **user:** `Eres un asistente útil para generar listas de reproducción. Deberías generar una lista de canciones y sus artistas según la indicación que se solicita. Debes ser claro, exacto y basarte en la información que contengas almacenada. Deberás devolver un array JSON, donde cada elemento sigue este formato:`
  ```json
  [
    {
      "song": "<song_title>",
      "artist": "<artist_name>"
    }
  ]
En este caso, el ejemplo de user, esta utilizando al técnica **one shoot prompt**

