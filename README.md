# 📊 Análisis de Evasión de Clientes - Telecom X

## 🚀 Descripción del Proyecto

Este proyecto forma parte de un desafío de análisis de datos de la empresa ficticia **Telecom X**, cuyo objetivo es reducir la **evasión de clientes (churn)**. A través de técnicas de limpieza, transformación y análisis exploratorio de datos (EDA), se identificaron patrones relevantes que permitirán mejorar la retención de clientes.

El análisis fue desarrollado en **Google Colab** usando datos proporcionados desde un archivo JSON.

---

## 🧠 Objetivos del Análisis

- Analizar el comportamiento de los clientes que cancelaron el servicio.
- Limpiar y estandarizar los datos para su análisis.
- Visualizar patrones y relaciones entre variables numéricas y categóricas.
- Generar recomendaciones estratégicas basadas en los datos.

---

## 📦 Tecnologías utilizadas

El proyecto fue desarrollado en **Google Colab** con las siguientes bibliotecas:

- pandas
- numpy
- matplotlib
- seaborn
- plotly

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/garin06/TelecomX/blob/main/Challenge_TelecomX_Eduardo_Garin.ipynb)

---

## 🧹 Limpieza y transformación de datos

- Se corrigieron valores nulos y vacíos.
- Se creó una nueva variable: **Facturación diaria**.
- Se tradujeron nombres de columnas y valores para facilitar su interpretación.
- Se mantuvieron los valores de churn desconocidos como `"Desconocido"` para análisis posteriores.

---

## 📊 Análisis Exploratorio de Datos

Se analizaron variables categóricas y numéricas para identificar patrones:

- 📈 **Distribución de la evasión**
- 📊 **Evasión según género, contrato, forma de pago, etc.**
- 📦 **Boxplots e histogramas para analizar facturación y duración de contratos**
- 🧩 Agrupaciones y promedios por tipo de cliente

Visualizaciones interactivas realizadas con **Plotly** y gráficas tradicionales con **Seaborn** y **Matplotlib**.

---

## 🧠 Conclusiones

- Los clientes con **contrato mensual**, **facturación alta** y **pocos servicios contratados** tienden a cancelar más.
- Clientes con servicios como **soporte técnico** o **seguridad en línea** tienden a permanecer más tiempo.
- Los métodos de pago **automáticos** muestran menor tasa de evasión.
- La mayoría de las cancelaciones ocurren en los **primeros meses del contrato**.

---

## 💡 Recomendaciones

- Fomentar **contratos anuales o bianuales** con incentivos.
- Promocionar servicios adicionales (como soporte técnico).
- Estimular el uso de **pagos automáticos** con descuentos.
- Implementar estrategias de retención en los **primeros 3 meses** de contrato.

---

## 👤 Autor

**Eduardo Garin**  
