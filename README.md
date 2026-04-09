# Análisis de Intensidad de Carbono y Eficiencia Energética Global

Este repositorio contiene un análisis técnico sobre la relación entre las emisiones de dióxido de carbono ($CO_2$) y el consumo de energía primaria a nivel internacional. El objetivo es evaluar la **Intensidad de Carbono**, una métrica clave para entender la sostenibilidad de las matrices energéticas nacionales.

## 📈 Fundamento Teórico

Para este análisis, se define la **Intensidad de Carbono** ($I_{C}$) como la relación entre las emisiones per cápita y el consumo de energía primaria per cápita:

$$I_{C} = \frac{E_{CO_{2}}}{E_{Energía}}$$

Donde:
* $E_{CO_{2}}$: Emisiones de toneladas de $CO_2$ por persona.
* $E_{Energía}$: Consumo de energía primaria en kilovatios-hora (kWh) por persona.

Esta métrica permite identificar qué tan "limpia" es la generación de energía de un país, independientemente de su riqueza o población.

## 🛠️ Herramientas y Librerías

El análisis fue desarrollado en **Python**, utilizando el stack científico estándar:
* **Pandas**: Limpieza y manipulación de series temporales.
* **Matplotlib & Seaborn**: Generación de visualizaciones estadísticas de alta resolución (300 DPI).
* **NumPy**: Operaciones vectorizadas para el cálculo de métricas.

## Visualizaciones 
![¿A más riqueza, más energía renovable?](¿A_más_riqueza_más_energía_renovable?.png)
![Adopción de Energías Renovables por País (Per Cápita)](Adopción_de_Energías_Renovables.png)
![Porcentaje de Energía Renovable en el Consumo Total (Año más reciente)](Porcentaje_de_Energía_Renovable.png)
