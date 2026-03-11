Telecom X – Predicción de Cancelación de Clientes (Churn)

📌 Descripción del Proyecto

Este proyecto forma parte del desafío Telecom X – Parte 2, cuyo objetivo es desarrollar modelos de Machine Learning capaces de predecir la cancelación de clientes (Churn).

A partir de un conjunto de datos previamente tratado en la primera parte del desafío, se construyen modelos predictivos que permiten identificar qué clientes tienen mayor probabilidad de cancelar sus servicios.

Este tipo de análisis permite a las empresas anticiparse al problema de la cancelación y diseñar estrategias de retención más efectivas.

---

🎯 Objetivos

- Preparar los datos para modelos de Machine Learning.
- Analizar la relación entre variables y la cancelación de clientes.
- Entrenar modelos de clasificación para predecir Churn.
- Evaluar el rendimiento de los modelos con métricas de desempeño.
- Identificar los factores que más influyen en la cancelación.
- Proponer estrategias de retención basadas en datos.

---

🧰 Tecnologías Utilizadas

- Python
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-learn

---

📂 Estructura del Proyecto

TelecomX_Churn_Prediction
│
├── TelecomX_parte2.ipynb
├── datos_tratados.csv
└── README.md

---

⚙️ Etapas del Proyecto

1️⃣ Preparación de los datos

Se cargó el dataset previamente tratado en la Parte 1 del desafío.

Durante esta etapa se realizaron las siguientes acciones:

- Eliminación de columnas irrelevantes (como identificadores de cliente).
- Eliminación de valores faltantes.
- Conversión de variables categóricas a variables numéricas mediante One-Hot Encoding.
- Análisis de la proporción de cancelación de clientes.

---

2️⃣ Análisis de correlación

Se realizó una matriz de correlación para identificar relaciones entre las variables y detectar posibles factores asociados a la cancelación de clientes.

Este análisis permite comprender mejor el comportamiento de los datos antes de construir los modelos.

---

3️⃣ Modelado predictivo

El dataset fue dividido en:

- 80% entrenamiento
- 20% prueba

Se entrenaron dos modelos de clasificación:

1. Regresión Logística

Modelo estadístico utilizado para predecir probabilidades de pertenencia a una clase.

Este modelo requiere normalización de los datos.

2. Random Forest

Modelo basado en múltiples árboles de decisión que permite capturar relaciones complejas entre las variables.

Este modelo no requiere normalización.

---

📊 Evaluación de Modelos

Los modelos fueron evaluados utilizando las siguientes métricas:

- Accuracy (Exactitud)
- Precision
- Recall
- F1-score
- Matriz de confusión

Estas métricas permiten evaluar la capacidad del modelo para identificar correctamente a los clientes que cancelan el servicio.

---

🔎 Importancia de Variables

Se analizó la importancia de las variables utilizando el modelo Random Forest.

Las variables que mostraron mayor impacto en la predicción de cancelación fueron:

- Tipo de contrato
- Antigüedad del cliente (tenure)
- Cargos mensuales
- Método de pago
- Servicios adicionales contratados

---

📈 Resultados

Entre los modelos evaluados, Random Forest presentó mejor desempeño general, mostrando mayor capacidad para capturar relaciones no lineales en los datos.

El modelo logró identificar patrones relevantes asociados a la cancelación de clientes.

---

🧠 Conclusiones

El análisis permitió identificar algunos factores clave asociados al churn:

- Clientes con contratos mensuales presentan mayor probabilidad de cancelar.
- Clientes con menor tiempo de permanencia tienen mayor riesgo de churn.
- Cargos mensuales más altos pueden aumentar la probabilidad de cancelación.
- Algunos métodos de pago y servicios adicionales influyen en la decisión del cliente.

---

💡 Estrategias de Retención Propuestas

Basándose en los resultados obtenidos, se sugieren las siguientes estrategias:

- Incentivar contratos de largo plazo mediante beneficios o descuentos.
- Implementar programas de fidelización para clientes nuevos.
- Ofrecer paquetes de servicios con mejor relación precio-beneficio.
- Mejorar el soporte técnico y la atención al cliente.

Estas estrategias pueden ayudar a reducir la tasa de cancelación y aumentar la satisfacción de los clientes.

---

👨‍💻 Autor

Proyecto desarrollado por Nestor Rubin de Celis como parte del desafío de Análisis de Datos y Machine Learning.
