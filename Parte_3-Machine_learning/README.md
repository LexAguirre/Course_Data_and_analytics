![Header](../Img/pyds.png)

---

# _Parte 3:_ MACHINE LEARNING PARA CIENCIA DE DATOS

## **_Indice_**

### <a href="https://github.com/LexAguirre/Course_Data_and_analytics/blob/main/Parte_3-Machine_learning/01-EDA_Tratamiento_de_datos.ipynb">01-EDA_Tratamiento_de_datos</a>

- Exploratory Data Analysis (EDA) y tratamiento de datos
  - Análisis exploratorio de datos
    - Univariate EDA
    - Importando y preparando los Datos
    - EDA univariado para variables categoricas
  - EDA Bivariado
    - variables numéricas
      - Gráfico de Dispersión
    - Correlación de Pearson
    - Variales numéricas con variables categoricas
  - Imputación paramétrica
    - Imputación usando la Media
    - Imputacion con la Mediana
    - Imputación usando Moda
  - Imputación no paramétrica para la imputación de valores perdidos
    - KNN para la imputación de valor perdido en Python usando scikit-learn
  - KNN para la imputación de valor perdido en Python usando scikit-learn
    - One Hot Enconding
    - Target Encoding
      - Beneficios de la Target Encoder
      - Limitaciones de la codificación Target Encoder
    - Label Encoding
  - División de datos en características y etiquetas
  - Introducción a scikit-learn
    - Funciona bien con el ecosistema de datos de Python
    - Nivel práctico de abstracción
    - Cuando no usar scikit-learn
  - Divida los datos en conjuntos de prueba y entrenamiento
  - Escalado / normalización de datos
    - Normalización estándar o escalado estándar
    - Escalado MinMax
    - Escalado RobustScaler
  - Balanceo de datos con SMOTE
    - Manejo de datos desequilibrados
    - ¿Qué es SMOTE?
    - ¿Cómo lo hace SMOTE?
    - Preparación de datos
  - Técnica de remuestreo
    - Submuestreo aleatorio (Random Under-Sampling)
    - Sobremuestreo aleatorio(Random Over-Sampling)

### <a href="https://github.com/LexAguirre/Course_Data_and_analytics/blob/main/Parte_3-Machine_learning/02-Linear_regression_Prediction.ipynb">02-Linear_regression_Prediction</a>

- Modelos predictivos bajo el enfoque de regresión
- Importando librerias
  - Cargando la data
- Análisis exploratorio
  - Entrenamiento de un modelo de regresión lineal
  - Data de entrenamiento y prueba
- Preparación de datos para la regresión lineal
- Regresión lineal
  - Evaluación del modelo
  - Predicción de nuestro modelo
  - Métricas de evaluación
- Regresión de Ridge
- Regressión LASSO
- Elastic Net
- Regresión polinomial
- Descenso de gradiente estocástico
- Regresión usando Random Forest
- Regresión usando SVM
- Comparación de modelos
- Conclusiones

### <a href="https://github.com/LexAguirre/Course_Data_and_analytics/blob/main/Parte_3-Machine_learning/03-Supervised_Learning_Regression_Methods.ipynb">03-Supervised_Learning_Regression_Methods</a>

