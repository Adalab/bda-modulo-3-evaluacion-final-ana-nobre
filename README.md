# ✈️ Análisis de Clientes del Programa de Lealtad – Evaluación Final

Este repositorio contiene el ejercicio de evaluación final del Módulo 3 del Bootcamp de Análisis de Datos. Trabajamos con dos conjuntos de datos sobre el comportamiento y perfil de clientes de un programa de lealtad de una aerolínea.

## 📂 Archivos utilizados

- `Customer Flight Activity.csv`: Información mensual sobre vuelos, puntos acumulados/redimidos, y distancia.  
- `Customer Loyalty History.csv`: Datos demográficos y de membresía de los clientes.  
- `Fase_1.ipynb`, `Fase_2.ipynb`, `Fase_3.ipynb`: Notebooks que contienen las distintas etapas del análisis (limpieza, exploración, visualización y análisis estadístico).

## 🧠 Objetivos del análisis

- Limpieza y unión de datos  
- Exploración estadística  
- Visualización de patrones  
- Análisis inferencial sobre el comportamiento de los clientes

## 🛠️ Tecnologías usadas

- Python (pandas, numpy, seaborn, matplotlib, scipy)  
- Jupyter Notebook  
- Git & GitHub

## 📊 Ejemplo de código aplicado

```python
import pandas as pd

# Cargar y estandarizar columnas
df = pd.read_csv("Customer Flight Activity.csv")
df_flight.columns = df_flight.columns.str.strip().str.lower()

# Verificar nulos
(df_flight.isnull().mean() * 100).round(2)

# Distribución de vuelos reservados por mes
import seaborn as sns
import matplotlib.pyplot as plt

# Calcular o coeficiente de Pearson
correlation, valor_p = pearsonr(df['Distance'], df['Points Accumulated'])
