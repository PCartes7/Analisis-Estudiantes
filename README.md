## Análisis Estudiantes

Este proyecto final desarrolla un modelo de Machine Learning Supervisado (Sklearn y PySpark) para clasificar si un estudiante terminará o no el curso, adicionalmente se utilizan modelos de Regresión para determinar la satisfacción de los cursos

---

## Resultados

* **Métrica Principal:** Con Spark, usamos RandomForest Clasiffier para predecir si completará o no el curso, entrega un AUC-ROC de 77% mientras que con el algoritmo de Regresion Logistica nos entrega un valor de 89%. Por lo que significa, que RL en clasificacion es mucho mejor que el modelo creado con Spark.
* **Insight de Negocio:** A partir de un analisis de sus multiples fuentes de datos de estudiantes logramos determinar que la satisfaccion de los cursos, era significativamente relacionado con quienes completan el aprendizaje, arrastrado principalmente por estas variables: 'promedio notas', 'participacion en foros' y 'tasa completitud'.
* **Valor Aportado:** En la educación online monitorear el avance del estudiante y aplicar medidas segun su proceso de formación es crucial para que la empresa pueda mejorar sus plataformas y su material de clase, de manera que logre con mayor eficacia y eficiencia el aprendizaje.

---

## Tecnologías y Librerías Utilizadas

* **Lenguaje:** Python 3.0
* **Análisis y Manipulación de Datos:** Pandas, NumPy, Scipy, Smote
* **Visualización:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn, RandomForestClassifier, LogisticRegression
* **Big Data:** PySpark, RandomForestRegressor, Ridge
* **Entorno de Desarrollo:** JupyterNotebook, GoogleColaboratory

---

## Estructura del Repositorio

```text
├── data/                  	                    # Conjuntos de datos (fuente original: Talento Digital)
├── notebooks/             	                    # Cuadernos de GoogleColaboratory explicativos
│   └── [Final Project] Data Scientist.ipynb    # Contexto, Análisis Exploratorio de Datos (EDA), Limpieza (ETL), Entrenamiento, Evaluación, Selección de Modelos y Resumen Ejecutivo Final.
├── src/                   	                    # Scripts de Python organizados (.py)
├── .gitignore             	                    # Archivos excluidos del control de versiones
├── README.md              	                    # Documentación principal del proyecto
└── requirements.txt      	                    # Lista de dependencias del proyecto