- Tipos de Algoritmos de Machine Learning
- Supervised Learning modelo de Regresión mediante Sklearn
  - Preparación de datos para problemas de regresión
  - Información de los datos Compañía de Seguro
    - Descripción de datos
  - Planteamiento del problema:
  - EDA
    - División de datos en funciones y etiquetas
    - Feature Engineering
    - Conversión de datos categóricos en números
    - Divida los datos en conjuntos de prueba y entrenamiento
    - Escalado / normalización de datos
  - Regresión
  - La idea detrás de la regresión lineal
  - Definición del modelo
    - ¿Por qué utilizar el algoritmo de regresión lineal?
    - Desventajas del algoritmo de regresión lineal
    - Implementación de regresión lineal con Sklearn
    - Coeficiente del modelo
    - Calcula el MSE
    - Coeficiente de Determinación
    - Tipos de Metricas
  - Modelo KNN para Regresión
    - Algoritmo KNN
    - (i) Euclidean distance; (ii) Manhattan distance; (iii) cosine similarity
    - Preparación de datos para problemas de regresión
    - División de datos en funciones y etiquetas
    - Conversión de datos categóricos en números
    - Divida los datos en conjuntos de prueba y entrenamiento
    - Escalado / normalización de datos
    - Implementación del algoritmo KNN con SKlearn
    - Tipos de Metricas
      - Calculo de Metrica
    - Calculo de K-vecinos contra RMSE
  - Support Vector Regresión
    - Ilustración de regresión de máquina de vectores de soporte
    - Preparación de datos para problemas de regresión
    - División de datos en funciones y etiquetas
    - Conversión de datos categóricos en números
    - Divida los datos en conjuntos de prueba y entrenamiento
    - Escalado / normalización de datos
    - Implementación de SVR con Sklearn
    - Tipos de Metricas
      - Cálculo de Metrica
  - Árbol de Decisión
    - Introducción al algoritmo del árbol de decisiones
    - Árboles de clasificación y regresión (CART)
    - Cálculo de Métricas
  - Random Forest Regresión
    - Preparación de datos para problemas de regresión
    - División de datos en funciones y etiquetas
    - Conversión de datos categóricos en números
    - Divida los datos en conjuntos de prueba y entrenamiento
    - Escalado / normalización de datos
    - Implementación de un regresor de bosque aleatorio mediante Sklearn
    - Tipos de Metricas
      - Cálculo de Metrica
  - Comparación de modelos
  - Predicciones

### <a href="https://github.com/LexAguirre/Course_Data_and_analytics/blob/main/Parte_3-Machine_learning/04-Regression_Ensemble_Methods.ipynb">04-Regression_Ensemble_Methods</a>

- Bagging, Random Forests y Boosting Para Regresión
  - Preparando los datos
    - Usando one- hot encoding para las variables categóricas
    - Haciendo las particiones para el conjunto de prueba y entrenamiento
    - Preparando el DataFrame para el análisis de nuestros modelos
  - Modelo K-Nearest Neighbors (KNN)
  - Bagging
  - Random Forests
  - Boosting
  - Usando el mejor modelo para predecir el precio de la Prima anual
    - XGBoost
    - XGBRegressor

### <a href="https://github.com/LexAguirre/Course_Data_and_analytics/blob/main/Parte_3-Machine_learning/05-Hyperparameter_for_Regression_Models.ipynb">05-Hyperparameter_for_Regression_Models</a>

- Manual Search
- Grid Search
- Random Search

### <a href="https://github.com/LexAguirre/Course_Data_and_analytics/blob/main/Parte_3-Machine_learning/06-Supervised_Learning_Classification_Methods.ipynb">06-Supervised_Learning_Classification_Methods</a>

- CASO: Predecir la posibilidad de una Cancelación de un Reserva de Hotel
- Importando las librerias
  - Información de la Data
  - Estadística Descriptiva
    - Variable ADR
    - Adults
    - Ajustar tipo de datos
- Feature Engineering (Ingeniería de características)
  - Total Stays
  - Total Guests
  - Kids
  - Guest Location
  - Valores duplicados
  - Eliminar características irrelevantes
  - Eliminar columnas redudantes
  - Dividir Características en Numéricas y Categoricas
- Análisis Exploratorio de Datos
  - Gráfico de Distribución
  - Análisis Multivariado
    - Matriz de Correlación
    - EDA Conclusion
  - Preprocesamiento de datos
    - Reformateando Feature
  - Class imbalance
  - Análisis multivariante con la variable objetivo
    - Distribución de ADR
    - Plazo de entrega y hotel
    - Plazo de entrega (mes) y cancelación
    - Tipo de Depósito y Cancelación
    - Cancelaciones Previas y Cancelación
    - Tipo de Hotel por cancelación
    - Ubicación del huésped y cancelación
    - Huésped repetido y hotel
    - Segmento de Mercado y Hotel
    - Tipo de Cliente y Hotel
    - Cambios y cancelaciones de reservas
    - Solicitud especial y cancelación
    - Espacio de Parking y Cancelación
    - Tipo de comida y cancelación
    - Distribución de canales & Cancelación
