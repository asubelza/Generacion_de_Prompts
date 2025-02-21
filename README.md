# Generador de Juegos Personalizados con IA

## Descripción
Este proyecto utiliza inteligencia artificial para generar juegos de mesa personalizados según las preferencias del usuario. La aplicación permite a los usuarios especificar detalles sobre el tipo de juego, la temática, la dificultad, las mecánicas, y la estética visual. Además, el sistema genera imágenes ilustrativas mediante DALL-E.

## Requisitos
- Python 3.x
- Las siguientes librerías:
  - openai
  - pandas
  - matplotlib
  - PIL
  - requests

## Instalación

1. Clona el repositorio o descarga el código fuente:

git clone https://github.com/tu-usuario/generador-juegos-IA.git


2. Instala las dependencias necesarias:


pip install -r requirements.txt


3. Configura tu API Key de OpenAI:
- Regístrate en [OpenAI](https://platform.openai.com/) para obtener tu API Key.
- Guarda la clave en una variable de entorno o configúralo directamente en el código como `openai.api_key = 'TU_API_KEY'`.

## Uso

1. Abre el archivo Jupyter Notebook `generador_juegos_IA.ipynb`.
2. Sigue las instrucciones en las celdas del notebook para interactuar con el generador de juegos.
3. Una vez completado, el código generará un resumen del juego y las imágenes asociadas.

## Contribuciones
Si deseas contribuir al proyecto, por favor crea un *fork* del repositorio y envía un *pull request*.

## Licencia
Este proyecto está licenciado bajo la [Licencia MIT](https://opensource.org/licenses/MIT).
