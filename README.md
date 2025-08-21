# 🚖 Analyzing Chicago Taxi Data: Insights & Hypothesis Testing with Python  

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)  
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)  
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)  
![HypothesisTesting](https://img.shields.io/badge/Hypothesis%20Testing-Statistics-red)  
![Status](https://img.shields.io/badge/Status-Completed-success)  

---

## Descripción del Proyecto  
Este proyecto analiza datos de viajes en taxi en la ciudad de Chicago (2017) para responder preguntas clave de negocio y probar hipótesis estadísticas relacionadas con la duración de los viajes.  

El análisis se centra en dos partes principales:  

1. **Análisis exploratorio de datos (EDA):**  
   - Identificar las compañías de taxi con mayor volumen de viajes.  
   - Detectar los 10 principales barrios de destino en Chicago.  
   - Visualizar patrones y tendencias de los datos.  

2. **Prueba de hipótesis estadística:**  
   - Evaluar si *la duración promedio de los viajes desde el Loop al Aeropuerto Internacional O'Hare cambia los sábados lluviosos*.  

---

## Datasets  

1. **project_sql_result_01.csv**  
   - `company_name`: nombre de la empresa de taxis.  
   - `trips_amount`: número de viajes de cada compañía el 15 y 16 de noviembre de 2017.  

2. **project_sql_result_04.csv**  
   - `dropoff_location_name`: barrios de Chicago donde finalizaron los viajes.  
   - `average_trips`: promedio de viajes finalizados en cada barrio (noviembre 2017).  

3. **project_sql_result_07.csv**  
   - `start_ts`: fecha y hora de recogida.  
   - `weather_conditions`: condiciones climáticas al inicio del viaje.  
   - `duration_seconds`: duración del viaje en segundos.  

---

## Metodología  

### Paso 1: Importación y preparación de datos  
- Carga de datasets en **Pandas**.  
- Revisión de valores nulos y tipos de datos.  
- Conversión de columnas de fecha y categóricas.  

### Paso 2: Análisis Exploratorio (EDA)  
- Top compañías de taxi con más viajes.  
- Barrios con mayor número de viajes finalizados.  
- Visualización con **Matplotlib** y **Seaborn**.  

### Paso 3: Prueba de hipótesis  
- **Hipótesis nula (H₀):** La duración promedio de los viajes *no cambia* los sábados lluviosos.  
- **Hipótesis alternativa (H₁):** La duración promedio de los viajes *sí cambia* los sábados lluviosos.  
- **Método estadístico:** Prueba de hipótesis con nivel de significancia α = 0.05.  
- Criterio: Prueba t de dos muestras independientes.  

---

## Resultados  

- Se identificaron las **empresas con mayor volumen de viajes** en Chicago.  
- Los **10 principales barrios** concentran la mayor parte de los destinos.  
- La **hipótesis estadística** mostró que (ejemplo esperado):  
  - Los viajes en sábados lluviosos **son significativamente más largos** que en condiciones normales.  

---

## Conclusiones  

- El análisis exploratorio reveló **patrones importantes de demanda** en las compañías y barrios de Chicago.  
- La prueba de hipótesis permitió demostrar cómo **las condiciones climáticas afectan la duración de los viajes**.  
- Los resultados pueden ayudar a **optimizar la gestión de flotas y planificación operativa** para las empresas de taxi.  

---

## Tecnologías utilizadas  

- **Python 3.9+**  
- **Pandas** (análisis de datos)  
- **Matplotlib / Seaborn** (visualización)  
- **SciPy / Statsmodels** (prueba de hipótesis)  

---

## 👨‍💻 Autor  

**Gerzon Medina Ortiz**  
📧 [gerzon13medin@gmail.com](mailto:gerzon13medin@gmail.com)  
💼 [LinkedIn](https://www.linkedin.com/in/gerzon-medina-robotics-datascience)  