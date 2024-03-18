## Uso de la API de Rick & Morty

![Logo R&M](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b1/Rick_and_Morty.svg/1280px-Rick_and_Morty.svg.png)

Este repositorio utiliza la API de Rick and Morty para obtener datos de personajes y crear un DataFrame con sus características. El notebook ``rickandmorty.ipynb`` realiza solicitudes HTTP a la API y procesa los datos recibidos para generar un DataFrame de Pandas con información detallada sobre los personajes. Este DataFrame es posteriormente procesado para proporcionar un correcto análisis de los datos.

#### ¿Qué es una API? :arrows_counterclockwise: 

Las APIs (Application Programming Interfaces) actúan como intermediarios entre dos aplicaciones, permitiendo que una aplicación solicite datos o servicios de otra de manera estructurada y controlada. 

#### Funcionalidades del repositorio

- **Consulta la API de Rick and Morty para obtener datos de personajes**. Para ello utiliza la función ``obtener_datos_personajes()`` para obtener datos de personajes de la API de Rick and Morty. Esta función utiliza la biblioteca ``requests`` para realizar solicitudes GET a la API de Rick and Morty. Inicia un bucle while para solicitar datos de personajes mientras la condición se cumpla. Finalmente, devuelve una lista de personajes y sus características en formato JSON.

- Crea un DataFrame de Pandas con las características de los personajes, como su nombre, especie, género, origen, o episodios en los que aparece. El DataFrame facilitará el procesamiento, análisis y visualización de los datos.


#### Instrucciones de Ejecución 💻

1. Clona este repositorio en tu máquina local.
2. Abre el notebook ``rickandmorty.ipynb`` en Jupyter Notebook o Jupyter Lab.
Ejecuta cada celda del notebook en orden para reproducir el análisis y los resultados.