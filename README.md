# Scaling-types
**Explicación y visualización de los tipos de escalamiento en un ejemplo.**

Escalar los datos es fundamental en el preprocesamiento de datos para el análisis estadístico y el modelado de machine learning por varias razones:

* **Comparabilidad**: Al escalar los datos, todas las características se colocan en una escala común, lo que permite compararlas de manera significativa. Esto es crucial cuando las características tienen magnitudes muy diferentes.

* **Estabilidad del algoritmo**: Algunos algoritmos de aprendizaje automático pueden ser sensibles a la escala de las características. Por ejemplo, en métodos basados en distancia como K-Nearest Neighbors (KNN) o Support Vector Machines (SVM), las características con escalas grandes pueden dominar el cálculo de distancias, lo que afecta negativamente el rendimiento del modelo.

* **Convergencia del algoritmo**: Escalar los datos puede mejorar la convergencia de los algoritmos de optimización, como el descenso de gradiente, al hacer que la función objetivo sea más "bien comportada". Esto puede acelerar el proceso de entrenamiento del modelo.

* **Interpretación del modelo**: En algunos modelos, como la regresión lineal, el escalado de datos puede facilitar la interpretación de los coeficientes al eliminar la influencia de la escala de las características en sus valores.

Antes de escalar:

![imagen_esc1](https://github.com/LeoSotoG/Scaling-types/blob/main/Scaler1.png?raw=true)

Despues de aplicar los tipos de escalamiento:

![imagen_esc2](https://github.com/LeoSotoG/Scaling-types/blob/main/Scaler2.png?raw=true)
