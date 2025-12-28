# Bank Customer Churn Prediction 📉

## 📋 Descripción del Proyecto
Proyecto enfocado en la retención de clientes bancarios. Se desarrolló un sistema de clasificación para identificar usuarios con alta probabilidad de abandonar el banco (Churn). El enfoque principal fue resolver el **desbalance de clases** y maximizar el **F1-Score** para permitir al equipo de marketing tomar acciones preventivas.

## 🛠️ Tecnologías Clave
* **Python** (Pandas, Scikit-learn).
* **Boosting:** CatBoost, XGBoost.
* **Técnicas Avanzadas:** Upsampling (SMOTE), Threshold Tuning, Ensembles.

## ⚙️ Metodología
1.  **Ingeniería de Características:** Codificación de variables categóricas (One-Hot Encoding) y escalado numérico.
2.  **Manejo de Desbalance:** La clase positiva (fuga) representaba solo el 20% de los datos. [cite_start]Se utilizaron técnicas de **Upsampling** para equilibrar el entrenamiento[cite: 26].
3.  **Comparativa de Modelos:** Se evaluaron Random Forest vs. Gradient Boosting.
4.  **Evaluación:** Se priorizó el F1-Score sobre el Accuracy debido a la naturaleza desbalanceada del problema.

## 📊 Resultados
* **Mejor Modelo:** CatBoost con ajuste de hiperparámetros.
* [cite_start]**Rendimiento:** Se superó el umbral de F1-Score requerido (> 0.59) y se obtuvo un AUC-ROC competitivo, permitiendo una segmentación efectiva de clientes[cite: 27].

## 📁 Disponibilidad de los Datos
**Nota:** Los datos demográficos y financieros utilizados son confidenciales/propietarios y no se distribuyen públicamente.
> 💡 **Cómo ver el proyecto:** El notebook contiene todas las salidas de celda, matrices de confusión y curvas ROC pre-renderizadas para su análisis inmediato.
