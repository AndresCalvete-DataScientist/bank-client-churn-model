## 🏦 Clasificación de clientes para predicción de abandono en cuentas bancarias

### 📌 Introducción

Este proyecto se centra en la predicción del riesgo de abandono de clientes mediante el análisis de un conjunto de datos históricos.

### Objetivo

El objetivo es construir un modelo de clasificación que permita predecir si un cliente tiene pensado abandonar la compañia, lo cual es vital para la toma de decisiones en instituciones financieras. Esto incluye tareas de análisis exploratorio, preparación de datos, selección de variables, entrenamiento de modelos y evaluación de su rendimiento.

---

### 🧠 Habilidades técnicas demostradas

Este proyecto pone en práctica habilidades fundamentales en ciencia de datos y aprendizaje automático aplicadas al sector financiero:

- **Carga y limpieza de datos**: tratamiento de datos inconsistentes, eliminación de valores nulos.
- **Análisis exploratorio de datos (EDA)**: identificación de patrones entre variables y comportamiento de los clientes.
- **Balanceo de clases**: manejo de clases desbalanceadas mediante técnicas como el ajuste del umbral de clasificación.
- **Modelado predictivo supervisado**: entrenamiento de clasificadores robustos y comparación de su desempeño.
- **Evaluación de modelos**: análisis de métricas como F1-score y curvas ROC.
- **Visualización**: apoyo gráfico al análisis para una mejor interpretación del comportamiento de las variables.

---

### 🛠️ Tecnologías y herramientas utilizadas

- **Python**: lenguaje base del proyecto.
- **pandas / numpy**: manipulación y análisis de estructuras de datos.
- **matplotlib**: visualización de patrones y relaciones.
- **scikit-learn**: para el entrenamiento, validación y evaluación de modelos.
- **Métodos clave**: `.train_test_split()`, `.RandomForestClassifier()`, `.StandardScaler()`, `.get_dummies()`, `.OrdinalEncoder()`, `.f1_score()`, `.roc_auc_score()`.

---

### ✅ Resultados y conclusiones

- Se logró una mejora significativa en la capacidad del modelo para detectar clientes en riesgo, especialmente tras aplicar balanceo de clases.
- El modelo seleccionado mostró un buen equilibrio entre precisión y recall, crucial en contextos financieros donde los falsos negativos son costosos.
- Explorando con los hiperparámetros del modelo logramos obtener una métrica de F1 de 0.63 y un área bajo la curva ROC de 0.86.

---

### 👨‍💻 Autor

**Andrés Calvete**  
Científico de Datos Junior  
[LinkedIn](https://www.linkedin.com/in/andrescalvete/)  
ascalvete@hotmail.com
