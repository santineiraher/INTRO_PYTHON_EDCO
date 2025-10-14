# Introducción al Análisis de Datos en Python

# 🚀 Intro_Python_EdCo

Este repositorio contiene notebooks, datos y recursos usados en las clases del curso de introducción a Python: manipulación de datos, visualización y comparación entre librerías (por ejemplo, pandas vs polars). 🐍📊

## 📖 Contenido del repositorio
- **Clase 1 — Introducción al análisis de datos en Python** 🐣
	- Contenido: sintaxis básica de Python, tipos de datos (int, float, bool, string), estructuras básicas (listas, tuplas, diccionarios), uso de Jupyter, y ejemplos simples (`print`, variables). Incluye ejemplos comparativos (p. ej. "Hola, Mundo" en Java vs Python) y ejercicios introductorios.

- **Clase 2 — Estructuras de datos y control de flujo** 🔁
	- Contenido: listas y sus métodos (`append`, `insert`, `pop`, `reverse`, `sort`), slicing, y ejemplos de uso práctico; además repaso de control de flujo (if, for, while) y ejercicios para manipular colecciones.

- **Clase 3 — Pandas (introducción)** 🧾
	- Contenido: qué es Pandas, cómo construir DataFrames desde diccionarios/listas, lectura de archivos, atributos útiles (`.head()`, `.info()`, `.shape`, `.dtypes`) y operaciones básicas de selección y limpieza para poner los datos listos para analizar.

- **Clase 4 — Continuación Pandas (manipulación avanzada)** 🔧
	- Contenido: trabajo con Series, edición de valores (`loc`, asignaciones condicionadas), creación de nuevas columnas (p. ej. `edad_dias`), y técnicas para transformar y preparar tablas para análisis posteriores.

- **cont_clase_4 — Uniones y merges** 🔗
	- Contenido: explicación práctica de `pd.merge()` y tipos de joins (`left`, `right`, `inner`, `outer`), validaciones y ejemplos visuales (one-to-one, one-to-many) con casos de uso y código demostrativo.

- **Clase 5 — Visualización** 📊
	- Contenido: introducción a visualización con `matplotlib` (y la integración desde `pandas.plot()`), ejemplos rápidos (líneas, barras, scatter), y uso de la base `cont_clase_4/data/info_accidentes.csv` para crear gráficos y series temporales.

- **Clase 6 — Más visualizaciones y seaborn** 🌈
	- Contenido: repaso de `seaborn` (estilos y gráficos avanzados), mapas de calor, jointplots, trabajo con un dataset de propiedades (`co_properties.csv.zip`) y ejercicios de filtrado/agrupamiento para producir visualizaciones más ricas.

- **Clase 7 — Introducción a Machine Learning** 🤖
	- Contenido: conceptos de ML (supervisado vs no supervisado), ejemplos de aplicaciones, problemas comunes (overfitting, split train/test) y una introducción a modelos simples como regresión lineal.

- **Aequitas & COMPAS (clase 7, notebook `Aequitas_COMPAS.ipynb`) — Auditoría de sesgos** ⚖️
	- Contenido: uso de la librería Aequitas para evaluar equidad y sesgo en modelos (ejemplo con dataset COMPAS de ProPublica). Incluye instalación de `aequitas`, carga del dataset, métricas de equidad por grupos (raza, sexo) y visualizaciones de distribución de scores.

- **`polars_vs_pandas_intro.ipynb` — Polars vs Pandas (comparativa)** ⚡
	- Contenido: instalación rápida de Polars y Pandas, ejemplos de filtrado y `groupby`, comparación de tiempos (`%time`), y explicación de la ventaja de pipelines lazy en Polars frente al eager evaluation de Pandas.


> Nota: si quieres ver todos los archivos, abre el explorador de tu editor o listalos con `ls`/`dir` en tu terminal. 🧭

## ▶️ Cómo ejecutar los notebooks
Puedes abrir y ejecutar los notebooks con Jupyter Notebook, JupyterLab o directamente desde VS Code (extensión de Jupyter).

Pasos rápidos (Windows PowerShell):

```powershell
# Crear y activar un entorno virtual (opcional pero recomendado)
python -m venv .venv; .\\.venv\\Scripts\\Activate.ps1

# Instalar Jupyter y librerías comunes (ajusta según lo que uses en cada notebook)
pip install --upgrade pip; pip install jupyter pandas numpy matplotlib plotly polars

# Iniciar Jupyter Notebook
jupyter notebook
```

Si prefieres VS Code: abre la carpeta del proyecto en VS Code y haz click en cualquier `.ipynb` para abrir el notebook con la extensión de Jupyter.


## 📬 Contacto
Si necesitas ayuda o quieres comentar el material, abre un issue o contacta al propietario del repositorio.

## 📜 Licencia
El repositorio no especifica una licencia; si vas a reutilizar código para algo público, considera añadir una licencia (por ejemplo MIT) o preguntar al autor.

---

¡Disfruta aprendiendo Python y analizando datos! 🎉📈
