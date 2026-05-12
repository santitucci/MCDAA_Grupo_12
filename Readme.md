# Tarea 1 — Introducción a la Ciencia de Datos

Este repositorio contiene la solución a la Tarea 1 del curso **Introducción a la Ciencia de Datos (2026)**, basada en el análisis exploratorio del dataset *All the News 2.1 – Component One*, que reúne artículos de distintos medios de prensa anglosajones.

---

## Archivos del repositorio

| Archivo | Descripción |
|---|---|
| `2026_template_tarea1.ipynb` | Notebook principal en Python. Contiene todo el código utilizado para cargar, limpiar y analizar los datos, así como la generación de visualizaciones. |
| `Informe_Tarea_1_-_IntroCD.pdf` | Informe con los resultados, análisis e interpretaciones de cada parte de la tarea. **Este es el documento principal para la corrección.** |

---

## Estructura del notebook

El notebook `2026_template_tarea1.ipynb` está organizado en las siguientes secciones:

- **Carga de bibliotecas y dataset** — importación de dependencias y descarga del dataset desde HuggingFace.
- **Parte 1A: Exploración y limpieza de datos** — detección de valores faltantes, inconsistencias en fechas, artículos duplicados y registros vacíos.
- **Parte 1B: Visualización temporal** — gráficas de la cantidad mensual de artículos publicados por los cinco medios con mayor volumen (Reuters, The New York Times, CNBC, The Hill y People).
- **Parte 2: Limpieza y normalización de texto** — implementación de la función `clean_text()` y análisis de frecuencia de palabras.

---

## Cómo ejecutar el notebook

1. Clonar el repositorio.
2. Instalar las dependencias:
   ```bash
   pip install -r requirements.txt
   ```
3. Abrir el notebook:
   ```bash
   jupyter notebook 2026_template_tarea1.ipynb
   ```

> **Nota:** el dataset completo pesa ~8.3 GB. El notebook utiliza `streaming=True` y una muestra representativa para evitar demoras en la descarga.

---
