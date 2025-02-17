# README - Datos Utilizados
Esta carpeta contiene los datasets utilizados para el análisis de Airbnb. A continuación se detallan los archivos y su contenido:

## 1. Fuente de los Datos
- **Origen:** [Inside Airbnb](https://insideairbnb.com/get-the-data/)
- **Archivo utilizado:** `listings_data.csv`
- **Descripción:** Este conjunto de datos contiene listados de Airbnb en la Ciudad de México, incluyendo información sobre precios, tipos de habitación, número de reseñas y disponibilidad.

## 2. Descripción de las Columnas Principales
- `id`: Identificador único del listado.
- `host_id`: Identificador del anfitrión.
- `neighbourhood`: Nombre de la zona o vecindario.
- `room_type`: Tipo de habitación (entera, privada, compartida).
- `price`: Precio por noche.
- `minimum_nights`: Número mínimo de noches para reservar.
- `number_of_reviews`: Total de reseñas recibidas.
- `availability_365`: Número de días disponibles para reservar en el año.

## 3. Proceso de Obtención
- Los datos fueron descargados directamente desde [Inside Airbnb](https://insideairbnb.com/get-the-data/) en formato CSV.

## 4. Limpieza y Transformaciones
- Se eliminaron columnas irrelevantes para el análisis.
- Se gestionaron valores nulos y se estandarizaron formatos.
- Se crearon nuevas columnas como `price_range` para análisis comparativos.

## 5. Ubicación de los Datos
- Los archivos originales y procesados se encuentran en la carpeta `data/`.

---

Este archivo proporciona contexto para entender la procedencia y estructura de los datos utilizados en el análisis.

## cleaned_listings.csv: Archivo resultante tras el proceso de limpieza de datos.

## 1. Columnas principales:
price: Precio filtrado (sin outliers)
number_of_reviews: Total de reseñas por listado
availability_365: Días disponibles tras depuración de datos inválidos

## 2. Cómo se generaron los archivos:
La limpieza y transformación de datos se realizó en el archivo:
scripts/data_cleaning.ipynb

Notas Importantes:
Formato CSV: Todos los archivos están en formato .csv y utilizan comas como delimitadores.
