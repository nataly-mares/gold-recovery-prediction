# Gold Recovery Prediction

✅ Project Description
Zyfra, a company focused on efficiency solutions for the heavy industry, aims to optimize gold extraction processes.
This project consists of building a machine learning model to predict the amount of gold recovered from ore during the extraction and purification process.
The model is designed to support decision-making by improving production efficiency and identifying non-profitable parameters.
The evaluation metric used was sMAPE (Symmetric Mean Absolute Percentage Error), considering both rougher and final recovery stages.

✅ Objective
Build and evaluate regression models that can:
- Predict gold recovery at different stages of the process (rougher and final)
- Optimize production efficiency
- Identify key variables affecting extraction performance
- Minimize prediction error using sMAPE

✅ Methodology
- Data Preparation
- Load datasets (train, test, full)
- Validate data consistency
- Handle missing values and duplicates
- Align features between training and test sets
- Exploratory Data Analysis
- Analyze gold concentration across different stages
- Study distributions of key variables
- Detect anomalies and outliers
- Evaluate changes in metal concentration during purification
- Data Preprocessing
- Feature selection based on availability in test data
- Handling missing values
- Scaling (if required)

✅ Modeling

Multiple regression models were trained and evaluated:
- Linear Regression
- Tree-based models (e.g., Random Forest)
- Gradient Boosting models
- Key configurations:
- Separate prediction for:
- Rougher recovery
- Final recovery
- Custom evaluation metric: sMAPE
- Cross-validation for model selection

Additionally:
- Comparison of model performance
- Analysis of prediction errors
- Evaluation of generalization on test data

✅ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

✅ Results
The model successfully predicts gold recovery for both rougher and final stages.
sMAPE was effectively minimized, meeting the project requirements.
The analysis revealed that gold concentration increases through purification stages, confirming process consistency.
Feature selection and preprocessing played a key role in improving model performance.


# Predicción de Recuperación de Oro

✅ Descripción del proyecto
Zyfra, una empresa enfocada en soluciones de eficiencia para la industria pesada, busca optimizar los procesos de extracción de oro.
Este proyecto consiste en construir un modelo de machine learning capaz de predecir la cantidad de oro recuperado del mineral durante las etapas de extracción y purificación.
El modelo está diseñado para apoyar la toma de decisiones, mejorar la eficiencia de producción e identificar parámetros no rentables.
La métrica de evaluación utilizada fue sMAPE (Error Porcentual Absoluto Medio Simétrico), considerando tanto la recuperación en la etapa rougher como en la etapa final.

✅ Objetivo
Construir y evaluar modelos de regresión que permitan:
- Predecir la recuperación de oro en distintas etapas del proceso (rougher y final)
- Optimizar la eficiencia de producción
- Identificar variables clave que afectan el rendimiento de extracción
- Minimizar el error de predicción utilizando sMAPE

✅ Metodología
- Preparación de datos
- Carga de datasets (train, test, full)
- Validación de consistencia de datos
- Tratamiento de valores ausentes y duplicados
- Alineación de variables entre entrenamiento y prueba
- Análisis exploratorio
- Análisis de la concentración de oro en distintas etapas
- Estudio de distribuciones de variables clave
- Detección de anomalías y valores atípicos
- Evaluación de cambios en la concentración durante la purificación
- Preprocesamiento de datos
- Selección de variables disponibles en el conjunto de prueba
- Tratamiento de valores faltantes
- Escalado de variables (si es necesario)

✅ Modelado
Se entrenaron y evaluaron múltiples modelos de regresión:
- Regresión Lineal
- Modelos basados en árboles (ej. Random Forest)
- Modelos de Gradient Boosting

Configuraciones clave:

Predicción separada para:
- Recuperación rougher
- Recuperación final
- Métrica personalizada: sMAPE
- Validación cruzada para selección de modelo

Adicionalmente:
- Comparación de desempeño entre modelos
- Análisis de errores de predicción
- Evaluación de generalización en datos de prueba

✅ Tecnologías utilizadas
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

✅ Resultados
El modelo logra predecir la recuperación de oro en ambas etapas del proceso.
Se minimizó el error sMAPE, cumpliendo con los requisitos del proyecto.
El análisis mostró que la concentración de oro aumenta a lo largo de las etapas de purificación, confirmando la coherencia del proceso.
La selección de variables y el preprocesamiento tuvieron un impacto clave en el desempeño del modelo.
