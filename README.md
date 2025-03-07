# Análisis de Airbnb: Mejores Zonas para Invertir

Este proyecto analiza los listados de Airbnb para identificar las mejores zonas y tipos de habitación para invertir en la Ciudad de México, considerando factores clave como número de reseñas, rango de precios y disponibilidad.

---

## Contexto
La creciente popularidad de plataformas como Airbnb ha transformado el mercado inmobiliario, convirtiéndose en una oportunidad rentable para inversores. Este proyecto busca responder a preguntas clave para identificar dónde y cómo invertir en la Ciudad de México, considerando la demanda, la popularidad de las zonas y las preferencias de los huéspedes.

## Estructura del Proyecto
- **README.md**: Introducción y resumen del proyecto.
- **analysis.md**: Explicación detallada de las gráficas generadas.
- **img/**: Carpeta que contiene las capturas de los gráficos generados.
- **scripts/**: Carpeta con los archivos principales de código:
  - `data_cleaning.ipynb`: Proceso de limpieza y preparación de datos.  
  - `analysis.ipynb`: Análisis exploratorio, visualizaciones y generación de gráficas.
- **listings_data/**: Carpeta con los datasets utilizados para el análisis.
- **requirements.txt**: Archivo que especifica las librerías necesarias para reproducir el proyecto.

---

## Preguntas Clave y Respuestas

**¿Qué zonas tienen más potencial para invertir?**	
- Cuauhtémoc, Venustiano Carranza y Miguel Hidalgo.
  
**¿Qué tipo de habitación es más rentable?**
- Las habitaciones privadas y apartamentos completos destacan por su rentabilidad.
  

## Requisitos
- **Python 3.10+**

### Librerías utilizadas:
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `statsmodels`

---

## Cómo Ejecutarlo

### **Instalar las dependencias**:
```bash
pip install -r requirements.txt
```

### **Ejecutar la limpieza de datos**:
```bash
jupyter notebook scripts/data_cleaning.ipynb
```

### **Ejecutar el análisis y generar gráficas**:
```bash
jupyter notebook scripts/analysis.ipynb
```

## Conclusiones
- Mejores zonas para invertir: Cuauhtémoc, Venustiano Carranza y Miguel Hidalgo .
- Tipos de alojamiento recomendados:Apartamentos completos, por su balance entre rentabilidad y popularidad.
- Rango de Precios: El precio promedio es accesible, con una media de aproximadamente $1,280 MXN por noche.