- MODELOS
  - Codificando Variables Categoricas
  - División de los Datos en etiquetas
- Division de los Datos para Entrenamiento y Prueba
- Regresión Logística
  - Métricas
  - Resultados
  - Matriz de Confusión
  - Otra Libreria
  - Curva de ROC
- Árbol de Decisón

  - Introducción
    - Gini
    - Entropy
  - Ventajas y Desventajas
  - Implementación de Modelo
  - Resultados
    - Matriz de Confusión
    - Curva ROC
  - Support Vector Machines
    - Resultados
      - Matriz de Confusión
      - Curva ROC
  - Random Forest
    - Resultados
      - Matriz de Confusión
  - AdaBoost
    - Resultado
    - Matriz de Confusión
    - Curva Roc
  - Gradient Boosting
    - Resultado
    - Matriz de Confusión
    - Curva Roc
  - XGBoost
    - Resultado
    - Matriz de Confusión
    - Curva Roc
  - ExtraTrees
    - Resultado
    - Matriz de Confusión
    - Curva ROC
  - Bagging
    - Resultados
    - Matriz de Confusión
    - Curva Roc
  - RESULTADO

### <a href="https://github.com/LexAguirre/Course_Data_and_analytics/blob/main/Parte_3-Machine_learning/07-Imputación_de_datos.ipynb">07-Imputación_de_datos</a>

- Imputación de datos usando Random Fotest

  - Conjunto de datos a trabajar: Brewer's Friend Beer Recipes
    - Técnicas de Imputación con Modelos de Machine Learning

### <a href="https://github.com/LexAguirre/Course_Data_and_analytics/blob/main/Parte_3-Machine_learning/08-RandomForest_Selección_de_Variables.ipynb">08-RandomForest_Selección_de_Variables</a>

- Selección de Variables usando Randon Forest

### <a href="https://github.com/LexAguirre/Course_Data_and_analytics/blob/main/Parte_3-Machine_learning/09-Supervised_Learning_Classification_RNA.ipynb">09-Supervised_Learning_Classification_RNA</a>

- Redes neuronales aplicado a datos bancarios
  - Implementando la Red Neuronal Artificial
    - Empecemos!
    - A predecir!
    - Calculamos la matriz de confusion

### <a href="https://github.com/LexAguirre/Course_Data_and_analytics/blob/main/Parte_3-Machine_learning/10-Deep_Learning_Keras.ipynb">10-Deep_Learning_Keras</a>

- Descripción del dataset
- Importar clases y datasets
- Cargando el Dataset
- Pre-procesamiento inicial de los datos
- Codificar la variable de salida
- Definir la red neuronal
- Redes
  - Modelo de línea base
  - Modelo medium
  - Modelo large
- Evaluar el modelo
  - Validación cruzada
  - Validación cruzada con estandarización
- Checkpoint y forecasting
  - Punto de control en el modelo
  - Cargar modelo con pesos del fichero
- Análisis de entrenamiento
  - Las métricas de Accuracy y Loss
- Regularación de la red con Dropout

  - Modificar el Gradiente Descendiente Estocástico (SGD)
  - Dropout en la capa de entrada
  - Dropout en las capas ocultas

### <a href="https://github.com/LexAguirre/Course_Data_and_analytics/blob/main/Parte_3-Machine_learning/11-Hyperparameter_for_Classification_Methods.ipynb">11-Hyperparameter_for_Classification_Methods</a>

- CASO: Spotify - Clasificación de popularidad
  - INTRODUCCIÓN
- OBJETIVO E INTERESES DEL PROYECTO:
- Importando librerias
- Descripción de los Datos y Limpieza
  - Resumen del conjunto de datos sin procesar:
  - Limpieza de datos
  - Columna de consolidación de género
  - Análisis:
