# 🎬 Análisis de las 100 Mejores Películas con Python, NLP y Power BI

Este proyecto presenta un análisis completo de las 100 películas mejor valoradas según IMDb, complementado con datos de OMDb y TMDb, y enriquecido mediante técnicas de análisis de datos, procesamiento de lenguaje natural (NLP) y visualización interactiva con Power BI.

---

## Objetivo

Explorar, comparar y visualizar de forma interactiva información clave sobre las mejores películas, sus calificaciones, actores, directores, plataformas de streaming, sentimiento de las reseñas de usuarios y rendimiento en taquilla.

---

## Tecnologías Utilizadas

- **Python** (pandas, requests, textblob, matplotlib, seaborn, sqlite3, dotenv)
- **APIs**: IMDb, OMDb, TMDb
- **SQLite** para modelado de base de datos relacional
- **Power BI** para visualización interactiva de los resultados
- **Jupyter Notebook** para desarrollo del análisis

---

## Funcionalidades

- ✅ Extracción de datos desde APIs y enriquecimiento con actores y directores  
- ✅ Normalización de calificaciones (IMDb, Rotten Tomatoes, Metacritic)  
- ✅ Análisis de sentimiento con NLP (TextBlob)  
- ✅ Base de datos SQLite con relaciones entre películas, actores, directores, plataformas y reseñas  
- ✅ Dashboard en Power BI con:
  - Tabla resumen de películas
  - Comparación de calificaciones por fuente
  - Gráfico de las 10 películas mejor valoradas
  - Análisis cruzado de sentimientos y valoraciones
  - Disponibilidad en plataformas de streaming
  - Información de presupuesto y taquilla

---

## Estructura del Proyecto

```
Proyecto_Cine_IA/
├── data/                      # CSVs limpios con datos
├── notebooks/                # Notebooks de análisis y visualización
├── dashboard/                # Archivo .pbix de Power BI
├── images/                   # Capturas para documentación
├── scripts/                  # Scripts .py de automatización
├── Pipfile / requirements.txt  # Dependencias del proyecto
├── README.md                 # Este archivo
```

---

## 📚Instalación y Ejecución

###  Con `pipenv`

```bash
pipenv install
pipenv run jupyter notebook
```


## 🌐 Visualización en Power BI

El archivo `dashboard/......pbix` contiene los dashboard con segmentadores, gráficos de comparación y análisis de sentimiento. Puedes abrirlos con Power BI Desktop.

---

## 💡 Posibles Mejoras Futuras

- Uso de modelos de NLP más avanzados (como spaCy o transformers)
- Análisis de géneros y clasificación temática
- Detección de emociones y temas dominantes en reseñas
- Publicación del dashboard en Power BI Service
- Integración con Streamlit para app web interactiva

---

## 🚀 Autor

**Alejandro Fuentes**  
Proyecto desarrollado como parte de formación en IA y análisis de datos.

---

## 📍 Conecta

Si te ha gustado este proyecto, no dudes en compartirlo o conectarte conmigo en [LinkedIn](https://www.linkedin.com/in/alejandrof-tech/) para más contenido sobre ciencia de datos, visualización y tecnología.

---

## 💾 Licencia

Este proyecto está bajo la licencia MIT. Puedes usarlo, modificarlo y compartirlo libremente.

