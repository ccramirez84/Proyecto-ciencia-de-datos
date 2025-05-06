Proyecto: Análisis de la Calidad del Aire en Colombia
Este proyecto se centró en el análisis de datos históricos de calidad del aire de Colombia con el objetivo de identificar patrones, tendencias y posibles incumplimientos de los estándares normativos.
1. Obtención de los Datos
El primer paso consistió en la obtención de un conjunto de datos público sobre la calidad del aire. La fuente de estos datos fue. El dataset contenía información horaria/diaria sobre la concentración de diversos contaminantes como PM2.5, PM10, O3, CO, NO2 y SO2, junto con la ubicación de la estación de monitoreo y la marca de tiempo de la medición. 
2. Carga e Inspección Inicial
Una vez descargado el archivo, se procedió a cargar los datos en un entorno de análisis. Se realizó una inspección inicial para comprender la estructura del dataset, los tipos de información disponibles y la presencia de datos faltantes. Esta etapa inicial proporcionó una visión general de la calidad y el formato de los datos con los que se trabajaría.
3. Limpieza y Preparación de los Datos
La fase de limpieza y preparación fue fundamental para asegurar la integridad de los resultados del análisis. Los pasos incluyeron la conversión de las marcas de tiempo a un formato adecuado para el análisis temporal. También se identificaron y abordaron los valores faltantes presentes en el dataset, utilizando una estrategia apropiada para no comprometer la representatividad de los datos. 
4. Análisis Exploratorio de Datos (EDA)
El objetivo del EDA fue extraer información valiosa de los datos a través de la visualización y el resumen estadístico.
•	Distribución de los Contaminantes: Se generaron histogramas y gráficos de densidad para cada contaminante (PM2.5, PM10, etc.). Estas visualizaciones mostraron la frecuencia con la que se presentaron diferentes niveles de concentración, permitiendo identificar la distribución típica de cada sustancia en el aire.
•	Comparación entre Estaciones: Se utilizaron diagramas de caja para comparar la distribución de la concentración de un contaminante específico entre las diversas estaciones de monitoreo. Esto permitió identificar si existían diferencias significativas en la calidad del aire según la ubicación de la estación.
•	Correlación entre Contaminantes: Se generó una matriz de correlación visualizada como un mapa de calor para identificar posibles relaciones entre las concentraciones de los diferentes contaminantes. Esto ayudó a entender si la presencia de un contaminante estaba asociada con la presencia de otros.

