# 📊 Predicción de Cancelación de Clientes (Churn) - TelecomX

## 📌 Descripción del Proyecto

La cancelación de clientes (**Churn**) es uno de los principales problemas para empresas de telecomunicaciones, ya que implica pérdida de ingresos y costos adicionales para adquirir nuevos clientes.

El objetivo de este proyecto es **desarrollar modelos de Machine Learning capaces de predecir qué clientes tienen mayor probabilidad de cancelar sus servicios en TelecomX**, permitiendo a la empresa implementar estrategias de retención basadas en datos.

Para ello se aplicaron técnicas de **análisis de datos y modelos de clasificación**, evaluando su desempeño mediante diferentes métricas de Machine Learning.

---

# 🎯 Objetivos

- Analizar los factores que influyen en la cancelación de clientes.
- Construir modelos de **Machine Learning** para predecir el churn.
- Evaluar el desempeño de los modelos utilizando métricas de clasificación.
- Identificar **variables clave** que influyen en la cancelación.
- Proponer **estrategias de retención de clientes basadas en datos**.

---

# 🧠 Modelos Utilizados

Se implementaron dos modelos de clasificación:

### Regresión Logística
Modelo estadístico utilizado para predecir la probabilidad de cancelación de un cliente.  
Su principal ventaja es la **interpretabilidad**, ya que permite analizar cómo cada variable influye en el churn.

### Random Forest
Modelo basado en **árboles de decisión** que permite capturar relaciones más complejas entre las variables y mejorar la capacidad predictiva.

---

# 📈 Evaluación de los Modelos

Para evaluar el rendimiento de los modelos se utilizaron las siguientes métricas:

- Matriz de Confusión
- Accuracy
- Precision
- Recall
- F1-score
- Curva ROC y AUC

### Resultados del modelo (Regresión Logística)

| Métrica | Resultado |
|------|------|
| Accuracy | 0.74 |
| Precision (Churn) | 0.51 |
| Recall (Churn) | 0.79 |
| F1-Score (Churn) | 0.62 |

Estos resultados muestran que el modelo tiene una **buena capacidad para identificar clientes con riesgo de cancelación**, lo cual es especialmente importante en problemas de churn.

---

# 🔎 Factores Clave en la Cancelación de Clientes

A partir del análisis de los modelos, se identificaron las variables más influyentes en la cancelación:

### Tipo de contrato
Los clientes con contratos **Month-to-Month** presentan mayor probabilidad de cancelar el servicio.

### Tiempo de permanencia (Tenure)
Los clientes con **menor tiempo en la empresa** tienen mayor tendencia a cancelar.

### Cargos mensuales
Clientes con **cargos mensuales altos** muestran mayor probabilidad de churn.

### Servicios adicionales
La ausencia de servicios adicionales como **soporte técnico o seguridad en línea** puede aumentar la probabilidad de cancelación.

---

# 💡 Estrategias de Retención Propuestas

Basado en los resultados del análisis, se sugieren las siguientes estrategias:

- Implementar **programas de fidelización para nuevos clientes**
- Incentivar **contratos a largo plazo**
- Optimizar los **planes y precios del servicio**
- Promover **paquetes de servicios adicionales**

Estas acciones pueden ayudar a **reducir la tasa de cancelación y mejorar la retención de clientes**.

---

# 🛠 Tecnologías Utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

---

# 📂 Estructura del Proyecto


TelecomX2
│
├── TelecomX_LATAM_PARTE_2.ipynb
└── README.md




📊 Resultados

El análisis permitió identificar los factores que más influyen en la cancelación de clientes y desarrollar modelos predictivos que permiten detectar clientes con alto riesgo de churn.

Esto permite a la empresa tomar decisiones estratégicas basadas en datos para mejorar la retención de clientes.

👨‍💻 Autor

Jorge Andrés Rodrriguez Romero 

Proyecto desarrollado como parte de práctica de Data Analytics / Machine Learning.
