# Predicción de Fármacos con Árbol de Decisión

Este repositorio contiene un Jupyter Notebook donde se implementa un modelo de árbol de decisión para predecir el fármaco más adecuado según parámetros de salud de pacientes.

## Contenido

* `Drug_Prediction.ipynb`: Notebook con:

  1. **Carga y preprocesamiento** de datos (codificación de variables categóricas, verificación de valores faltantes).
  2. **Análisis exploratorio** (correlaciones, distribución de clases).
  3. **División** en conjuntos de entrenamiento y prueba.
  4. **Entrenamiento** del `DecisionTreeClassifier`.
  5. **Evaluación** del modelo (precisión, recall, F1, matriz de confusión).
  6. **Visualización** del árbol y extracción de reglas de decisión.

* `data/drug200.csv`: Conjunto de datos original.

## Requisitos

* Python 3.7+
* Jupyter Notebook
* Librerías:

  * pandas
  * numpy
  * scikit-learn
  * matplotlib

Puedes instalar las dependencias con:

```bash
pip install -r requirements.txt
```

## Uso

1. Clona el repositorio:

   ```bash
   ```

git clone https://github.com/Christ02/Arbol-de-decision.git

````
2. Abre el Notebook:
   ```bash
jupyter notebook Drug_Prediction.ipynb
````

3. Ejecuta cada celda en orden.

## Resultados

Al final obtendrás:

* Precisión del modelo (\~98.3%).
* Diagrama del árbol de decisión.
* Reglas de clasificación para cada medicamento.

## Licencia

© 2025 Christian02801
