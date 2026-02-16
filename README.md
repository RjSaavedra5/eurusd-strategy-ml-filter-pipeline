# Proyecto Fin de Máster: Trading Algorítmico con Machine Learning

Este repositorio contiene el código y los notebooks desarrollados como apoyo para mi Proyecto de Fin de Máster. El objetivo del proyecto es el diseño, validación y optimización de una estrategia de trading algorítmico sobre el par EUR/USD, integrando técnicas de Machine Learning para mejorar la toma de decisiones.

## Estructura del Repositorio

El proyecto se divide en 7 etapas principales, documentadas en los siguientes notebooks:

### [01_descarga_tickdata_eurusd.ipynb](01_descarga_tickdata_eurusd.ipynb)
**Descarga y Verificación de Datos**
*   Descarga de datos históricos de tick (tick data) para el par EUR/USD.
*   Procesamiento y verificación de la calidad e integridad de los datos para asegurar una base sólida para el backtesting.

### [02_strategy_design_gridsearch.ipynb](02_strategy_design_gridsearch.ipynb)
**Diseño de Estrategia y GridSearch**
*   Definición de la lógica de la estrategia de trading base.
*   Ejecución de una búsqueda de rejilla (GridSearch) para identificar los parámetros y marcos temporales donde la estrategia muestra mejor desempeño preliminar.

### [03_backtest_baseline_candles_strategy.ipynb](03_backtest_baseline_candles_strategy.ipynb)
**Backtest Final (Baseline)**
*   Ejecución del backtest "baseline" (estrategia base sin Machine Learning) utilizando los parámetros optimizados.
*   Establecimiento de las métricas de referencia para comparar con las mejoras posteriores.

### [04_analisis_backtest_final.ipynb](04_analisis_backtest_final.ipynb)
**Análisis de Trades (Baseline)**
*   Análisis exploratorio detallado de las operaciones generadas por la estrategia base.
*   Identificación de patrones en operaciones ganadoras y perdedoras que puedan ser explotados por modelos de ML.

### [05_ml_longs.ipynb](05_ml_longs.ipynb)
**Machine Learning para Operaciones en Largo**
*   Ingeniería de características (feature engineering) específica para compras (Longs).
*   Entrenamiento, validación y selección de modelos de ML para filtrar y optimizar las señales de entrada en largo.

### [06_ml_shorts.ipynb](06_ml_shorts.ipynb)
**Machine Learning para Operaciones en Corto**
*   Ingeniería de características específica para ventas (Shorts).
*   Entrenamiento y validación de modelos para mejorar la eficacia de las señales de entrada en corto.

### [07_resultados_finales.ipynb](07_resultados_finales.ipynb)
**Resultados Finales y Validación**
*   Integración de los modelos de ML (Longs + Shorts) con la estrategia base.
*   Comparativa final de rendimiento: Estrategia Baseline vs. Estrategia Potenciada por ML.
*   Validación estadística de los resultados para confirmar la robustez del sistema.

---
*Este código se proporciona con fines académicos y de investigación.*
