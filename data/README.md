Archivos de Datos
Esta carpeta contiene los datasets utilizados para el análisis de Airbnb. A continuación se detallan los archivos y su contenido:

Archivos Incluidos:
listings_data.csv: Contiene información detallada de los listados de Airbnb.

Columnas principales:
id: Identificador único del listado
neighbourhood: Nombre de la zona
room_type: Tipo de habitación
price: Precio por noche
availability_365: Días disponibles al año
cleaned_listings.csv: Archivo resultante tras el proceso de limpieza de datos.

Columnas principales:
price: Precio filtrado (sin outliers)
number_of_reviews: Total de reseñas por listado
availability_365: Días disponibles tras depuración de datos inválidos

Cómo se generaron los archivos:
La limpieza y transformación de datos se realizó en el archivo:
scripts/data_cleaning.ipynb

Notas Importantes:
Confidencialidad: No se deben compartir los archivos de datos sin autorización.
Formato CSV: Todos los archivos están en formato .csv y utilizan comas como delimitadores.