- ANÁLISIS EXPLORATORIO Y VISUALIZACIONES
  - ¿Géneros y artistas más populares de 1950 a 2000?
    - Conclusión:
  - ¿Hay una tendencia/cambio en los géneros preferidos antes de la década de 2000 frente a los actuales a lo largo de los años?
  - Visuales de gráfico circular de bloques de año que muestran tendencia/cambio en géneros entre (1956 - 2019)
    - Conclusión: análisis de gráfico circular:
  - Recuento de popularidad del género a lo largo de los años
  - ¿Qué otras características tienen un impacto en la popularidad de una canción?
    - Nota:
    - Ahora para reemplazar nuestra columna de género original con la versión actualizada
    - Como puede ver, se han eliminado los géneros con aquellos que tienen una instancia inferior a 20
    - Conclusión:
- DATOS DE MODELADO
  - Modelo (Clasificación de popularidad)
    - Paso 1: Una codificación One hot-encode de género y artista:
      - Clasifique la función de destino: 'popularidad' en contenedores 2x, para ayudar a clasificar mejor nuestros datos para nuestro modelo predictivo
    - Análisis
    - Step 2: Splitting & Scaling Data
  - Modeling & Training
  - Salidas de Accuracy del modelo de entrenamiento:
    - Análisis:
  - Validating models with k-fold cross validation:
    - Análisis:
  - Conclusión

### <a href="https://github.com/LexAguirre/Course_Data_and_analytics/blob/main/Parte_3-Machine_learning/12-K_Means_Clustering.ipynb">12-K_Means_Clustering</a>

- Introducción
- Cargando las Libraria
- Load Dataset
- Análisis Exploratorio de datos
  - Distribución
  - Correlación
- K-Means
  - Implementación de K-means
- Método del codo
- Coeficiente y visualización silhouette
- Mini Batch K-Means
- Método del codo
- Agregando clustering al Dataset
- Visualización de los Clustering
- Coeficiente y visualización silhouette
  - Ventajas y Desventajas

### <a href="https://github.com/LexAguirre/Course_Data_and_analytics/blob/main/Parte_3-Machine_learning/13-Association_Rule_Learning.ipynb">13-Association_Rule_Learning</a>

- ¿Reglas de asociación? Qué es eso!
- MBA (Market Basket Analysis):
  - Introduction:
  - Análisis Exploratorio de Datos (EDA):
  - Ventas a lo largo del tiempo:
    - Análisis de los mejores productos: café, té, pasteles, tostadas
  - Market Basket Analysis:
  - Un Antecedente
  - Más de un antecedente
  - 5 Conclusión

### <a href="https://github.com/LexAguirre/Course_Data_and_analytics/blob/main/Parte_3-Machine_learning/14-DBSCAN_Affinity_Propagation.ipynb">14-DBSCAN_Affinity_Propagation</a>

- Introduction
- Leer datos
- Análisis Exploratorio de datos
  - Distribución
  - Correlación
- Clustering
  - DBSCAN
  - Descripción
  - Implemetación DBSCAN - customers segmentation
- Affinity Propagation
  - Description
  - Algoritmo
  - Use case - customers segmentation
- Comparison and discussion

### <a href="https://github.com/LexAguirre/Course_Data_and_analytics/blob/main/Parte_3-Machine_learning/15-PCA.ipynb">15-PCA</a>

- CASO: PREDICCIÓN DE LA CALIDAD DEL VINO TINTO

### <a href="https://github.com/LexAguirre/Course_Data_and_analytics/blob/main/Parte_3-Machine_learning/16-Series de Tiempo.ipynb">16-Series de Tiempo</a>

- Contenido
- Introducción
  - ¿Qué es una Serie de Tiempo?
  - Características de la serie de tiempo
- Evaluación de Modelos
  - Métricas evaluar modelo
    - Métrica 1: MSE
    - Métrica 2: RMSE
    - Métrica 3: MAE
    - Métrica 4: MAPE
    - Métrica 5: R2
- Método de Suavizamiento (smoothing)
  - Media móvil simple
  - Suavizado exponencial simple
  - Doble Suavizamiento exponencial
- Modelo Arima
  - Cómo encontrar el orden de diferenciación (d) en el modelo ARIMA
  - Cómo encontrar el orden del término AR (p)

### Proyectos

- #### <a href="https://github.com/LexAguirre/Course_Data_and_analytics/tree/main/Proyecto_5">Proyecto 5</a>
