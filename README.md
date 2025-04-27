## ⚙️ Configuración del Entorno

Este proyecto utiliza **Conda** para la gestión de entornos virtuales.

### 📦 Crear el entorno de forma automática

1. Asegúrate de tener **Miniconda** o **Anaconda** instalado en tu sistema.
2. Descarga el archivo `environment.yml` incluido en este repositorio.
3. Ejecuta los siguientes comandos en tu terminal:

```bash
# Crear un nuevo entorno a partir del archivo .yml
conda env create -f environment.yml

# Activar el entorno recién creado
conda activate master




# 🩺 Heart Disease Classification Project

## 📋 Descripción
Proyecto de Machine Learning para predecir la presencia de enfermedad cardíaca usando variables clínicas de pacientes.

## 🗂️ Dataset
- Fuente: UCI Machine Learning Repository
- Variables: Edad, sexo, presión arterial, colesterol, frecuencia cardíaca máxima, entre otras.

## 🧹 Preprocesamiento
- Eliminación de columna 'id'.
- Imputación de nulos con mediana/moda.
- Tratamiento de outliers.
- Codificación categórica (One-Hot Encoding).
- Escalado de variables (StandardScaler).

## 🛠️ Modelos utilizados
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest

## 📈 Evaluación
- Accuracy, Precision, Recall, F1-Score
- Matrices de confusión
- Curvas ROC

## 🧠 Conclusiones
Random Forest fue el modelo con mejor desempeño.
