\# Taller de Análisis Predictivo



\## Descripción



Este proyecto corresponde a un taller académico de análisis predictivo desarrollado en Python. Se utilizan datos históricos de ventas para construir modelos que permitan estimar las ventas diarias y evaluar su desempeño.



\## Objetivo



Aplicar los conceptos básicos del análisis predictivo mediante la preparación de datos, la selección de variables, el entrenamiento de modelos de regresión lineal y la evaluación de sus resultados.



\## Archivos del proyecto



\- `Informe\_Analisis\_Predictivo.ipynb`: notebook de Google Colab con el código, las explicaciones, las tablas, las gráficas y las conclusiones.

\- `online\_retail\_limpio.csv`: conjunto de datos utilizado para realizar el análisis.



\## Herramientas utilizadas



\- Python

\- Pandas

\- NumPy

\- Matplotlib

\- Scikit-learn

\- Google Colab



\## Modelos utilizados



Se desarrollaron dos modelos de regresión lineal:



1\. Un modelo que utiliza el orden de los días como variable predictora.

2\. Un modelo que incorpora el orden de los días, el día de la semana y el mes.



Los modelos se evaluaron mediante MAE, RMSE y R². El segundo modelo obtuvo mejores resultados, aunque ambos presentaron valores negativos de R², por lo que sus predicciones tienen limitaciones importantes.



\## Cómo ejecutar el proyecto



1\. Descarga los archivos del repositorio o abre el notebook directamente en Google Colab.

2\. Descarga `online\_retail\_limpio.csv` y súbelo a la sesión de Colab.

3\. Ejecuta las celdas del notebook en orden.



El notebook utiliza la siguiente ruta para cargar los datos:



```python

df = pd.read\_csv("/content/online\_retail\_limpio.csv")

```



Por lo tanto, el archivo CSV debe estar disponible en la ruta `/content/` de Google Colab.



\## Conclusión



El taller permitió comprender las etapas básicas del análisis predictivo y comprobar que agregar variables puede mejorar un modelo. Sin embargo, también mostró la importancia de evaluar las predicciones y reconocer sus limitaciones antes de utilizarlas para tomar decisiones empresariales.

