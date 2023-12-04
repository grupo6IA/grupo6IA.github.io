---
# the default layout is 'page'
#
#
#
icon: fas fa-book-open
order: 4
---

# ¿Qué es el aprendizaje automático?


![PosterIA](/assets/img/favicons/infoo/data.jpg)




## Definición

El aprendizaje automático es una rama de la inteligencia artificial (IA) y la informática que se centra en el uso de datos y algoritmos para imitar la forma en que aprenden los humanos, mejorando gradualmente su precisión. El aprendizaje automático es un componente importante del creciente campo de la ciencia de datos. Mediante el uso de métodos estadísticos, los algoritmos se entrenan para hacer clasificaciones o predicciones, y para descubrir ideas clave en proyectos de minería de datos. Posteriormente, estos conocimientos impulsan la toma de decisiones dentro de las aplicaciones y las empresas, lo que idealmente repercute en las métricas de crecimiento clave. 


Los modelos de aprendizaje automático se dividen en tres categorías principales: 


## Aprendizaje automático Supervisado

El aprendizaje supervisado, también conocido como aprendizaje automático supervisado, se define por el uso de conjuntos de datos etiquetados para entrenar algoritmos que clasifiquen datos o predigan resultados con precisión. A medida que los datos de entrada se introducen en el modelo, éste ajusta sus ponderaciones hasta que se ha ajustado adecuadamente. Esto ocurre como parte del proceso de validación cruzada para garantizar que el modelo no se ajuste en exceso o en defecto. 

- Clasificación: En las tareas de clasificación, el programa de aprendizaje automático debe extraer una conclusión a partir de los valores observados y determinar a qué categoría pertenecen las nuevas observaciones. 

- Regresión: En las tareas de regresión, el programa de aprendizaje automático debe estimar y comprender las relaciones entre variables. El análisis de regresión se centra en una variable dependiente y una serie de otras variables cambiantes, lo que lo hace especialmente útil para la predicción y la previsión. 

- Predicción: La previsión es el proceso de hacer predicciones sobre el futuro basándose en los datos pasados y presentes, y se utiliza habitualmente para analizar tendencias. 


## Aprendizaje automático No Supervisado

El aprendizaje no supervisado, también conocido como aprendizaje automático no supervisado, utiliza algoritmos de aprendizaje automático para analizar y agrupar conjuntos de datos no etiquetados. Estos algoritmos descubren patrones ocultos o agrupaciones de datos sin necesidad de intervención humana. La capacidad de este método para descubrir similitudes y diferencias en la información lo hace ideal para el análisis exploratorio de datos, las estrategias de venta cruzada, la segmentación de clientes y el reconocimiento de imágenes y patrones. También se utiliza para reducir el número de características de un modelo mediante el proceso de reducción de la dimensionalidad. 


Bajo el paraguas del aprendizaje no supervisado, caen: 


- Clustering: El clustering consiste en agrupar conjuntos de datos similares (basándose en criterios definidos). Es útil para segmentar datos en varios grupos y realizar análisis en cada conjunto de datos para encontrar patrones. 

- Reducción de dimensiones: La reducción de dimensiones reduce el número de variables que se tienen en cuenta para encontrar la información exacta que se necesita. 

## Aprendizaje Semisupervisado 

El aprendizaje semisupervisado es un término medio entre el aprendizaje supervisado y el no supervisado. Durante el entrenamiento, utiliza un conjunto de datos etiquetados más pequeño para guiar la clasificación y la extracción de características de un conjunto de datos más grande y sin etiquetar. El aprendizaje semisupervisado puede resolver el problema de no disponer de suficientes datos etiquetados para un algoritmo de aprendizaje supervisado. También ayuda si resulta demasiado costoso etiquetar suficientes datos. 




# Preprocesamiento de datos

La mayoría de las veces es difícil manejar datos sin procesar. Dado el hecho de que pueden estar en cualquier formato, puede haber atributos faltantes y, en algunos casos, incluso hay muchos datos que son inútiles para nuestro modelo. Por esta razón, es esencial filtrar los conjuntos de datos antes de comenzar a construir un modelo, para que pueda ser más claro y fácil entender con qué estamos tratando.

Introducción
El preprocesamiento de datos es un paso crucial en la cadena de análisis de datos y aprendizaje automático. Implica limpiar, transformar y organizar datos crudos en un formato adecuado para el análisis o el entrenamiento de modelos. El objetivo del preprocesamiento de datos es mejorar la calidad de los datos, eliminar ruido e inconsistencias, y preparar los datos para su uso efectivo.
Un preprocesamiento de datos efectivo es esencial para garantizar la calidad y confiabilidad de los resultados obtenidos del análisis de datos y la modelización. Los pasos y técnicas específicos utilizados en el preprocesamiento de datos dependen de la naturaleza de los datos, los objetivos del análisis y los requisitos del modelo de aprendizaje automático que se esté utilizando. A continuación, se mencionan algunos de los más comunes que son aplicables a casi cualquier conjunto de datos:

