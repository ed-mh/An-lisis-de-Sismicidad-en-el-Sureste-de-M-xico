# Análisis Estadístico y Geoespacial de la Sismicidad en el Sureste de México (1975-2025)

## Descripción del Proyecto
Este proyecto presenta un análisis exploratorio de datos (EDA) y geoespacial de la actividad sísmica en Chiapas y el sureste de México, una de las zonas tectónicas más complejas de América debido a la interacción de las placas de Cocos, Norteamérica y del Caribe.

A través del procesamiento de registros del catálogo del USGS y el uso de herramientas especializadas como **PyGMT**, el proyecto caracteriza la sismicidad espacial y temporal, desmitificando aparentes "incrementos" de actividad que en realidad corresponden a mejoras en la red de monitoreo.

## Tecnologías Utilizadas
* **Python 3.x**
* **Pandas:** Limpieza y manipulación de series de tiempo.
* **Matplotlib:** Visualización estadística.
* **PyGMT:** Mapeo geofísico y trazado de eventos tectónicos.

## Estructura del Repositorio
* `codigo/`: Jupyter Notebooks con el análisis paso a paso.
* `datos/`: Dataset de sismos (USGS/SSN).
* `imagenes/`: Gráficas y mapas de alta resolución generados.

## Resultados Clave
* **Ilusión del Incremento:** Se demuestra que el aumento exponencial de eventos registrados en las últimas décadas correlaciona con la instalación de nuevas estaciones sismológicas, no con un cambio geológico abrupto.
* **Geometría de Subducción:** La distribución espacial de epicentros revela claramente la zona de Benioff donde la Placa de Cocos subduce bajo la Placa de Norteamérica.

## Instalación y Uso
Para replicar este análisis, asegúrate de tener instalado un entorno con las dependencias necesarias:

```bash
conda install numpy pandas matplotlib
conda install -c conda-forge pygmt