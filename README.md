# Análisis de Agrupamiento en Cantos de Anuros (MFCCs)

## Resumen
Este proyecto tiene como objetivo analizar los patrones en los cantos de diferentes especies de ranas utilizando técnicas de agrupamiento, específicamente para determinar si las clasificaciones taxonómicas actuales se alinean con características vocales distintas. El conjunto de datos utilizado, "Anuran Calls (MFCCs)", está disponible públicamente y consiste en coeficientes cepstrales en las frecuencias de Mel (MFCCs), que representan características de audio de los cantos de ranas grabados en condiciones reales, incluyendo ruido de fondo.

## Conjunto de Datos
El conjunto de datos utilizado en este proyecto es el "Anuran Calls (MFCCs)", disponible en el Repositorio de Aprendizaje Automático de UCI. Contiene grabaciones de cantos de ranas que han sido transformadas en MFCCs, que son una representación compacta de las características espectrales del sonido. Los datos incluyen 7,195 instancias de 10 especies diferentes, con clasificaciones taxonómicas proporcionadas a nivel de género y familia.

## Objetivos del Proyecto
- Realizar un análisis exploratorio de datos para identificar patrones iniciales en los cantos de las ranas.
- Detectar y eliminar _outliers_ y aplicar las transformaciones necesarias para el agrupamiento.
- Experimentar con diferentes algoritmos de agrupamiento y evaluar su idoneidad utilizando métricas intrínsecas.
- Evaluar si existe una correspondencia entre los grupos formados y las clasificaciones taxonómicas existentes.

## Metodología
1. **Análisis Exploratorio de Datos (EDA):** Análisis inicial del conjunto de datos para comprender las distribuciones y visualizar posibles patrones.
2. **Limpieza de Datos:** Detección y eliminación de _outliers_, seguida de transformaciones de datos para asegurar la idoneidad de los algoritmos de agrupamiento.
3. **Técnicas de Agrupamiento:** Aplicación de algoritmos de agrupamiento (e.g., K-Means, DBSCAN) y evaluación de los grupos resultantes utilizando métricas intrínsecas como la puntuación de silueta.
4. **Interpretación:** Evaluar si los grupos reflejan la clasificación taxonómica de las especies de ranas.

## Resultados
Los resultados del agrupamiento se evalúan para determinar si los patrones acústicos capturados por los MFCCs se alinean con la taxonomía conocida de las especies de ranas. Los conocimientos obtenidos de este análisis podrían contribuir a estudios adicionales sobre el reconocimiento automático de especies utilizando datos acústicos.

## Dependencias
- Python 3.x
- Jupyter Notebook
- Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## Ejecución del Proyecto
1. Clonar el repositorio.
2. Instalar las dependencias necesarias.
3. Ejecutar el notebook de Jupyter `Agrupamiento.ipynb` para reproducir el análisis.

## Referencias
1. Repositorio de Aprendizaje Automático de UCI: [Anuran Calls (MFCCs)](https://archive.ics.uci.edu/dataset/406/anuran+calls+mfccs).
2. Información sobre los coeficientes cepstrales en las frecuencias de Mel (MFCCs): [Wikipedia](https://es.wikipedia.org/wiki/Mel-frequency_cepstrum).

## Licencia
Este proyecto está bajo la Licencia MIT.