## Manejo de datos faltantes

La falta de datos puede surgir de diversas fuentes, como errores en sensores, falta de respuestas en encuestas o errores en la entrada de datos. Métodos comunes para tratar con datos faltantes incluyen:
Imputación: Sustituir los valores faltantes por una estimación razonable. Esto se puede hacer utilizando valores medios, medianos o modales, o técnicas más avanzadas como la imputación por regresión.
Eliminación: Si los datos faltantes son extensos y la imputación no es factible, puede ser necesario eliminar filas o columnas con valores faltantes.

Detección y manejo de Outliers
Los valores atípicos son puntos de datos que se desvían significativamente de la mayoría de los datos. Identificar y tratar con valores atípicos es importante, ya que pueden distorsionar análisis estadísticos y modelos de aprendizaje automático. Los métodos para el tratamiento de valores atípicos incluyen recorte o transformación de los datos para que sean menos sensibles a los valores atípicos.

Ingeniería de Características o “Feature Engeneering”
La ingeniería de características implica crear nuevas características o modificar las existentes para mejorar el rendimiento de los modelos de aprendizaje automático. Esto puede incluir:
Crear características de interacción combinando dos o más variables. Dividir o discretizar variables continuas para convertirlas en categóricas. Extraer información de datos de texto, como puntajes de sentimiento o recuentos de palabras clave. Escalado de características, como la escala min-max o la escala z, para estandarizar las características.


## Reducción de dimensionalidad

Las técnicas de reducción de dimensionalidad se utilizan para disminuir el número de características mientras se preserva la información más importante. Métodos comunes incluyen Análisis de Componentes Principales (PCA) para la reducción lineal de dimensionalidad y t-Distributed Stochastic Neighbor Embedding (t-SNE) para la reducción no lineal de dimensionalidad.

Manejo de Datos Desbalanceados
Los conjuntos de datos desequilibrados ocurren cuando una clase supera significativamente a la otra. En tales casos, técnicas como el sobremuestreo, el submuestreo o el uso de métodos de generación de datos sintéticos como SMOTE pueden equilibrar el conjunto de datos, haciéndolo más adecuado para el aprendizaje automático.

Codificación de variables categóricas
Las variables categóricas deben ser codificadas en forma numérica para la mayoría de los algoritmos de aprendizaje automático. Métodos comunes incluyen:
One-Hot Encoding: Crear columnas binarias para cada categoría. Label Encoding: Asignar una etiqueta numérica única a cada categoría.




## Transformación de datos

Escalado y Normalización de Datos: Escalar características numéricas a un rango estándar (por ejemplo, entre 0 y 1) para asegurar que diferentes características estén en una escala similar. Esto es importante para muchos algoritmos de aprendizaje automático, como máquinas de soporte vectorial o agrupamiento k-means, que son sensibles a la escala de las características. Las técnicas ampliamente utilizadas son el escalado min-max y la normalización z-score.
Estandarización de Datos: Transformar los datos para que tengan una media de 0 y una desviación estándar de 1, lo cual es especialmente útil para algoritmos que asumen una distribución normal de los datos.
Codificación de Datos Categóricos: Convertir variables categóricas a un formato numérico con el que los algoritmos puedan trabajar. Técnicas comunes incluyen one-hot encoding y label encoding.
Ingeniería de Características: Crear nuevas características a partir de las existentes para capturar información adicional o simplificar la representación de los datos.

### Codificación de variables categóricas

Las variables categóricas deben ser codificadas en forma numérica para la mayoría de los algoritmos de aprendizaje automático. Métodos comunes incluyen:
One-Hot Encoding: Crear columnas binarias para cada categoría. 
Label Encoding: Asignar una etiqueta numérica única a cada categoría.

### División de datos

Los datos suelen dividirse en tres conjuntos: entrenamiento, validación y prueba. El conjunto de entrenamiento se utiliza para entrenar el modelo, el conjunto de validación para ajustar hiperparámetros y evaluar el rendimiento del modelo, y el conjunto de prueba para evaluar la capacidad de generalización del modelo a nuevos datos no vistos.






## Preprocesamiento de Series Temporales

Al tratar con datos de series temporales, es posible que debas manejar la estacionalidad, las tendencias y los patrones temporales. Técnicas como la diferenciación, promedios móviles y descomposición se pueden utilizar para hacer que los datos sean estacionarios y adecuados para el análisis.



## Conclusiones

