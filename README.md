## 🌍 Lastfm_music

Este proyecto consiste en la extracción, almacenamiento y análisis de datos musicales utilizando la API de Last.fm. El objetivo es crear una base de datos relacional con información de artistas, álbumes y canciones para responder a preguntas clave mediante consultas SQL.

## 📋 Fases del proyecto
1. **Extracción de datos**
   - Obtención de datos de artistas, álbumes y canciones desde las APIs de Last.fm y Spotify.
   - Guardado de los datos en archivos CSV.

2. **Diseño y creación de la base de datos**
   - Creación de una base de datos relacional en SQLite y/o MySQL.
   - Inserción de los datos extraídos en las tablas correspondientes.

3. **Consultas y análisis**
   - Realización de consultas SQL para responder preguntas como:
     - ¿Qué artista tiene más álbumes?
     - ¿Qué artista tiene más reproducciones?
     - ¿Cuál es la canción más popular?
     - ¿Quién es el artista mejor valorado?
     - Top 5 canciones más populares.

## 🚀 Cómo usar
1. **Clona este repositorio**
2. **Instala las dependencias necesarias**
   - Python 3.x
   - pandas
   - requests
   - numpy
   - sqlite3
   - mysql-connector-python (opcional, si usas MySQL)

   Puedes instalar los paquetes ejecutando:
   ```sh
   pip install pandas requests numpy mysql-connector-python
   ```
3. **Obtén tus claves de API**
   - Regístrate en [Last.fm API](https://www.last.fm/api) 
   - Añade tu clave en las celdas correspondientes del notebook.
4. **Ejecuta el notebook**
   - Sigue el flujo del notebook para extraer los datos, guardarlos en CSV y cargarlos en la base de datos.
   - Realiza las consultas SQL propuestas para analizar los datos.
5. **Ejecuta la presentación**
   - https://view.genially.com/68b1c8a1019cad2f86825af6/presentation-roxymusic

### 🪐 Autor

Rocío Ramírez
