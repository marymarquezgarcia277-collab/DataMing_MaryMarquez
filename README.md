# Proyecto de Minería de Datos: Análisis del Dataset Iris

## Objetivo del Proyecto

El objetivo de este proyecto es analizar las características de diferentes especies de flores Iris utilizando técnicas básicas de análisis y visualización de datos. A través del estudio de medidas físicas de las flores, se busca identificar patrones que permitan diferenciar las especies.

## Pregunta de Investigación

¿Qué características de las flores permiten diferenciar las especies del dataset Iris?

---

## Fuente de los Datos y Proceso de Limpieza

### Fuente de los datos

El dataset utilizado es el **Iris Dataset**, un conjunto de datos clásico utilizado en análisis de datos y aprendizaje automático.
Contiene 150 observaciones de flores pertenecientes a tres especies:

* Iris setosa
* Iris versicolor
* Iris virginica

Cada registro incluye cuatro medidas de la flor:

* Largo del sépalo
* Ancho del sépalo
* Largo del pétalo
* Ancho del pétalo

El dataset fue cargado en formato CSV en un entorno de análisis en Python.

### Proceso de limpieza

El dataset se encontraba limpio y estructurado. Sin embargo, se realizaron los siguientes pasos:

* Verificación de tipos de datos.
* Revisión de valores nulos.
* Confirmación de consistencia en las categorías de especies.
* Exploración inicial de las primeras filas del dataset.

---

## Técnicas de Minería de Datos Aplicadas

Para analizar el dataset se aplicaron técnicas básicas de análisis exploratorio de datos (EDA):

* Análisis descriptivo de variables.
* Agrupación de datos por especie.
* Visualización de datos mediante gráficos.

Las visualizaciones utilizadas incluyen:

* Gráficos de dispersión para analizar relaciones entre variables.
* Histogramas para observar distribuciones de datos.
* Gráficos de barras para comparar cantidades por categoría.
* Boxplots para analizar variaciones entre especies.
* Mapas de calor para identificar correlaciones entre variables.

---

## Resultados Obtenidos y Conclusiones

Los resultados muestran que las características relacionadas con el tamaño del pétalo son las que mejor permiten diferenciar las especies de flores. En particular, el largo y el ancho del pétalo presentan una fuerte relación entre sí y permiten identificar patrones claros entre las tres especies.

Las visualizaciones revelan que la especie *setosa* se diferencia claramente de las demás, mientras que *versicolor* y *virginica* presentan algunas similitudes pero aún muestran diferencias en las medidas de los pétalos.

En conclusión, las variables relacionadas con el pétalo son las más relevantes para clasificar las especies de flores del dataset Iris.

---

## Limitaciones y Recomendaciones Futuras

### Limitaciones

* El dataset es pequeño (150 registros).
* Solo contiene cuatro variables numéricas.
* No incluye información adicional como condiciones ambientales o ubicación geográfica.

### Recomendaciones futuras

* Aplicar modelos de clasificación como árboles de decisión o k-means.
* Utilizar datasets más grandes para comparar resultados.
* Incluir nuevas variables que permitan mejorar la precisión del análisis.
* Realizar modelos predictivos para identificar automáticamente la especie de una flor.
