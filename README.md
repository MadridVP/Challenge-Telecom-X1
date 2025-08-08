# Challenge ONE Data Science: Telecom X1
## Descripción del Proyecto
Este proyecto analiza la **evasión de clientes (Churn)** en una empresa de telecomunicaciones, con el objetivo de identificar patrones y factores que influyen en la cancelación del servicio.  
El análisis se enfoca en descubrir las variables y categorias  que ayuden a diseñar estrategias de retención más efectivas.

## Objetivos principales: identificar patrones de comportamiento que conducen el Churn, predecir qué clientes son más propensos a abandonar, y proponer estrategias de retención.

## Estructura del Proyecto
- **`Challenge ONE Data Science: Telecom X1_VM.ipynb`** → Notebook principal con el análisis completo.
- **`TelecomX_Data.json`** → Dataset utilizado en formato JSON.
- **`README.md`** → Documento descriptivo del proyecto.

Herramientas y Librerías Utilizadas
- **Python**
- [Pandas](https://pandas.pydata.org/) – Manipulación y análisis de datos.
- [Matplotlib](https://matplotlib.org/) – Visualización básica.
- [Seaborn](https://seaborn.pydata.org/) – Visualización avanzada.
- [Requests](https://docs.python-requests.org/) – Carga de datos desde URL.
- [NumPy](https://numpy.org/) – Operaciones numéricas.

---

## Análisis Realizado

### 1. Carga y Limpieza de Datos
- Importación del dataset desde archivo JSON.
- Revisión de estructura y tipos de datos.
- Creación de columna `Churn_Label` para facilitar la interpretación (`0 = No se fue`, `1 = Se fue`).

### 2. Análisis Descriptivo
- Cálculo de medidas estadísticas: media, mediana, desviación estándar.
- Distribución general de churn con gráficos de barras y pastel.

### 3. Análisis por Variables Categóricas
- Género: Sin diferencias significativas en evasión.
- Tipo de contrato: *Month-to-month* con mayor tasa de cancelación.
- Método de pago: *Electronic check* con mayor churn.

### 4. Análisis por Variables Numéricas
- **Cargo Total**: Clientes que se fueron muestran gasto medianamente mayor.
- **Tiempo de contrato (tenure)**: Menor permanencia, mayor evasión.

### 5. Análisis de Correlaciones
- Matriz de correlación para variables numéricas.
- Relación entre **Cargo Diario** y churn.
- Relación entre **número de servicios contratados** y churn.

---

## Principales Hallazgos
- **Tipo de contrato** y **método de pago** son fuertes predictores de evasión.
- **Mes a mes + Electronic check** = mayor probabilidad de churn.
- Clientes con **menos de 12 meses** de contrato presentan alto riesgo.
- El **número de servicios** puede influir en la retención.

---

## Recomendaciones
1. Incentivar contratos anuales o bianuales con beneficios.
2. Promover métodos de pago automáticos para mayor retención.
3. Implementar programas de fidelización para clientes nuevos.
4. Hacer seguimiento proactivo a clientes con alto riesgo de churn.
5. Revisar la política de precios para clientes con gasto alto.

---

## Autor: Patricia Madrid
Proyecto desarrollado como parte del **Challenge ONE Data Science – Telecom X1**.

---

