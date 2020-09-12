# Programación del Gradiente Descendente en Python

Código fuente donde se implementa el algoritmo del Gradiente Descendente sin usar librerías de *Machine Learning*.

Para este ejemplo usaremos un set de datos que relaciona la presión sanguínea de una persona con su edad, y, haciendo uso de la librería Keras, encontraremos la línea recta que mejor se ajusta a estos datos.

En este tutorial veremos cómo:
- Realizar la lectura del set de datos usando la librería "Pandas" de Python
- Visualizar los datos usando la librería "Matplotlib" de Python
- Implementar el modelo en Keras usando las funciones "Sequential" y "Dense"
- Crear el optimizador (gradiente descendente) usando la librería Keras, definiendo además la función de error y la tasa de aprendizaje
- Realizar el entrenamiento del modelo en la librería Keras y cómo ver los resultados de este entrenamiento en cada iteración

Finalmente, graficaremos la línea recta obtenida tras el entrenamiento, y haremos una predicción usando un dato que el modelo no ha visto previamente.
