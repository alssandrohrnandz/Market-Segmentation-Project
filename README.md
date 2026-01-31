## English version test

# Strategic Customer Segmentation using Machine Learning

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?logo=scikit-learn&logoColor=white)
![Status](https://img.shields.io/badge/Status-In%20Progress-green)

## 🎯 Executive Summary
This project leverages advanced clustering techniques to transform raw transactional data into actionable business segments. Moving beyond basic descriptive statistics, this approach utilizes **RFM (Recency, Frequency, Monetary Value)** metrics to uncover hidden behavioral patterns, enabling the optimization of marketing budgets and churn prevention strategies.

> **Scientific Perspective:** Leveraging my background in Population Genetics, I apply the statistical rigor used in population structure analysis (analogous to ancestry inference) to validate the robustness, stability, and variance of the identified market niches.

---

## 📊 Primary Visualization
![Cluster Segmentation](reports/figures/main_segmentation.png)
*(Replace this with a screenshot of your Plotly interactive chart)*

---

## 🛠️ Methodology & Tech Stack

### 1. Feature Engineering
Raw data was transformed into strategic business dimensions:
* **Recency:** Days since the last transaction (indicator of potential churn).
* **Frequency:** Total number of transactions (indicator of loyalty).
* **Monetary Value:** Total spend (indicator of customer lifetime value).

### 2. Clustering Algorithm
**K-Means Clustering** was implemented as the primary model. The optimal number of clusters ($K$) was validated using:
* **The Elbow Method:** Identifying the point of diminishing returns in variance reduction.
* **Silhouette Analysis:** Measuring the cohesion and separation quality between clusters.

### 3. Tech Stack
* **Data Manipulation:** `Pandas`, `Numpy`
* **Machine Learning:** `Scikit-Learn`, `Yellowbrick`
* **Interactive Visualization:** `Plotly`, `Seaborn`

---

## 📈 Business Insights & Strategy
The analysis identified [X] key customer segments:

1. **Champions:** High-frequency, high-spend customers. *Strategy: Exclusive rewards and early access programs.*
2. **At-Risk Customers:** Historically high-value clients with no recent activity. *Strategy: Personalized re-engagement campaigns.*
3. **[Cluster Name]:** [Brief description]. *Strategy: [Recommended Action].*

---

## 📂 Project Structure
* `data/`: Raw and processed datasets.
* `notebooks/`: Exploratory Data Analysis (EDA) and model development.
* `reports/figures/`: Exported visualizations for stakeholder reporting.

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/customer-segmentation-project.git](https://github.com/your-username/customer-segmentation-project.git)

## Version en Español
# Segmentación Estratégica de Clientes mediante Machine Learning

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?logo=scikit-learn&logoColor=white)
![Status](https://img.shields.io/badge/Status-En%20Desarrollo-green)

## 🎯 Resumen Ejecutivo
Este proyecto aplica técnicas de clustering avanzado para transformar datos transaccionales brutos en segmentos de clientes accionables. A diferencia de un análisis descriptivo básico, este enfoque utiliza métricas de **RFM (Recencia, Frecuencia, Valor Monetario)** para identificar patrones de comportamiento ocultos, permitiendo optimizar presupuestos de marketing y estrategias de retención.

> **Perspectiva Científica:** Como investigador en genética de poblaciones, aplico el rigor estadístico de la estructura poblacional (análogo al análisis de ancestría) para validar la robustez y separación de los nichos de mercado identificados.

---

## 📊 Visualización Principal
![Segmentación de Clusters](reports/figures/main_segmentation.png)
*(Sustituye esta imagen con un screenshot de tu gráfico de Plotly)*

---

## 🛠️ Metodología y Stack Tecnológico

### 1. Ingeniería de Características (Feature Engineering)
Se transformaron los datos brutos en dimensiones estratégicas:
* **Recencia:** Días desde la última compra (indicador de deserción).
* **Frecuencia:** Número total de transacciones (indicador de lealtad).
* **Valor Monetario:** Gasto total acumulado (indicador de rentabilidad).

### 2. Algoritmo de Agrupamiento
Se implementó **K-Means Clustering**. La selección del número óptimo de grupos ($K$) se validó mediante:
* **Método del Codo (Elbow Method):** Identificación del punto de inflexión en la varianza.
* **Análisis de Silueta:** Validación de la cohesión y separación de los clusters.

### 3. Stack Técnico
* **Análisis de Datos:** `Pandas`, `Numpy`
* **Machine Learning:** `Scikit-Learn`, `Yellowbrick`
* **Visualización:** `Plotly` (Interactivo), `Seaborn`

---

## 📈 Conclusiones Estratégicas
Tras el análisis, se identificaron [X] segmentos clave:

1. **Campeones:** Clientes de alto gasto y alta frecuencia. *Estrategia: Programas de recompensas exclusivas.*
2. **Clientes en Riesgo:** Historial de alto valor pero sin actividad reciente. *Estrategia: Campañas de reactivación personalizadas.*
3. **[Nombre del Cluster]:** [Breve descripción]. *Estrategia: [Acción recomendada].*

---

## 📂 Estructura del Proyecto
* `data/`: Datasets originales y procesados.
* `notebooks/`: Análisis exploratorio y modelado detallado.
* `reports/figures/`: Gráficos generados para la toma de decisiones.

---

## 🚀 Cómo Ejecutar este Proyecto

1. Clonar el repositorio:
   ```bash
   git clone [https://github.com/tu-usuario/proyecto-segmentacion.git](https://github.com/tu-usuario/proyecto-segmentacion.git)