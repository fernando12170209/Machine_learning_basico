# Regresión Logística en Keras

Set de datos y código fuente donde con la implementación de La Regresión Logística en Keras, como se explica en [este video](https://youtu.be/jv44zMWc4nM).

En este tutorial veremos cómo resolver un problema de clasificación binaria usando el algoritmo de Regresión Logística en Keras. Para ello usaremos un set de datos que relaciona el número de horas de estudio y el número de horas de sueño con la probabilidad de que un grupo de estudiantes apruebe o no un examen.

La idea del modelo a implementar es que, con base en las variables "número de horas de estudio" y "número de horas de sueño", aprenda a determinar si un estudiante en particular aprobará o reprobará el examen.

Para ello haremos uso de la librería Keras, en donde implementaremos un modelo de Regresión Logística (es decir un modelo con una sola neurona artificial) siguiendo estos pasos:

- Lectura y visualización del set de datos usando las librerías "Pandas" y "Matplotlib" de Python
- Creación del modelo de Regresión Logística en Keras, usando las funciones "Sequential" y "Dense"
- Creación del optimizador (gradiente descendente) y definición de la función de error (entropía cruzada) y de la tasa de aprendizaje.
- Entrenamiento del modelo usando la librería Keras
- Visualización de la frontera de decisión obtenida tras el entrenamiento de la neurona artificial, lo que permitirá determinar de forma gráfica si el modelo permite separar correctamente una categoría de la otra.
