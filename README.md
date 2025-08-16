# 📊 | Challenge Telecom X: análisis de evasión de clientes - Parte 2

Este proyecto corresponde al desafío de análisis de datos propuesto en el curso de **Alura LATAM y Oracle ONE**.

El objetivo fue identificar patrones y factores asociados a la evasión (churn) de clientes en una compañía de telecomunicaciones, utilizando modelos de Machine Learning, métricas de evaluación y visualizaciones que permitan fundamentar estrategias de retención.

## 📌 | Objetivo principal

Analizar el comportamiento de los clientes para:

- Determinar los principales factores que influyen en la cancelación del servicio.  
- Explorar la relación entre variables demográficas, contractuales y de uso con la evasión.  
- Construir modelos predictivos que permitan estimar la probabilidad de cancelación.  
- Proveer información útil para diseñar estrategias de retención más efectivas.  

## 🧪 | Tecnologías y herramientas usadas

- **Python**  
- **Pandas / Numpy** (análisis y manipulación de datos)  
- **Matplotlib / Seaborn** (visualización de datos)  
- **Scikit-learn** (modelado y métricas de evaluación)  
- **Google Colab** (entorno de desarrollo)  
- **GitHub** (control de versiones y publicación)  

## 📷 | Visualizaciones generadas

Se generaron múltiples gráficos con descripciones explicativas:

- **Gráfico de barras:** Distribución de evasión por tipo de contrato.  
- **Gráfico de barras horizontales:** Cancelación según tipo de servicio de internet.  
- **Gráfico de barras agrupadas:** Relación entre método de pago y cancelación.  
- **Gráfico de pastel:** Proporción de clientes que permanecen vs. que cancelan.  
- **Mapa de calor (heatmap):** Correlación entre variables numéricas y cancelación.  
- **Matrices de confusión:** Evaluación de desempeño de modelos predictivos.  
- **Importancia de variables:** Factores clave según Regresión Logística y Random Forest.  

## 📄 | Informe de resultados

El análisis y modelado permitió identificar que:

- Los contratos **mensuales** presentan una tasa de cancelación mucho más alta que los de mayor duración.  
- Los clientes con **servicio de fibra óptica** registran más cancelaciones que quienes tienen DSL o no poseen internet.  
- Determinados métodos de pago, como la tarjeta de crédito automática, se asocian a **menor churn**.  
- Existe una **relación negativa** entre la antigüedad del cliente (*tenure*) y la probabilidad de cancelación.  
- En términos de modelos:  
  - **Random Forest** alcanzó mejor desempeño general (Accuracy ≈ 82%, ROC AUC ≈ 0.88).  
  - **Regresión Logística** obtuvo resultados ligeramente menores (Accuracy ≈ 78%, ROC AUC ≈ 0.85).  
  - Random Forest se destacó en la predicción de la clase minoritaria (clientes que cancelan).  

## 📝 | Cómo ejecutar

1. Clona este repositorio:
2. Abre el archivo .ipynb en Google Colab o Jupyter Notebook.
3. Instala las dependencias necesarias (si no están disponibles en tu entorno):
4. Ejecuta las celdas del notebook en orden para reproducir el análisis y las visualizaciones.

```bash
git clone https://github.com/RamsRD/desafio-alura-telecom-x-2
pip install pandas numpy matplotlib seaborn scikit-learn
