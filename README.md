# Predicción de Fármacos con Árbol de Decisión

Este repositorio contiene un Jupyter Notebook en el que se implementa un modelo de árbol de decisión para predecir el fármaco más adecuado según parámetros de salud de pacientes.

## Contenido

* **Drug\_Prediction.ipynb**: Notebook con:

  1. **Carga y preprocesamiento** de datos (codificación de variables categóricas, verificación de valores faltantes).
  2. **Análisis exploratorio** (correlaciones, distribución de clases).
  3. **División** en conjuntos de entrenamiento y prueba.
  4. **Entrenamiento** del `DecisionTreeClassifier`.
  5. **Evaluación** del modelo (precisión, recall, F1, matriz de confusión).
  6. **Visualización** del árbol y extracción de reglas de decisión.
* **data/drug200.csv**: Conjunto de datos original.
* **requirements.txt**: Dependencias del proyecto.

## Requisitos

* Python 3.7+
* Jupyter Lab o Jupyter Notebook
* Librerías:

  * pandas
  * numpy
  * scikit-learn
  * matplotlib

## Instalación

1. Clona el repositorio:

   ```bash
   git clone https://github.com/Christ02/Arbol-de-decision.git
   cd Arbol-de-decision
   ```

2. Crea y activa un entorno virtual (recomendado):

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate   # Windows
   ```

## Uso

Puedes levantar el proyecto con Jupyter Lab o Notebook:

* **Jupyter Lab**:

  ```bash
  jupyter lab
  ```

* **Jupyter Notebook**:

  ```bash
  jupyter notebook
  ```

Luego, abre el archivo `ArbolDecision.ipynb` y ejecuta las celdas en orden.

## Resultados

Al completar el notebook, obtendrás:

* Precisión del modelo (\~98.3%).
* Diagrama del árbol de decisión.
* Reglas de clasificación para cada medicamento.

## Licencia

MIT © 2025 Christian02801
