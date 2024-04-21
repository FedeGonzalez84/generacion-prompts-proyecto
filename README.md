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
- **system:** _Vas a asumir el rol de experto en educación para niños con vastos conocimientos en contenido educativo y multimedial._
- **user:** Necesito que me proporciones un top 10 de canciones en Spotify para niños entre 1 y 5 años (rango de edad) que faciliten el aprendizaje del abecedario (temática a aprender). Este contenido debe encontrarse en español y necesito que me lo muestres en forma tabulada, donde la primera columna muestre el nombre de la canción y como segunda columna quién es el autor de dicho tema. Enfócate principalmente en que la canción contenga la temática que se quiere enseñar al niño.


