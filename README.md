# Spotify Wrapped Personalizado 🎵📊

Este proyecto es un análisis personalizado de mis hábitos de escucha en **Spotify**, utilizando la API de Spotify y la librería `spotipy`. A través de este script, genero visualizaciones interactivas que muestran datos como:

- 🎤 **Top 5 artistas más escuchados**
- 🎶 **Top 5 canciones más escuchadas**
- ⏳ **Minutos y canciones escuchadas en el año**
- 📅 **Días y horas con más actividad musical**
- 🔥 **Géneros más escuchados** (opcional)

Las gráficas fueron generadas con **Altair** y **Matplotlib** para un diseño más atractivo y fácil de interpretar. 🚀

---

## 📦 Instalación y configuración

Para ejecutar este análisis en tu entorno local, sigue estos pasos:

### 1️⃣ Clona el repositorio
```bash
git clone https://github.com/tu_usuario/spotify-wrapped-personalizado.git
cd spotify-wrapped-personalizado
```

### 2️⃣ Crea un entorno virtual (opcional pero recomendado)
```bash
python -m venv env
source env/bin/activate  # En Mac/Linux
env\Scripts\activate     # En Windows
```

### 3️⃣ Instala las dependencias
```bash
pip install -r requirements.txt
```

### 4️⃣ Configura tu acceso a la API de Spotify
Para conectarte a Spotify, necesitas obtener tus credenciales desde [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/) y agregarlas a un archivo `.env` en la raíz del proyecto:

```bash
SPOTIPY_CLIENT_ID='tu_client_id'
SPOTIPY_CLIENT_SECRET='tu_client_secret'
SPOTIPY_REDIRECT_URI='http://localhost:8888/callback'
```

Luego, puedes cargarlas en Python con `dotenv`.

---

## 🚀 Cómo ejecutar el análisis
Abre un **Jupyter Notebook** en la carpeta del proyecto y ejecuta los scripts para obtener los datos y generar visualizaciones interactivas.

Si prefieres ejecutar el script directamente, usa:
```bash
python main.py
```

---

## 📊 Ejemplos de visualizaciones
Aquí algunos ejemplos de las gráficas generadas:

### 1️⃣ **Top 5 Artistas Más Escuchados**
```md
![image](https://github.com/user-attachments/assets/307c3cf7-7a4c-4555-af4e-ea55608d29b8)

```

### 2️⃣ **Distribución de Canciones Más Escuchadas**
```md
![image](https://github.com/user-attachments/assets/92c4d6c3-1b5d-4218-ad91-9884abdf74ed)

```

### 3️⃣ **Métricas Generales de Minutos escuchados, canciones escuchadas y Artistas escuchados**
```md
![image](https://github.com/user-attachments/assets/5b577025-0b38-4e88-aecb-ef8bdc404868)

```

---

## 🔥 Contribuciones y mejoras
Si tienes ideas para mejorar el análisis (por ejemplo, agregar más métricas o mejorar las visualizaciones), ¡siéntete libre de hacer un **pull request**! 💡

## 📜 Licencia
Este proyecto es de uso personal y educativo. Puedes modificarlo y adaptarlo según tus necesidades. 😊

