# 🐍 Introducción al Análisis de Datos en Python

> **Curso completo de Python para análisis de datos** - De fundamentos a Machine Learning
> 
> **Profesor:** Santiago Neira Hernández

---

## 📋 Tabla de Contenidos

- [Descripción General](#-descripción-general)
- [Estructura del Curso](#-estructura-del-curso)
- [Clase 1: Introducción a Python](#-clase-1-introducción-a-python)
- [Clase 2: Estructuras de Datos y Control de Flujo](#-clase-2-estructuras-de-datos-y-control-de-flujo)
- [Clase 3: Pandas - Manipulación de Datos](#-clase-3-pandas---manipulación-de-datos)
- [Clase 4: Pandas Avanzado](#-clase-4-pandas-avanzado)
- [Clase 5: Visualización de Datos](#-clase-5-visualización-de-datos)
- [Clase 6: Visualizaciones Avanzadas](#-clase-6-visualizaciones-avanzadas)
- [Clase 7: Machine Learning](#-clase-7-machine-learning)
- [Material Extra](#-material-extra)
- [Requisitos](#-requisitos)
- [Cómo Usar Este Repositorio](#-cómo-usar-este-repositorio)

---

## 🎯 Descripción General

Este repositorio contiene el material completo de un curso introductorio de análisis de datos en Python. El curso está diseñado para llevar a los estudiantes desde los fundamentos de Python hasta la implementación de modelos de Machine Learning, pasando por manipulación de datos con Pandas y visualización con Matplotlib y Seaborn.

### ¿Por qué Python?

Python se destaca por su simplicidad. Compara el clásico "Hola, Mundo":

**Java (5 líneas):**
```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("¡Hola, Mundo!");
    }
}
```

**Python (1 línea):**
```python
print("¡Hola, Mundo!")
```

---

## 📚 Estructura del Curso

El curso está organizado en 7 clases principales más material complementario:

```
INTRO_PYTHON_EDCO/
├── 📁 clase_1/          # Introducción a Python
├── 📁 clase_2/          # Estructuras de datos y control de flujo
├── 📁 clase_3/          # Pandas básico
├── 📁 clase_4/          # Pandas avanzado (merge, groupby)
├── 📁 clase_5/          # Visualización con Matplotlib
├── 📁 clase_6/          # Visualizaciones avanzadas con Seaborn
├── 📁 clase_7/          # Machine Learning
└── 📁 extras/           # Material complementario y ejercicios
```

---

## 📘 Clase 1: Introducción a Python

**📂 Carpeta:** [`clase_1/`](clase_1/)

### Contenido

- **Jupyter Notebooks**: Introducción y uso
- **Variables en Python**: Declaración y tipos
- **Tipos de datos básicos**: 
  - Enteros (`int`)
  - Flotantes (`float`)
  - Lógicos (`bool`)
  - Caracteres (`str`)
  - Valores faltantes (`NaN`, `NA`)
- **Estructuras de datos básicas**:
  - Listas
  - Cadenas
  - Tuplas
  - Diccionarios
- **NumPy y Pandas**: Introducción básica

### Archivos

- 📓 `Modulo1.ipynb` - Notebook principal de la clase
- 📄 `Intro.pdf` - Presentación introductoria del curso

### Objetivos de Aprendizaje

✅ Entender la sintaxis básica de Python  
✅ Trabajar con Jupyter Notebooks  
✅ Manipular tipos de datos fundamentales  
✅ Crear y manipular estructuras de datos básicas

---

## 📗 Clase 2: Estructuras de Datos y Control de Flujo

**📂 Carpeta:** [`clase_2/`](clase_2/)

### Contenido

- **Listas en Python**:
  - Creación y acceso por índice
  - Slicing (rebanado)
  - Métodos: `append()`, `insert()`, `pop()`, `reverse()`, `sort()`
- **Control de flujo**:
  - Condicionales (`if`, `elif`, `else`)
  - Ciclos (`for`, `while`)
- **Comprensión de listas**
- **Funciones**: Definición y uso

### Archivos

- 📓 `Modulo2.ipynb` - Notebook base
- 📓 `Modulo2_After.ipynb` - Notebook con ejercicios resueltos

### Objetivos de Aprendizaje

✅ Dominar las operaciones con listas  
✅ Implementar estructuras de control de flujo  
✅ Crear funciones personalizadas  
✅ Aplicar comprensión de listas para código eficiente

---

## 📙 Clase 3: Pandas - Manipulación de Datos

**📂 Carpeta:** [`clase_3/`](clase_3/)

### Contenido

- **Introducción a Pandas**:
  - ¿Qué es Pandas?
  - DataFrames y Series
- **Creación de DataFrames**:
  - Desde diccionarios
  - Desde archivos (CSV, Excel)
- **Operaciones básicas**:
  - Selección de datos
  - Filtrado
  - Indexación (`.loc[]`, `.iloc[]`)
- **Limpieza de datos**:
  - Manejo de valores faltantes
  - Normalización

### Archivos

- 📓 `Modulo3.ipynb` - Notebook base
- 📓 `Modulo3_After.ipynb` - Notebook con ejercicios resueltos
- 📁 `data/` - Datos de ejemplo (consumo masivo Colombia)
- 📁 `img/` - Imágenes de apoyo
- 🔗 [`video_link.md`](clase_3/video_link.md) - Recurso de video complementario

### Objetivos de Aprendizaje

✅ Crear y manipular DataFrames  
✅ Importar datos desde diferentes formatos  
✅ Realizar operaciones de limpieza de datos  
✅ Aplicar indexación y filtrado eficiente

---

## 📕 Clase 4: Pandas Avanzado

**📂 Carpeta:** [`clase_4/`](clase_4/)

### Contenido

- **Unión de bases de datos (`merge`)**:
  - Left merge
  - Right merge
  - Inner merge
  - Outer merge
  - Relaciones one-to-one, one-to-many, many-to-many
- **Agrupación de datos (`groupby`)**:
  - Agregaciones
  - Transformaciones
  - Filtrado por grupos
- **Concatenación de DataFrames**
- **Operaciones avanzadas**

### Archivos

- 📓 `Modulo_4_Pandas_avanzado.ipynb` - Notebook principal
- 📓 `Modulo_4_After.ipynb` - Notebook con ejercicios resueltos
- 📁 `data/` - Datasets de ejemplo (accidentes, consumo masivo)
- 📁 `img/` - Diagramas explicativos de merges y groupby

### Objetivos de Aprendizaje

✅ Unir múltiples DataFrames con diferentes estrategias  
✅ Realizar agregaciones complejas con groupby  
✅ Entender las relaciones entre tablas  
✅ Aplicar transformaciones por grupos

---

## 📊 Clase 5: Visualización de Datos

**📂 Carpeta:** [`clase_5/`](clase_5/)

### Contenido

- **Matplotlib**:
  - Gráficos básicos desde Pandas
  - Método `.plot()`
  - Personalización de gráficos
- **Tipos de gráficos**:
  - Gráficos de dispersión (scatter)
  - Gráficos de líneas
  - Gráficos de barras
  - Histogramas
- **Personalización**:
  - Colores
  - Etiquetas
  - Leyendas
  - Títulos

### Archivos

- 📓 `Modulo5.ipynb` - Notebook base
- 📓 `Modulo5_After.ipynb` - Notebook con ejercicios resueltos
- 📁 `data/` - Datos de accidentes para visualización
- 📁 `img/` - Paletas de colores y ejemplos

### Objetivos de Aprendizaje

✅ Crear visualizaciones básicas con Matplotlib  
✅ Personalizar gráficos para comunicar información  
✅ Elegir el tipo de gráfico apropiado para cada análisis  
✅ Integrar visualizaciones en el flujo de análisis

---

## 📈 Clase 6: Visualizaciones Avanzadas

**📂 Carpeta:** [`clase_6/`](clase_6/)

### Contenido

- **Seaborn**:
  - Introducción y configuración de temas
  - Integración con Pandas
- **Visualizaciones avanzadas**:
  - Joint plots (dispersión + distribución)
  - Heatmaps (mapas de calor)
  - Gráficos de distribución
- **Análisis de datos reales**:
  - Dataset de propiedades en Colombia
  - Análisis geoespacial básico
  - Análisis de precios por sector

### Archivos

- 📓 `Modulo6.ipynb` - Notebook base
- 📓 `Modulo6_After.ipynb` - Notebook con ejercicios resueltos
- 🔗 [`datos.md`](clase_6/datos.md) - **Enlace a datos en Dropbox** (debido al tamaño)

> ⚠️ **Nota:** Los datos de esta clase están alojados en Dropbox debido a su tamaño. Consulta el archivo `datos.md` para el enlace de descarga.

### Objetivos de Aprendizaje

✅ Crear visualizaciones estadísticas avanzadas con Seaborn  
✅ Analizar datos de propiedades inmobiliarias  
✅ Generar mapas de calor para análisis multivariado  
✅ Combinar múltiples tipos de visualizaciones

---

## 🤖 Clase 7: Machine Learning

**📂 Carpeta:** [`clase_7/`](clase_7/)

### Contenido

- **Introducción al Machine Learning**:
  - ¿Qué es ML? (perspectiva Data Science y AI)
  - Tipos de aprendizaje
- **Aprendizaje Supervisado**:
  - Regresión lineal
  - Clasificación
  - Evaluación de modelos
- **Aprendizaje No Supervisado**:
  - Clustering
  - Segmentación
- **Problemas comunes**:
  - Overfitting
  - División de datos (train/test)
- **Aplicaciones prácticas**:
  - Pronóstico de demanda
  - Scoring crediticio
  - Detección de fraude
  - Segmentación de clientes

### Archivos

- 📓 `Modulo7_after.ipynb` - Notebook con ejercicios resueltos
- 🔗 [`datos.md`](clase_7/datos.md) - **Enlace a datos y notebook original en Dropbox**

> ⚠️ **Nota:** Los datos y el notebook original de esta clase están en Dropbox. Consulta el archivo `datos.md` para el enlace de descarga.

### Objetivos de Aprendizaje

✅ Comprender los fundamentos del Machine Learning  
✅ Diferenciar entre aprendizaje supervisado y no supervisado  
✅ Implementar modelos de regresión lineal  
✅ Evaluar y validar modelos predictivos  
✅ Aplicar ML a problemas reales de negocio

---

## 🎁 Material Extra

**📂 Carpeta:** [`extras/Bolsas_ejercicios/`](extras/Bolsas_ejercicios/)

### Contenido

#### 📓 Ejercicios 1 - Fundamentos
Bolsa de ejercicios iniciales que cubre:
- Objetos básicos de Python (int, float, str, bool)
- Estructuras de datos nativas (list, dict, tuple, set)
- Definición de funciones con parámetros y retornos
- Buenas prácticas y docstrings

**Incluye:**
- ✅ Ejercicios guiados con soluciones
- ❌ Ejercicios sin solución para práctica independiente

#### 🔗 Ejercicios 2
Bolsa adicional de ejercicios disponible en Dropbox.

📄 Consulta [`Ejercicios_2.md`](extras/Bolsas_ejercicios/Ejercicios_2.md) para el enlace de descarga.

#### ⚡ Polars vs Pandas
Introducción rápida a Polars, una alternativa moderna y rápida a Pandas.

**Contenido:**
- Instalación y configuración
- Comparación de sintaxis con Pandas
- Filtrado y transformaciones
- Ventajas de rendimiento

📓 [`polars_vs_pandas_intro.ipynb`](extras/Bolsas_ejercicios/polars_vs_pandas_intro.ipynb)

### Recursos Adicionales

- 🎥 [`video_link.md`](extras/Bolsas_ejercicios/video_link.md) - Video tutorial complementario

---

## 💻 Requisitos

### Software Necesario

- **Python 3.8+** (recomendado 3.11)
- **Jupyter Notebook** o **JupyterLab**
- **Anaconda** (opcional pero recomendado)

### Librerías Principales

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

#### Detalle de librerías:

| Librería | Versión Mínima | Propósito |
|----------|----------------|-----------|
| `pandas` | 1.3.0+ | Manipulación de datos |
| `numpy` | 1.21.0+ | Operaciones numéricas |
| `matplotlib` | 3.4.0+ | Visualización básica |
| `seaborn` | 0.11.0+ | Visualización estadística |
| `scikit-learn` | 1.0.0+ | Machine Learning (Clase 7) |
| `polars` | - | Alternativa a Pandas (opcional) |

### Instalación Recomendada con Anaconda

```bash
conda create -n intro_python python=3.11
conda activate intro_python
conda install pandas numpy matplotlib seaborn jupyter scikit-learn
```

---

## 🚀 Cómo Usar Este Repositorio

### 1️⃣ Clonar el Repositorio

```bash
git clone https://github.com/tu-usuario/INTRO_PYTHON_EDCO.git
cd INTRO_PYTHON_EDCO
```

### 2️⃣ Instalar Dependencias

```bash
pip install -r requirements.txt
```

### 3️⃣ Iniciar Jupyter Notebook

```bash
jupyter notebook
```

### 4️⃣ Navegar por las Clases

Sigue el orden secuencial de las clases (1-7) para un aprendizaje progresivo:

1. Comienza con `clase_1/Modulo1.ipynb`
2. Avanza a `clase_2/Modulo2.ipynb`
3. Continúa secuencialmente hasta `clase_7/`

### 5️⃣ Descargar Datos Externos

Algunas clases requieren datos externos alojados en Dropbox:

- **Clase 6:** Ver [`clase_6/datos.md`](clase_6/datos.md)
- **Clase 7:** Ver [`clase_7/datos.md`](clase_7/datos.md)
- **Ejercicios Extra:** Ver [`extras/Bolsas_ejercicios/Ejercicios_2.md`](extras/Bolsas_ejercicios/Ejercicios_2.md)

---

## 📝 Estructura de los Notebooks

Cada clase típicamente incluye:

- **📓 `ModuloX.ipynb`**: Notebook base con teoría y ejemplos
- **📓 `ModuloX_After.ipynb`**: Notebook con ejercicios resueltos
- **📁 `data/`**: Datasets para práctica
- **📁 `img/`**: Imágenes y diagramas de apoyo

### Convenciones de Código

- **Variables:** `snake_case` (ej: `mi_variable`)
- **Funciones:** `snake_case` (ej: `calcular_promedio()`)

---

## 🎓 Metodología de Aprendizaje

### Para cada clase:

1. **📖 Lee la teoría** en el notebook base
2. **💻 Ejecuta los ejemplos** celda por celda
3. **✏️ Practica** con los ejercicios propuestos
4. **🔍 Compara** tus soluciones con el notebook `_After`
5. **🚀 Experimenta** modificando el código

### Reglas de Oro

- ✅ **Comenta tu código** cuando sea necesario
- ✅ **Nombra variables con claridad**
- ✅ **Evita copiar/pegar sin entender**
- ✅ **Experimenta y prueba diferentes enfoques**
- ✅ **Consulta la documentación oficial**

---

## 📚 Recursos Adicionales

### Documentación Oficial

- 🐍 [Python Documentation](https://docs.python.org/3/)
- 🐼 [Pandas Documentation](https://pandas.pydata.org/docs/)
- 🔢 [NumPy Documentation](https://numpy.org/doc/)
- 📊 [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- 🎨 [Seaborn Documentation](https://seaborn.pydata.org/)
- 🤖 [Scikit-learn Documentation](https://scikit-learn.org/stable/)

### Tutoriales Recomendados

- [Jupyter Notebook Official Docs](https://jupyter-notebook.readthedocs.io/en/stable/)
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [Python for Data Analysis (Book)](https://wesmckinney.com/book/)

---

## 👨‍🏫 Sobre el Instructor

**Santiago Neira Hernández**
Senior Data Scientist en Beetmann. Profesor de Cátedra en Universidad de los Andes.
Instructor especializado en análisis de datos y Python, con experiencia en enseñanza de ciencia de datos y machine learning.

---

## 📄 Licencia

Este material es de uso educativo. Por favor, consulta con el instructor para cualquier uso fuera del contexto académico.

---

## ⭐ Agradecimientos

Gracias a todos los estudiantes que han participado en este curso y han contribuido a mejorar el material con sus preguntas y feedback.

---

<div align="center">

**¡Feliz aprendizaje! 🎉**

*"El análisis de datos es el arte de convertir datos en conocimiento"*

</div>

