# Aprendizaje-Supervisado

El aprendizaje supervisado es una técnica de machine learning en la cual un modelo es entrenado utilizando un conjunto de datos etiquetado. En este contexto, cada entrada del conjunto de datos incluye tanto las características (input) como las etiquetas correspondientes (output). El objetivo del aprendizaje supervisado es aprender una función que mapee las entradas a las salidas deseadas, de modo que el modelo pueda predecir la etiqueta correcta para nuevas entradas no vistas.

## Componentes del Aprendizaje Supervisado
### 1.Conjunto de Datos de Entrenamiento:

* Características (Features): Variables de entrada que se utilizan para hacer predicciones.

* Etiquetas (Labels): La salida esperada o la respuesta correcta para cada conjunto de características.

### 2.Modelo:

* Un algoritmo que aprende a partir de los datos de entrenamiento para hacer predicciones. Ejemplos incluyen regresión lineal, árboles de decisión, redes neuronales, entre otros.

### 3.Función de Pérdida:

* Una medida de cuán bien el modelo está realizando sus predicciones en comparación con las etiquetas reales. El objetivo es minimizar esta función.

### 4.Algoritmo de Optimización:

Un método para ajustar los parámetros del modelo con el fin de minimizar la función de pérdida. Ejemplos incluyen el descenso del gradiente y sus variantes.

## Tipos de Problemas de Aprendizaje Supervisado
### 1.Clasificación:

* Asignar una etiqueta a una entrada. Por ejemplo, clasificar correos electrónicos como "spam" o "no spam", o clasificar imágenes de animales como "perro", "gato", etc.

* Algoritmos comunes: Regresión logística, máquinas de vectores de soporte (SVM), árboles de decisión, redes neuronales.

### 2.Regresión:

* Predecir un valor continuo. Por ejemplo, predecir el precio de una casa basado en sus características (tamaño, ubicación, etc.).

* Algoritmos comunes: Regresión lineal, regresión polinómica, árboles de regresión, redes neuronales.


## Ejemplos de Algoritmos de Aprendizaje Supervisado
**Regresión Lineal**:

* Utilizado para problemas de regresión. Encuentra la línea que mejor se ajusta a los datos.

**Regresión Logística**:

* Utilizado para problemas de clasificación binaria. Estima la probabilidad de que una entrada pertenezca a una clase particular.

***Árboles de Decisión**:

* Utilizado tanto para clasificación como para regresión. Divide el espacio de características en regiones más pequeñas y homogéneas.

**Máquinas de Vectores de Soporte (SVM)**:

* Utilizado principalmente para clasificación. Encuentra el hiperplano que mejor separa las clases en el espacio de características.

**Redes Neuronales**:

* Utilizadas para tareas complejas de clasificación y regresión. Compuestas de capas de neuronas que aprenden representaciones jerárquicas de los datos.


##  Proceso de Aprendizaje Supervisado
Recolección de Datos:

Obtener un conjunto de datos etiquetados relevante para el problema.
Preprocesamiento de Datos:

Limpieza de datos, normalización, manejo de valores faltantes, y transformación de características.
División del Conjunto de Datos:

Separar los datos en un conjunto de entrenamiento y un conjunto de prueba (y a veces un conjunto de validación).
Entrenamiento del Modelo:

Utilizar el conjunto de entrenamiento para ajustar los parámetros del modelo.
Evaluación del Modelo:

Utilizar el conjunto de prueba para evaluar el rendimiento del modelo. Métricas comunes incluyen precisión, recall, F1-score para clasificación, y error cuadrático medio para regresión.
Ajuste de Hiperparámetros:

Optimizar los parámetros del modelo utilizando técnicas como la validación cruzada.
Implementación:

Desplegar el modelo entrenado para hacer predicciones sobre nuevos datos.
