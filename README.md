# 3erChallenge-AluraLatam-AaronCapellino
# 📊 Proyecto de Machine Learning: Predicción de Churn (SUJETO A FEEDBACK Y A MEJORAS) 

Este proyecto busca predecir la **cancelación de clientes (churn)** en una empresa de telecomunicaciones, utilizando técnicas de Machine Learning.  

El dataset contiene información demográfica, de servicios contratados y de facturación de clientes, con la columna objetivo `churn` (1 = canceló, 0 = no canceló).  

---

## 📂 Estructura del Proyecto

├── TelecomX_Data.json # Raw Dataset
├── data_procesada.csv # Dataset base
├── 3er_Challenge.ipynb # Desarrollo en Google Colab / Jupyter
├── README.md # Documentación del proyecto

---

## 🛠️ Librerías utilizadas

- **pandas** → manipulación de datos
- **imblearn** → balanceo
- **scikit-learn** → preprocesamiento, modelos y métricas  
- **matplotlib / seaborn** → visualizaciones  
- **pickle** → guardar y cargar modelos  

---

## 🔑 Flujo del proyecto

1. **Encoding**  
   - Conversión de variables categóricas a numéricas.  
   - Codificación de la variable objetivo `churn`.  

2. **Análisis Exploratorio (EDA)**  
   - Proporción de churn.  
   - Distribución de clientes según contrato, servicios y facturación.  
   - Correlaciones entre variables.  

3. **Preprocesamiento**  
   - Balanceo con SMOTE

4. **Modelado**  
   - **Arbol de decisiones** (no lineal).  
   - **Random Forest** (modelo más robusto, no lineal).  

5. **Evaluación**  
   - Métricas: Accuracy, Precision, Recall, F1.  
   - Reporte de clasificación y matriz de confusión.  

6. **Importancia de Variables**    
   - Feature Importances del Random Forest.
  
7. **Conclusión**    
   - El análisis permitió construir modelos predictivos capaces de anticipar la cancelación de clientes (churn) a partir de información demográfica, contractual y de consumo.
  
## 👨‍💻 Autor

Proyecto desarrollado en Python (Google Colab) por Aaron Capellino.
