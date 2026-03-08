<div align="center">

# 📡 TELECOM X — CUSTOMER CHURN ANALYSIS

### Análisis exploratorio de evasión de clientes para estrategias de retención

</div>

---

## 📋 Descripción del proyecto

Este proyecto analiza el comportamiento de cancelación de clientes (**churn**) en la empresa ficticia **Telecom X**, una compañía de telecomunicaciones que enfrenta una **alta tasa de pérdida de clientes**.

El objetivo principal es identificar **patrones y factores asociados a la evasión de clientes** mediante un proceso completo de **ETL (Extracción, Transformación y Carga)** y **Análisis Exploratorio de Datos (EDA)**.

A través del análisis de variables demográficas, características del servicio contratado y patrones de facturación, se generan **insights accionables** que pueden apoyar al equipo de **Data Science** en el desarrollo de modelos predictivos y estrategias de retención.

---

## 🛠️ Tecnologías utilizadas

<div align="center">

| Tecnología | Uso |
|------------|-----|
| <img src="https://img.icons8.com/color/48/000000/python.png" width="20"/> Python | Lenguaje principal |
| <img src="https://img.icons8.com/color/48/000000/pandas.png" width="20"/> Pandas | Manipulación y análisis de datos |
| <img src="https://img.icons8.com/color/48/000000/matplotlib.png" width="20"/> Matplotlib | Visualización de datos |
| <img src="https://img.icons8.com/color/48/000000/google-logo.png" width="20"/> Google Colab | Entorno de desarrollo |

</div>

---

## 🔍 Análisis realizados

Durante el proyecto se desarrollaron las siguientes etapas de análisis:

| # | Análisis | Descripción |
|---|---------|-------------|
| 1️⃣ | **Extracción de datos** | Obtención de datos desde una API en formato JSON |
| 2️⃣ | **Limpieza y transformación** | Identificación de valores nulos, inconsistencias y estandarización |
| 3️⃣ | **Ingeniería de variables** | Creación de la variable **cuenta diaria** a partir de cargos mensuales |
| 4️⃣ | **Distribución de churn** | Análisis de proporción de clientes que cancelan vs permanecen |
| 5️⃣ | **Churn por variables categóricas** | Evaluación por contrato, método de pago, género y servicios |
| 6️⃣ | **Churn por variables numéricas** | Análisis de cargos mensuales, cargos totales y antigüedad del cliente |

---

## 💡 Principales hallazgos

<div align="center">

| Insight | Descripción |
|---------|-------------|
| 📉 **Contratos mensuales con mayor churn** | Los clientes con contratos *month-to-month* presentan la tasa más alta de cancelación |
| ⏳ **Antigüedad del cliente como factor clave** | Los clientes con menor **tenure** tienen mayor probabilidad de abandonar el servicio |
| 💳 **Método de pago asociado al churn** | El método **Electronic Check** muestra mayor proporción de cancelaciones |
| 📦 **Más servicios = menor evasión** | Clientes con más servicios adicionales presentan menor tasa de churn |

</div>

---

## 📊 Perfil de cliente con mayor riesgo de churn

Basado en el análisis exploratorio, el perfil típico de cliente con mayor probabilidad de cancelar el servicio es:

- 📅 Contrato **month-to-month**
- 💳 Método de pago **Electronic Check**
- ⏳ Antigüedad baja (**tenure < 12 meses**)
- 💰 **Cargos mensuales relativamente altos**
- 📦 **Pocos servicios adicionales contratados**

Este perfil puede utilizarse como base para **modelos predictivos de churn** y campañas de retención.

---

## 📈 Recomendaciones estratégicas

A partir de los hallazgos obtenidos, Telecom X podría considerar las siguientes acciones:

- 🎯 Incentivar **contratos de largo plazo** mediante descuentos o beneficios
- 🤝 Diseñar **estrategias de retención temprana** para clientes nuevos
- 📦 Promover **paquetes de servicios combinados**
- 💬 Implementar campañas dirigidas a clientes con **alto riesgo de churn**

Estas medidas podrían ayudar a **reducir la tasa de cancelación y mejorar la fidelización de clientes**.

---

## 📁 Estructura del proyecto

📦 telecomx-churn-analysis
├── 📓 telecomx_churn_analysis.ipynb # Notebook principal de análisis
├── 📊 data/ # Datos utilizados en el proyecto
└── 📄 README.md # Documentación del proyecto


---

<div align="center">

### 👨‍💻 Autor

**Alan Rodríguez**  
*Oracle Next Education — Alura Latam*

</div>

---

<div align="center">

[![Python](https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python&logoColor=white)]()
[![Pandas](https://img.shields.io/badge/Pandas-2.0+-purple?style=for-the-badge&logo=pandas&logoColor=white)]()
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.5+-orange?style=for-the-badge&logo=matplotlib&logoColor=white)]()
[![Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)]()

</div>
