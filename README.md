## Descripción del Proyecto

Este proyecto implementa un pipeline completo de **Machine Learning para el descubrimiento de materiales superconductores**, desde el análisis exploratorio de datos hasta el diseño inverso de materiales con propiedades óptimas. El objetivo principal es predecir la **temperatura crítica ($T_c$)** de superconductores basándose en propiedades atómicas y estadísticas de sus elementos constituyentes, e identificar las características químicas necesarias para alcanzar la superconductividad a temperatura ambiente.

### Objetivos
- Desarrollar un modelo predictivo robusto para la temperatura crítica de superconductores
- Identificar las propiedades atómicas más influyentes mediante técnicas de explicabilidad (SHAP)
- Determinar mediante optimización global las características ideales para maximizar $T_c$
- Proporcionar un framework reproducible para el diseño inverso de materiales

### Resultados y conclusiones
-  El modelo más eficiente en términos de uso de recursos computacionales fue Gradient Boosting
-  Se obtuvo un R2 de 0.9110 para gradient boosting y de 0.9187 para Random Forest
-  Utilizando la química encontrada en el dataset la máxima temperatura crítica predicha es de 178.62 K (-94.53 °C)
-  No se puede desarrollar un superconductor con los datos del dataset pero se puede observar que la mayor varianza en la conductividad térmica de la aleación contribuye al aumento de la temperatura crítica
