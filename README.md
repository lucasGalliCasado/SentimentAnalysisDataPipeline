#Base de datos de Analisis de Sentimiento

Usando Pandas, Selenium y la API de OpenAI el programa scrapea noticias relevantes de google news y luego analiza su sentimiento y carga la informacion relvante en un archivo xlsx.

Variables a tener en cuenta

"queries": las key nos dan un separacion categorcas de los temas y sus values son los temas que se buscaran bajo dicha categoria

"x-path": Determina la cantidad de articulos que el programa intentara obtener para cada tema.

"cantDias": Acota la cantidad de dias de vejez de las notas que el programa busca
 
El analisis de sentimiento es hecho por ChatGPT y sus posibles valores son "positivo","negativo" y "nuetral", esto puede modificarse facilmente cambiando el prompt presente en el codigo.
