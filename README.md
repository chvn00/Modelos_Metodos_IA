# Modelos y Métodos de Sistemas Inteligentes

Repositorio académico de la asignatura **Modelos y Métodos de Sistemas Inteligentes**.

Este repositorio reúne notebooks, bases de datos y ejemplos prácticos desarrollados en Python para el estudio de diferentes técnicas de inteligencia artificial, aprendizaje automático, aprendizaje profundo, lógica difusa y optimización bioinspirada.

Los ejemplos están orientados a facilitar la comprensión de los fundamentos teóricos mediante implementaciones reproducibles que pueden ejecutarse principalmente en **Google Colaboratory**.

## Objetivo del repositorio

El objetivo es proporcionar material práctico para que los estudiantes puedan:

- Comprender el funcionamiento de diferentes modelos de inteligencia artificial.
- Implementar algoritmos en Python.
- Analizar el efecto de hiperparámetros y configuraciones.
- Evaluar modelos mediante métricas apropiadas.
- Comparar diferentes metodologías.
- Aplicar los modelos a problemas de clasificación, regresión, predicción, control y optimización.

---

## Estructura del repositorio

### `DT` - Decision Trees

Contiene ejemplos relacionados con **árboles de decisión** como modelos de clasificación basados en reglas.

Archivos disponibles:

- `Arboles_Decisión_fixed.ipynb`

Este material permite estudiar conceptos como:

- Construcción de árboles de decisión.
- Criterios de partición.
- Selección de variables.
- Profundidad del árbol.
- Extracción de reglas.
- Interpretación del modelo.
- Evaluación mediante métricas de clasificación.

---

### `Database` - Bases de datos

Contiene conjuntos de datos utilizados en diferentes prácticas y ejercicios del curso.

Archivos disponibles:

- `AI_Datasets_Benchmark.csv`
- `AI_Datasets_Benchmark.xlsx`

Estos archivos pueden utilizarse para comparar diferentes técnicas de inteligencia artificial sobre un mismo conjunto de datos.

---

### `Fuzzy Logic` - Lógica Difusa

Esta carpeta contiene ejemplos de **sistemas de inferencia difusa**, aplicaciones de lógica fuzzy y modelos híbridos.

Notebooks disponibles:

- `AI_Intelligent_Systems_fixed.ipynb`
- `ANFIS1_fixed.ipynb`
- `Business_Management_fixed.ipynb`
- `Edu_Social_fixed.ipynb`
- `Engineering_Control_fixed.ipynb`
- `Environment_Energy_fixed.ipynb`
- `FuzzyLogic_fixed.ipynb`
- `Health_Biomedicine_fixed.ipynb`
- `Robotics_Autonomous_Systems_fixed.ipynb`
- `metricas_fixed.ipynb`
- `prestamo_fixed.ipynb`

Los ejemplos cubren aplicaciones en diferentes áreas:

- Sistemas inteligentes.
- Gestión empresarial.
- Educación y ciencias sociales.
- Ingeniería y control.
- Energía y medio ambiente.
- Salud y biomedicina.
- Robótica y sistemas autónomos.
- Evaluación de métricas.
- Evaluación de riesgo y préstamos.
- Sistemas neuro-difusos mediante ANFIS.

En estos notebooks se trabajan conceptos como:

- Variables lingüísticas.
- Funciones de pertenencia.
- Reglas IF-THEN.
- Inferencia difusa.
- Sistemas Mamdani y Sugeno.
- Defuzzificación.
- Sistemas neuro-difusos ANFIS.
- Interpretación de reglas y resultados.

---

### `NN` - Redes Neuronales y Aprendizaje Profundo

Esta carpeta contiene ejemplos de diferentes arquitecturas de redes neuronales para clasificación, regresión, procesamiento de imágenes y análisis de secuencias.

Notebooks disponibles:

- `CNN_EMNIST_fixed.ipynb`
- `CNN_combo_fixed.ipynb`
- `CNN_prediccion_fixed.ipynb`
- `GRU_Prediction_fixed.ipynb`
- `GRU_fixed.ipynb`
- `LSTM_fixed.ipynb`
- `LSTM_regression_fixed.ipynb`
- `MLP_GD_fixed.ipynb`
- `MLP_TA_fixed.ipynb`
- `MLP_fixed.ipynb`
- `MLP_regresion_fixed.ipynb`
- `RNN_fixed.ipynb`
- `SOM_fixed.ipynb`
- `Transformers_fixed.ipynb`

