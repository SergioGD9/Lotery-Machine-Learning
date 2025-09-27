# EuroMillions ML (Demo educativa)

Este repositorio contiene:
- Un **notebook** (`EuroMillions_ML_Notebook.ipynb`) con análisis, *feature engineering* y un modelo base.
- Un **dataset limpio** (`euromillones_clean.csv`) generado desde histórico 2004–2025.
- Un **borrador de post** para LinkedIn (`LinkedIn_Post_ES.md`).

## Estructura de datos
- `draw_date`: fecha del sorteo
- `ball1..ball5`: bolas (orden ascendente)
- `star1, star2`: estrellas (orden ascendente)
- `draw_id`, `dow`, `year`, `month`: variables auxiliares

## Aviso
Predecir combinaciones exactas es esencialmente aleatorio. El objetivo es didáctico: construir *pipelines* reproducibles, validar sin *leakage* y comunicar resultados con honestidad.
