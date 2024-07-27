# Loan Prediction Analysis 📊

Este repositorio contiene un análisis completo para la predicción de la aprobación de préstamos utilizando modelos de Machine Learning. Implementamos y comparamos varios modelos, incluyendo Regresión Logística, Árbol de Decisión y Random Forest, utilizando técnicas de validación cruzada y optimización de hiperparámetros.
![logo](https://datahack-prod.s3.ap-south-1.amazonaws.com/__sized__/contest_cover/loanpre-thumbnail-1200x1200.png)
## Descripción del Proyecto

El objetivo de este proyecto es predecir si un solicitante de préstamo será aprobado o no, basado en varias características del solicitante. Utilizamos un conjunto de datos preprocesado para entrenar y evaluar diferentes modelos de clasificación.

## Estructura del Proyecto

- **Data Preprocessing**: Carga y limpieza de datos.
- **Exploratory Data Analysis (EDA)**: Análisis exploratorio para entender la distribución de los datos.
- **Model Training**: Entrenamiento de varios modelos de Machine Learning.
- **Cross-Validation**: Evaluación de modelos utilizando validación cruzada.
- **Hyperparameter Tuning**: Optimización de hiperparámetros usando GridSearchCV.
- **Model Comparison**: Comparación de modelos basados en métricas de rendimiento.
- **Final Analysis**: Selección del mejor modelo y análisis detallado de los resultados.

## Resultados Principales
![image](https://github.com/user-attachments/assets/f4da7073-108a-47dc-8a1c-a7cb4b8489ca)

### Modelos Evaluados

1. **Regresión Logística**:
   - Mean AUC score: `0.7739`
   - Best cross-validated AUC score: `0.7829`
   - Final Accuracy: `0.8130`
   - Final AUC: `0.7359`

2. **Árbol de Decisión**:
   - Mean AUC score: `0.6634`
   - Best cross-validated AUC score: `0.7410`
   - Final Accuracy: `0.6016`
   - Final AUC: `0.6015`

3. **Random Forest**:
   - Mean AUC score: `0.7662`
   - Best cross-validated AUC score: `0.7915`
   - Final Accuracy: `0.8211`
   - Final AUC: `0.7765`

### Análisis de Resultados del Modelo Seleccionado (Random Forest)

- **Porcentaje de personas que aprueban el préstamo**: `21.95%`
- **Porcentaje de personas que no aprueban el préstamo**: `78.05%`
- **Porcentaje total de aciertos**: `78%`

### Conclusión

El modelo de **Random Forest** fue seleccionado como el mejor modelo para la predicción de aprobación de préstamos debido a su alto rendimiento en términos de precisión y AUC. Este modelo proporciona una base sólida para implementar un sistema automatizado de evaluación de solicitudes de préstamos.

## Requisitos

Para ejecutar este proyecto, necesitarás las siguientes librerías de Python:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Puedes instalarlas usando:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Agradecimientos
Agradezco a los profesores de Data Analítica por brindarme todos los conocimientos necesarios para realizar este proyecto.



## Cómo Ejecutar el Proyecto

Para ejecutar este proyecto y replicar el análisis, sigue los siguientes pasos:

1. **Clona este repositorio**:
   ```bash
   git clone https://github.com/tu-usuario/Loan_Prediction.git
   ```
2. **Navega al directorio del proyecto**:
   ```bash
   cd Loan_Prediction
   ```
3. **Instala las dependencias necesarias**:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
2. **Ejecuta el notebook**:
   ```bash
   jupyter notebook Loan_Prediction.ipynb
   ```






