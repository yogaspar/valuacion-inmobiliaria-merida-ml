# Valuación de Departamentos en Mérida mediante Machine Learning

## Descripción
Proyecto de modelado predictivo para estimar el precio de departamentos en la zona norte de Mérida, Yucatán.

Se comparan:
- Regresión Lineal (log)
- Random Forest

## Resultados

| Modelo | MAE | RMSE | R² |
|--------|------|------|------|
| Regresión Lineal (log) | 534,128 | 942,138 | 0.829 |
| Random Forest | 300,754 | 544,720 | 0.942 |

## Conclusión
Random Forest captura relaciones no lineales y mejora el desempeño predictivo en aproximadamente 43%.

## Tecnologías
Python, Pandas, Scikit-learn, Matplotlib
