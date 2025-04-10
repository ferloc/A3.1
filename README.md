# A3.1
El objetivo de este proyecto es desarrollar un modelo de clasificación utilizando Máquinas de Vectores de Soporte (SVM) para identificar distintos tipos de cáncer, a partir de datos de expresión génica estandarizada. Además, se realizaron múltiples pruebas con distintos kernels para comparar el rendimiento de cada modelo y seleccionar el más adecuado.

📊 Descripción del Conjunto de Datos "A3.1 Khan.csv"
Número de muestras: 83

Número de variables de entrada: 2308

Características: Cada variable representa la expresión génica estandarizada de un gen específico.

Variable de salida (y): Valores numéricos del 1 al 4, donde cada número representa un tipo de cáncer distinto.

⚙️ Proceso realizado
Preprocesamiento de datos

Estandarización de los datos de entrada

División de datos en conjunto de entrenamiento y prueba

Entrenamiento de modelos SVM con distintos kernels:

Lineal

Polinomial (grado 3)

Radial (RBF)

Evaluación del desempeño mediante:

Matrices de confusión

Cálculo de precisión

Comparación de modelos para determinar cuál ofrece mejores resultados de clasificación.

📈 Resultados
SVM con kernel lineal: Precisión = 0.9412

SVM con kernel polinomial (grado 3): Precisión = 0.9412

SVM con kernel radial (RBF): Precisión = 1.0000


Indice

- [Reporte en formato HTML](A3.1%20641675.html)
- [Reporte en formato ipynb](A3.1%20641675.ipynb)
- [Base de datos](A3.1%20Khan.csv)
