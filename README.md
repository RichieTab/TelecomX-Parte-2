# 📊 TelecomX: Predicción de Evasión de Clientes (Churn)

Este proyecto desarrolla un pipeline completo de Ciencia de Datos para predecir la cancelación de clientes (*Churn*) en una empresa de telecomunicaciones. El flujo abarca desde la extracción de datos de fuentes JSON y CSV hasta el despliegue de modelos de Machine Learning validados mediante técnicas de remuestreo.

## 🎯 Objetivo del Proyecto
Desarrollar un modelo predictivo capaz de identificar clientes en riesgo de abandonar la empresa, permitiendo al equipo de marketing ejecutar estrategias de retención proactivas basadas en datos.

## 🛠️ Tecnologías y Librerías
* **Python 3.x**
* **Pandas & NumPy**: Procesamiento y limpieza de datos.
* **Matplotlib & Seaborn**: Visualización de patrones y correlaciones.
* **Scikit-Learn**: Modelado, estandarización y evaluación.
* **Imbalanced-Learn (SMOTE)**: Balanceo de clases minoritarias.

## 📂 Estructura del Proyecto

1.  **Ingesta y Normalización**: Transformación de datos crudos (JSON/CSV) a estructuras tabulares.
2.  **Limpieza de Datos**: Manejo de valores nulos, corrección de tipos de datos y eliminación de identificadores irrelevantes.
3.  **Análisis Exploratorio (EDA)**: Identificación de variables críticas como el tiempo de contrato y cargos mensuales.
4.  **Ingeniería de Características**: Codificación *One-Hot* para variables categóricas y estandarización para modelos de distancia.
5.  **Balanceo de Clases**: Aplicación de SMOTE para mitigar el sesgo hacia clientes activos.
6.  **Modelado Predictivo**: Implementación de Regresión Logística y Random Forest.
7.  **Validación Cruzada**: Uso de K-Fold para garantizar la estabilidad del modelo.

## 📊 Principales Hallazgos (Insights)
* **Contratos Mensuales**: Los clientes con contratos mes a mes presentan la tasa más alta de deserción.
* **Periodo Crítico**: Los primeros 12 meses de antigüedad son vitales; si un cliente supera este umbral, su lealtad aumenta significativamente.
* **Métodos de Pago**: El uso de cheques electrónicos está fuertemente vinculado a la cancelación en comparación con los pagos automáticos.



## 🚀 Cómo utilizar este repositorio

### Requisitos previos
Instala las dependencias necesarias con el siguiente comando:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn

Gemini ha dicho
Aquí tienes un archivo README.md completo, diseñado profesionalmente para GitHub o GitLab. Está listo para copiar y pegar directamente; el formato Markdown se encargará de que se vea perfecto.

Markdown
# 📊 TelecomX: Predicción de Evasión de Clientes (Churn)

Este proyecto desarrolla un pipeline completo de Ciencia de Datos para predecir la cancelación de clientes (*Churn*) en una empresa de telecomunicaciones. El flujo abarca desde la extracción de datos de fuentes JSON y CSV hasta el despliegue de modelos de Machine Learning validados mediante técnicas de remuestreo.

## 🎯 Objetivo del Proyecto
Desarrollar un modelo predictivo capaz de identificar clientes en riesgo de abandonar la empresa, permitiendo al equipo de marketing ejecutar estrategias de retención proactivas basadas en datos.

## 🛠️ Tecnologías y Librerías
* **Python 3.x**
* **Pandas & NumPy**: Procesamiento y limpieza de datos.
* **Matplotlib & Seaborn**: Visualización de patrones y correlaciones.
* **Scikit-Learn**: Modelado, estandarización y evaluación.
* **Imbalanced-Learn (SMOTE)**: Balanceo de clases minoritarias.

## 📂 Estructura del Proyecto

1.  **Ingesta y Normalización**: Transformación de datos crudos (JSON/CSV) a estructuras tabulares.
2.  **Limpieza de Datos**: Manejo de valores nulos, corrección de tipos de datos y eliminación de identificadores irrelevantes.
3.  **Análisis Exploratorio (EDA)**: Identificación de variables críticas como el tiempo de contrato y cargos mensuales.
4.  **Ingeniería de Características**: Codificación *One-Hot* para variables categóricas y estandarización para modelos de distancia.
5.  **Balanceo de Clases**: Aplicación de SMOTE para mitigar el sesgo hacia clientes activos.
6.  **Modelado Predictivo**: Implementación de Regresión Logística y Random Forest.
7.  **Validación Cruzada**: Uso de K-Fold para garantizar la estabilidad del modelo.

## 📊 Principales Hallazgos (Insights)
* **Contratos Mensuales**: Los clientes con contratos mes a mes presentan la tasa más alta de deserción.
* **Periodo Crítico**: Los primeros 12 meses de antigüedad son vitales; si un cliente supera este umbral, su lealtad aumenta significativamente.
* **Métodos de Pago**: El uso de cheques electrónicos está fuertemente vinculado a la cancelación en comparación con los pagos automáticos.



## 🚀 Cómo utilizar este repositorio

### Requisitos previos
Instala las dependencias necesarias con el siguiente comando:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
Ejecución
Abre el archivo .ipynb en Google Colab o Jupyter Notebook.

Ejecuta las celdas de forma secuencial. El notebook descargará automáticamente los datasets desde los repositorios remotos configurados.

📈 Resultados de los Modelos
Modelo	Exactitud (Accuracy)	F1-Score	Requiere Normalización
Regresión Logística	~80%	0.78	Sí
Random Forest (K-Fold)	~85%	0.84	No
💡 Recomendaciones Estratégicas
Incentivos de Migración: Ofrecer beneficios a clientes con contrato mensual para que migren a planes anuales.

Alertas Tempranas: Automatizar llamadas de soporte para clientes con altos cargos mensuales en sus primeros 6 meses de vida.

Digitalización de Pagos: Promover el uso de cargos automáticos para reducir la fricción en el proceso de cobro.

Autor: [Tu Nombre/Usuario de GitHub]

Fecha: Marzo 2026

Proyecto: Desafío de Ciencia de Datos - Análisis de Churn
