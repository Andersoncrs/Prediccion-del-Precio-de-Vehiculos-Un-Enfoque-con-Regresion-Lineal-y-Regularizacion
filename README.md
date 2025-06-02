# Predicción del Precio de Vehículos: Un Enfoque con Regresión Lineal y Regularización

Este repositorio contiene un análisis completo orientado a la **predicción del valor de vehículos** usando técnicas de regresión lineal y regularización Lasso. El objetivo es construir modelos predictivos robustos y comprensibles que permitan estimar el precio de un automóvil a partir de sus características principales.

---

## Contenido del Análisis

El flujo de trabajo seguido en el análisis incluye los siguientes pasos:

1. **Exploración y Limpieza de los Datos**
   - Se inspeccionó el conjunto de datos, identificando la estructura y los tipos de variables.
   - Se eliminaron variables irrelevantes (como `Car_Name`) y se transformó la columna `Year` en una nueva característica de `Age` (antigüedad).
   - Se verificó la ausencia de valores faltantes y se validaron los formatos de los datos.

2. **Análisis Estadístico y Visualización**
   - Se calcularon estadísticas descriptivas de las variables numéricas y categóricas.
   - Se emplearon gráficos para visualizar la distribución de los datos y detectar posibles valores atípicos.

3. **Construcción del Modelo de Regresión Lineal**
   - Se desarrolló un modelo de regresión lineal base para predecir el precio de venta (`Selling_Price`) utilizando las variables seleccionadas.
   - Se evaluó el desempeño del modelo mediante métricas como $R^2$, MSE y RMSE.

4. **Ampliación con Términos Polinomiales**
   - Se incorporaron términos polinomiales para capturar relaciones no lineales entre las variables independientes y el precio.

5. **Optimización con Regularización Lasso**
   - Se aplicó la regularización Lasso para mejorar la generalización del modelo y reducir el sobreajuste, seleccionando automáticamente las variables más relevantes.

---

## Conocimientos Aplicados

Durante el desarrollo de este proyecto se profundizó en:

- **Pre-procesamiento de Datos**
  - Importancia de limpiar y transformar los datos para obtener mejores resultados en los modelos predictivos.
  - Conversión de variables temporales en variables de mayor relevancia para el problema (por ejemplo, transformar el año de fabricación en antigüedad).

- **Regresión Lineal y Métricas de Evaluación**
  - Comprensión del funcionamiento de la regresión lineal y sus supuestos.
  - Interpretación de métricas de desempeño ($R^2$, MSE, RMSE) para evaluar la calidad del modelo.

- **Regularización**
  - Uso de Lasso para prevenir el sobreajuste y realizar selección automática de características.
  - Análisis de la importancia relativa de cada variable y cómo la regularización puede simplificar modelos complejos.

- **Visualización y Análisis Exploratorio**
  - Utilización de herramientas gráficas para entender la distribución y las relaciones entre variables.

---

## Beneficios y Resultados Obtenidos

- **Modelo Predictivo Preciso:** El análisis permitió construir un modelo capaz de estimar el precio de un vehículo con buen nivel de precisión, validado mediante técnicas de validación cruzada.

- **Interpretabilidad:** Gracias a la regularización Lasso, se identificaron las variables más influyentes en el precio del vehículo, facilitando la interpretación de los resultados y la toma de decisiones.

- **Metodología Reproducible:** El flujo de trabajo implementado es claro, documentado y puede ser adaptado para otros conjuntos de datos similares o ampliado con nuevas técnicas de machine learning.

- **Herramienta de Valor para Negocios:** El modelo desarrollado puede ser utilizado por concesionarios, vendedores particulares o plataformas de compra-venta de autos para estimar precios de manera objetiva y fundamentada.

---

## Estructura del Repositorio

- `analisis.ipynb`: Notebook principal con todo el análisis, visualizaciones y construcción de modelos.
- `car data.csv`: Conjunto de datos base utilizado para el análisis.

---

## Conclusión

Este proyecto demuestra cómo un enfoque sistemático de análisis de datos, combinado con técnicas estadísticas y de machine learning, puede generar modelos predictivos robustos y útiles para el mundo real. Los conocimientos aplicados permiten abordar problemas similares en diferentes contextos y abren la puerta a futuras mejoras, como el uso de modelos más avanzados o el análisis de nuevos conjuntos de datos.

---