También se incluye una carpeta:

- `MLP`

Los contenidos permiten estudiar diferentes arquitecturas:

#### Multilayer Perceptron - MLP
- Clasificación.
- Regresión.
- Descenso de gradiente.
- Entrenamiento y ajuste de hiperparámetros.

#### Convolutional Neural Networks - CNN
- Clasificación de imágenes.
- Reconocimiento de patrones.
- Uso de bases de datos como EMNIST.
- Predicción mediante redes convolucionales.

#### Recurrent Neural Networks - RNN
- Procesamiento de secuencias.
- Dependencias temporales.

#### Long Short-Term Memory - LSTM
- Predicción de secuencias.
- Modelos de regresión.
- Dependencias temporales de largo plazo.

#### Gated Recurrent Unit - GRU
- Predicción de series y secuencias.
- Comparación con arquitecturas recurrentes tradicionales.

#### Self-Organizing Maps - SOM
- Aprendizaje no supervisado.
- Agrupamiento y visualización de datos.

#### Transformers
- Modelado de secuencias.
- Mecanismos de atención.
- Arquitecturas modernas de aprendizaje profundo.

---

### `GA` - Algoritmos Evolutivos e Inteligencia de Enjambre

Esta carpeta contiene ejemplos de técnicas de optimización bioinspirada.

Notebooks disponibles:

- `CNN+GA_fixed.ipynb`
- `GA_fixed.ipynb`
- `NSGAII_fixed.ipynb`
- `PSO_fixed.ipynb`

Los principales temas abordados son:

#### Genetic Algorithms - GA
- Representación de individuos.
- Función de aptitud.
- Selección.
- Cruce.
- Mutación.
- Evolución de poblaciones.

#### NSGA-II
- Optimización multiobjetivo.
- Frentes de Pareto.
- Dominancia.
- Diversidad de soluciones.

#### Particle Swarm Optimization - PSO
- Inteligencia de enjambre.
- Movimiento de partículas.
- Búsqueda global.
- Actualización de velocidad y posición.

#### CNN + GA
- Integración de redes neuronales convolucionales con algoritmos genéticos.
- Optimización de arquitecturas o hiperparámetros mediante técnicas evolutivas.

---

## Notebooks adicionales

En la raíz del repositorio también se encuentran diferentes notebooks asociados con aplicaciones específicas:

- `Braille_NN.ipynb`
- `PGAGV.ipynb`
- `PGFiltro.ipynb`
- `PGValvula.ipynb`
- `corregir_git_fixed.ipynb`
- `mapreduce_fixed.ipynb`

Estos notebooks complementan los ejemplos principales con aplicaciones prácticas relacionadas con redes neuronales, algoritmos genéticos, procesamiento de señales, sistemas físicos y procesamiento de datos.

---

## Temas principales de la asignatura

El repositorio cubre principalmente los siguientes contenidos:

1. Sistemas basados en reglas.
2. Árboles de decisión.
3. Lógica difusa.
4. Sistemas neuro-difusos.
5. Redes neuronales artificiales.
6. Aprendizaje automático.
7. Redes neuronales profundas.
8. CNN.
9. RNN, LSTM y GRU.
10. Self-Organizing Maps.
11. Transformers.
12. Algoritmos genéticos.
13. Optimización multiobjetivo.
14. Inteligencia de enjambre.
15. Optimización de modelos de inteligencia artificial.

---

## Herramientas utilizadas

Los ejemplos se desarrollan principalmente con:

- Python
- Google Colaboratory
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- TensorFlow
- Keras
- Scikit-Fuzzy

Dependiendo del ejercicio pueden utilizarse librerías adicionales.

---

## Reproducibilidad

Para el desarrollo de las prácticas se recomienda:

- Ejecutar los notebooks desde el inicio.
- Documentar los hiperparámetros utilizados.
- Definir semillas aleatorias cuando corresponda.
- Identificar claramente los conjuntos de entrenamiento, validación y prueba.
- Registrar las transformaciones realizadas sobre los datos.
- Analizar los resultados obtenidos y no limitarse únicamente a reportar métricas.

---

## Uso académico

Este repositorio tiene fines académicos y sirve como material de apoyo para la asignatura **Modelos y Métodos de Sistemas Inteligentes**.

Los notebooks pueden utilizarse como punto de partida para prácticas, experimentos y actividades, pero se espera que los estudiantes comprendan, modifiquen, analicen y justifiquen las configuraciones utilizadas en cada modelo.
