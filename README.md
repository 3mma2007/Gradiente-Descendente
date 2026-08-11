# Implementación de Gradiente Descendente en Regresión Lineal

Implementación desde cero (sin librerías de Machine Learning) del algoritmo de **Gradiente Descendente** para ajustar un modelo de regresión lineal simple, con validación posterior de los resultados usando `scikit-learn`.

## 📋 Descripción

Este notebook desarrolla, paso a paso, el algoritmo de gradiente descendente para encontrar los coeficientes óptimos (β0 y β1) de una regresión lineal simple del tipo:

```
y = β0 + β1 * x
```

El proceso incluye:

1. **Análisis exploratorio**: carga de datos en un `DataFrame` de pandas y cálculo de la correlación entre variables.
2. **Gradiente descendente manual**: inicialización de los parámetros, definición de la tasa de aprendizaje (`eta`) y del criterio de convergencia (`epsilon`), y actualización iterativa de β0 y β1 minimizando el Error Cuadrático Medio (MSE).
3. **Visualización**: gráfico de la recta de regresión obtenida frente a los valores observados.
4. **Validación con SKLearn**: comparación de los coeficientes (β0, β1) y del error (MSE) obtenidos manualmente contra los que entrega `LinearRegression` de `scikit-learn`.

## 🛠️ Tecnologías utilizadas

- Python 3
- [pandas](https://pandas.pydata.org/)
- [numpy](https://numpy.org/)
- [matplotlib](https://matplotlib.org/)
- [scikit-learn](https://scikit-learn.org/)

## 📦 Instalación

Clona el repositorio e instala las dependencias:

```bash
git clone <URL-del-repositorio>
cd <nombre-del-repositorio>
pip install pandas numpy matplotlib scikit-learn
```

## 🚀 Uso

Abre el notebook con Jupyter:

```bash
jupyter notebook Gradiente_Descendente.ipynb
```

y ejecuta las celdas en orden.

## 📈 Resultados esperados

El notebook imprime en pantalla:

- Los valores óptimos de β0 y β1 encontrados por el algoritmo de gradiente descendente.
- El error mínimo (MSE) alcanzado.
- La comparación de estos valores con los obtenidos por `scikit-learn`, mostrando que el algoritmo implementado manualmente converge a resultados muy similares a los de la librería.

## 📁 Estructura del repositorio

```
.
├── Gradiente_Descendente.ipynb   # Notebook principal
└── README.md                     # Este archivo
```

## ✍️ Autor

Agrega aquí tu nombre y, si quieres, un enlace a tu perfil de GitHub o LinkedIn.

## 📄 Licencia

Este proyecto se distribuye bajo la licencia que prefieras (por ejemplo, MIT). Agrega un archivo `LICENSE` si deseas especificarla formalmente.