Un preprocesamiento de datos efectivo es una parte crítica del proceso de análisis de datos y aprendizaje automático. Las decisiones tomadas durante esta fase pueden tener un impacto significativo en la calidad y confiabilidad de los resultados obtenidos a partir de los datos. A menudo, se requiere una combinación de conocimiento del dominio, exploración de datos y refinamiento iterativo para preparar los datos de manera óptima para la tarea analítica específica en cuestión.





































# Algoritmos 

Elegir el algoritmo de aprendizaje automático adecuado depende de varios factores, entre los que se incluyen: el tamaño, la calidad y la diversidad de los datos, así como las respuestas que las empresas quieren obtener de esos datos. Otras consideraciones son la precisión, el tiempo de entrenamiento, los parámetros, los puntos de datos y mucho más. Por lo tanto, elegir el algoritmo adecuado es a la vez una combinación de necesidad empresarial, especificación, experimentación y tiempo disponible. 


Estos son algunos de los algoritmos de aprendizaje automático más comunes y populares: 


## Regresión Lineal - Aprendizaje Supervisado 

La regresión lineal es el tipo más básico de regresión. Es un algoritmo utilizado para modelizar la relación entre una variable dependiente (la variable que se desea predecir) y una o más variables independientes (atributos) mediante una ecuación lineal. El objetivo es encontrar la línea recta (en el caso de una única característica) o un hiperplano (en el caso de múltiples características) que mejor se ajuste a los datos.   

Como entrada recibe una o varias variables independientes, que representan atributos de los datos. Y como salida se obtiene la variable objetivo, que es la variable que queremos predecir. 

Este algoritmo es útil para problemas en los que se busca predecir un valor numérico continuo, como los ingresos de una persona. Es un algoritmo de aprendizaje supervisado, porque se basa en datos etiquetados para aprender las relaciones que existen entre las variables. 

## Regresión Logística - Aprendizaje Supervisado 

Es un algoritmo utilizado en problemas de clasificación. Se utiliza para predecir la probabilidad de que una instancia pertenezca a una de dos clases, o a una de varias clases. 

Como entrada recibe las características o atributos utilizados para la clasificación. Y como salida se obtiene la etiqueta que representa la clase a la que se asigna una instancia en función de la probabilidad calculada. 
 
Este algoritmo es útil cuando se necesita clasificar, por ejemplo, si correo electrónico pertenece o no a la casilla de spam. Es un algoritmo de aprendizaje supervisado. 


## Algoritmo Naive Bayes - Aprendizaje/Clasificación Supervisada

El clasificador Naive Bayes se basa en el teorema de Bayes y clasifica cada valor como independiente de cualquier otro valor. Nos permite predecir una clase/categoría, basándonos en un conjunto dado de características, utilizando la probabilidad. A pesar de su simplicidad, el clasificador funciona sorprendentemente bien y se utiliza a menudo porque supera a métodos de clasificación más sofisticados. 


## Vecinos mas cercanos - Aprendizaje Supervisado/Clasificación/Regresión 

El algoritmo K-Nearest-Neighbour calcula la probabilidad de que un punto de datos pertenezca a un grupo u otro. Esencialmente, examina los puntos de datos que rodean a un único punto de datos para determinar en qué grupo se encuentra realmente. Por ejemplo, si un punto está en una cuadrícula y el algoritmo intenta determinar en qué grupo está ese punto de datos (Grupo A o Grupo B, por ejemplo), miraría los puntos de datos cercanos a él para ver en qué grupo está la mayoría de los puntos. 


## Support Vector Machines (SVM)

Las Máquinas de Vectores de Soporte (SVM) son algoritmos de aprendizaje supervisado utilizados para clasificación y regresión. Este modelo busca encontrar el hiperplano óptimo que mejor separa las clases en un espacio multidimensional. El proceso de aprendizaje consiste en encontrar este hiperplano que maximice el margen entre las clases, minimizando el error de clasificación. Para hacer predicciones con un modelo SVM entrenado, se utiliza este hiperplano para clasificar nuevos puntos de datos. Es esencial normalizar los datos previos para evitar sesgos hacia características con mayor escala y garantizar que las clases estén bien separadas para obtener un rendimiento óptimo del modelo SVM.

Estos enfoques ofrecen herramientas poderosas para la clasificación y predicción en problemas de aprendizaje automático, cada uno con sus propias características, ventajas y consideraciones en cuanto a la preparación de datos y su implementación.


## Árboles de Clasificación y Regresión (CART)

