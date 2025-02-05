Spotify Wrapped Personalizado 🎵📊

Este proyecto es un análisis personalizado de mis hábitos de escucha en Spotify, utilizando la API de Spotify y la librería spotipy. A través de este script, genero visualizaciones interactivas que muestran datos como:

🎤 Top 5 artistas más escuchados

🎶 Top 5 canciones más escuchadas

⏳ Minutos y canciones escuchadas en el año

📅 Días y horas con más actividad musical

🔥 Géneros más escuchados (opcional)

Las gráficas fueron generadas con Altair y Matplotlib para un diseño más atractivo y fácil de interpretar. 🚀

📦 Instalación y configuración

Para ejecutar este análisis en tu entorno local, sigue estos pasos:

1️⃣ Clona el repositorio

git clone https://github.com/tu_usuario/spotify-wrapped-personalizado.git
cd spotify-wrapped-personalizado

2️⃣ Crea un entorno virtual (opcional pero recomendado)

python -m venv env
source env/bin/activate  # En Mac/Linux
env\Scripts\activate     # En Windows

3️⃣ Instala las dependencias

pip install -r requirements.txt

4️⃣ Configura tu acceso a la API de Spotify

Para conectarte a Spotify, necesitas obtener tus credenciales desde Spotify Developer Dashboard y agregarlas a un archivo .env en la raíz del proyecto:

SPOTIPY_CLIENT_ID='tu_client_id'
SPOTIPY_CLIENT_SECRET='tu_client_secret'
SPOTIPY_REDIRECT_URI='http://localhost:8888/callback'

Luego, puedes cargarlas en Python con dotenv.

🚀 Cómo ejecutar el análisis

Abre un Jupyter Notebook en la carpeta del proyecto y ejecuta los scripts para obtener los datos y generar visualizaciones interactivas.

Si prefieres ejecutar el script directamente, usa:

python main.py

📊 Ejemplos de visualizaciones

Aquí algunos ejemplos de las gráficas generadas:

1️⃣ Top 5 Artistas Más Escuchados



2️⃣ Distribución de Canciones Más Escuchadas



3️⃣ Heatmap de Actividad por Día y Hora



🔥 Contribuciones y mejoras

Si tienes ideas para mejorar el análisis (por ejemplo, agregar más métricas o mejorar las visualizaciones), ¡sientete libre de hacer un pull request! 💡

Si te gustó el proyecto, no olvides darle ⭐ en GitHub.

📜 Licencia

Este proyecto es de uso personal y educativo. Puedes modificarlo y adaptarlo según tus necesidades. 😊


