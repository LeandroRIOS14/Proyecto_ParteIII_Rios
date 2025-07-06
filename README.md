# Proyecto Parte III - Feature Selection y Clasificación

Este proyecto tiene como objetivo aplicar técnicas de **reducción de dimensionalidad (Feature Selection)** y **clasificación supervisada** utilizando el dataset del Titanic.

## 📊 Dataset

Se utilizó el dataset `Titanic` provisto por la librería `seaborn`. Este dataset contiene información de pasajeros del Titanic como:

- Edad, sexo, clase, tarifa, etc.
- Supervivencia (0 = no, 1 = sí)

## ⚙️ Metodología

1. Limpieza y preprocesamiento del dataset
2. Codificación de variables categóricas
3. Selección de las 5 variables más relevantes usando `SelectKBest` con `chi2`
4. Entrenamiento de un modelo de clasificación (`RandomForestClassifier`)
5. Evaluación del modelo con métricas:
   - Accuracy
   - Precisión
   - Recall
   - F1-score
   - Matriz de confusión

## 📈 Resultados

El modelo obtuvo buenos resultados prediciendo la supervivencia de los pasajeros. Las variables seleccionadas fueron significativas y permitieron reducir la complejidad del modelo sin perder precisión.

## 🛠️ Librerías utilizadas

- pandas
- seaborn
- matplotlib
- scikit-learn

## 📂 Instrucciones

Podés abrir y ejecutar el archivo `.ipynb` en Jupyter Notebook o Google Colab.

## Autor

Ríos – 2025