Los árboles CART son modelos de aprendizaje automático utilizados para clasificación (categorización) y regresión (predicción de valores numéricos). Este modelo se representa como una estructura de árbol donde cada nodo representa una característica de los datos y cada rama representa una decisión o un valor que dicha característica puede tomar. Estos árboles se construyen de manera recursiva, dividiendo los datos en función de las características que mejor separan las clases o predicen los valores deseados. Para predecir, se sigue el camino desde el nodo raíz hasta llegar a una hoja, que determina la clase (en clasificación) o el valor (en regresión) predicho. La preparación de datos para modelos CART implica asegurarse de tener datos limpios, sin valores faltantes y con características relevantes para el modelo.


## Clustering - k-Means

El algoritmo de k-Means es una técnica de clustering utilizada para agrupar datos no etiquetados en k grupos distintos. Funciona dividiendo el conjunto de datos en k clusters, donde cada observación pertenece al cluster con el centroide más cercano. El proceso implica inicializar centroides aleatorios, asignar puntos al cluster más cercano y actualizar los centroides recalculando sus posiciones en base a los puntos asignados. k-Means busca minimizar la suma de las distancias al cuadrado entre cada punto y su centroide dentro del cluster asignado. Es fundamental elegir adecuadamente el valor de k y realizar una exploración de los datos para comprender la estructura inherente antes de aplicar este algoritmo.


## Clustering - DBSCAN

DBSCAN (Density-Based Spatial Clustering of Applications with Noise) es un algoritmo de clustering que identifica clusters basados en la densidad de los puntos en un espacio de características. Este método puede identificar clusters de cualquier forma y es resistente al ruido en los datos. DBSCAN define clusters como áreas donde hay densidades altas de puntos, separadas por regiones con baja densidad. Los puntos pueden ser clasificados como núcleo, borde o ruido, dependiendo de su proximidad a otros puntos. La elección de los parámetros epsilon (ε) y minPoints es crucial para la efectividad de este algoritmo.


## Clustering Jerárquico

El clustering jerárquico es un enfoque que construye una jerarquía de clusters. Puede ser aglomerativo (bottom-up) o divisivo (top-down). En el enfoque aglomerativo, cada observación comienza como un cluster individual y se van fusionando en clusters más grandes en función de la similitud entre ellos. Por otro lado, en el enfoque divisivo, se comienza con un único cluster que se va dividiendo en clusters más pequeños hasta que cada observación es un cluster individual. Este método crea un dendrograma que muestra la estructura jerárquica de los clusters, permitiendo seleccionar el número óptimo de clusters cortando el dendrograma en un punto adecuado.


## Análisis de Componentes Principales - PCA

El Análisis de Componentes Principales (PCA) es una técnica de reducción de dimensionalidad utilizada para transformar variables correlacionadas en un conjunto de variables no correlacionadas (llamadas componentes principales). PCA busca identificar la dirección en la que los datos tienen más variabilidad y proyecta los datos originales en estas direcciones principales. Esto permite reducir la dimensionalidad del conjunto de datos manteniendo la mayor cantidad posible de información. PCA es útil para visualización de datos, eliminación de la multicolinealidad y compresión de datos manteniendo la mayor cantidad posible de información.

## Ensamble de Modelos

Los ensambles combinan múltiples modelos de aprendizaje automático para mejorar la precisión y robustez predictiva. La idea principal es combinar las predicciones de varios modelos base para obtener una predicción final más precisa y generalizable.

## Bootstrap Aggregation (Bagging)

Bagging es una técnica de ensamblado que consiste en entrenar múltiples modelos base utilizando subconjuntos aleatorios de los datos originales, generados mediante muestreo con reemplazo (bootstrap). Luego, combina las predicciones de estos modelos mediante promedio (en regresión) o votación (en clasificación) para obtener una predicción final más estable y reducir el sobreajuste.


## Random Forest

Random Forest es una extensión de Bagging que utiliza árboles de decisión como modelos base. Crea múltiples árboles de decisión con subconjuntos aleatorios de características y datos. La predicción final se obtiene promediando las predicciones de todos los árboles. Esta técnica reduce la correlación entre los árboles, lo que lleva a un mejor rendimiento general y una mayor resistencia al sobreajuste.

## Boosting

Boosting es una técnica de ensamblado que entrena múltiples modelos débiles secuencialmente, dándole más peso a las instancias mal clasificadas en cada iteración. Cada modelo subsiguiente se enfoca en corregir los errores de predicción de los modelos anteriores, lo que resulta en un modelo final más fuerte y preciso.

## AdaBoost (Adaptive Boosting)

AdaBoost es un algoritmo de Boosting que asigna pesos a cada instancia en los datos de entrenamiento y ajusta los modelos sucesivos para centrarse en las instancias mal clasificadas. En cada iteración, se aumenta el peso de las instancias mal clasificadas, lo que hace que el modelo se concentre más en ellas. Al combinar los modelos débiles, AdaBoost genera un modelo final fuerte y generalizable.
