# Análisis de Iris virginica 🌺

Este repositorio contiene un análisis detallado de la especie **Iris virginica**, una de las tres especies en el famoso conjunto de datos Iris. Este proyecto utiliza herramientas estadísticas y de aprendizaje automático para explorar y clasificar las flores de esta especie en función de sus características.

---

## ⚡ Forma breve

El proyecto consiste en entrenar un modelo de clasificación utilizando el conjunto de datos de *train* para predecir la especie de una flor en el conjunto de *test*. La clasificación se realiza en función de las siguientes características:  
- `sepal length`  
- `sepal width`  
- `petal length`  
- `petal width`  

---

## 📋 Resumen

La **Iris virginica** es una de las tres especies en el conjunto de datos Iris. Este repositorio se centra específicamente en:  
- Analizar las características biológicas de Iris virginica.  
- Comparar sus atributos con los de otras especies (Iris setosa y Iris versicolor).  
- Entrenar y evaluar modelos de clasificación para identificar la especie en función de las medidas disponibles.  

---

## 📂 Estructura del repositorio

- `data/`: Conjunto de datos Iris (`iris.csv`).  
- `notebooks/`: Cuadernos Jupyter con los pasos detallados del análisis.  
- `images/`: Visualizaciones y gráficos generados durante el análisis.  
- `scripts/`: Scripts en Python para preprocesamiento, visualización y modelado.  
- `README.md`: Este documento explicativo.  

---

## 🔍 Detalles del análisis

1. **Análisis Exploratorio de Datos (EDA):**  
   - Distribución de las características de Iris virginica.  
   - Análisis de correlación entre dimensiones de pétalos y sépalos.  

2. **Visualización de Datos:**  
   - Gráficos de dispersión para relaciones entre características.  
   - Diagramas de caja para comparar rangos entre especies.  

3. **Modelos de Aprendizaje Automático:**  
   - Modelos de clasificación para identificar Iris virginica usando las dimensiones mencionadas.  
   - Evaluación de rendimiento en modelos como Regresión Logística, Árboles de Decisión y SVM.  

---

## 📊 Resultados clave

- Iris virginica generalmente presenta los pétalos y sépalos más largos en comparación con las otras especies.  
- La longitud del pétalo (`petal length`) es la característica más distintiva para la clasificación.  

---

## 🚀 Cómo empezar

### Requisitos previos
- Python 3.8 o superior.  
- Bibliotecas: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`.  

### Instalación
1. Clona este repositorio:  
   ```bash
   git clone https://github.com/crisrey211/kopuru-iris-aprendizaje-superviasdo.git
### 🛠️ Configuración de un Entorno Virtual

It's recommended to use a virtual environment to manage dependencies for this project. Follow the steps below:

2. Create a Virtual Environment
    Run the following command to create a virtual environment named `.venv`:
    ```bash
    py -m venv .venv
### Activar el Entorno Virtual

3. En Windows:
    ```bash
    .\.venv\Scripts\activate
4. En Linux/MacOS:
    ```bash
    source .venv/bin/activate
### Instalar Dependencias

5. On Linux/MacOS:
    ```bash
    pip install -r requirements.txt