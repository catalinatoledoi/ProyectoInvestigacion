# Perfiles de Alto Costo en la Salud Pública Chilena (GRD 2024)

Este repositorio contiene el análisis estadístico e inferencial del **Segundo Avance** para el proyecto de identificación de perfiles clínicos asociados a un alto consumo de recursos hospitalarios, utilizando datos de Egresos Hospitalarios (GRD) del MINSAL.

## 📋 Descripción del Proyecto
El objetivo central es determinar si existen patrones predecibles (edad, sexo, severidad, ubicación) que definan al "paciente de alto costo", operacionalizado como aquel situado sobre el **Percentil 75 (P75)** de la distribución del Peso Relativo.

## 📊 Hallazgos Clave
- **Perfil de Riesgo:** Hombres mayores de 60 años con severidad Nivel 3 (Mediana: $606.000).
- **Concentración (80/20):** El 20% de los beneficiarios concentra el 79.6% del gasto total.
- **Punto de Inflexión:** El costo se duplica al superar los **7 días** de estadía hospitalaria.
- **Predicción:** El modelo de regresión lineal explica el **32%** de la varianza del gasto ($R^2=0.32$).

## 📁 Estructura del Repositorio
- `final.ipynb`: Cuaderno Jupyter con el flujo completo de limpieza, EDA, tests de hipótesis y modelos.
- `Avance2_LaraToledo.pdf`: Informe técnico detallado con la narrativa y justificación académica.

## 🛠️ Requisitos y Tecnologías
- **Lenguaje:** Python 3.9+
- **Librerías Principales:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`, `scipy`.
- **Análisis Estadístico:** Test de Kruskal-Wallis, Regresión OLS, Análisis de Pareto.

## 🚀 Ejecución
1. Clonar el repositorio.
2. Asegurar la presencia de los archivos de datos en la carpeta `/data/` según las rutas definidas en el notebook.
3. Se recomienda usar pyarrow para que vaya más rápido la lectura del GRD.
4. Ejecutar las celdas del archivo `final.ipynb` secuencialmente.

## 👥 Integrantes
- Josefa Lara
- Catalina Toledo
