# Proyecto de Detección de Fraude en Transacciones con Aprendizaje Automático

Este proyecto tiene como objetivo la detección de transacciones fraudulentas utilizando varios modelos de aprendizaje automático. A continuación, se detalla el flujo de trabajo para ejecutar los análisis y entrenar los modelos.

## Autor:
Marco Antonio Jurado

## Instrucciones de Ejecución

Sigue los pasos a continuación para ejecutar los notebooks en el orden indicado:

### 1. Análisis Exploratorio

Abre y ejecuta el notebook `analisisExploratorio.ipynb` para realizar un análisis exploratorio de los datos de transacciones. Este paso incluye la carga de datos, visualización de distribuciones y patrones, y detección de valores atípicos.

### 2. Ingeniería de Variables

A continuación, ejecuta el notebook `ingenieriaVariables.ipynb` para realizar la ingeniería de características. Este paso implica crear nuevas columnas basadas en los datos existentes, así como transformar y normalizar los datos.

### 3. Balanceo del Dataset

Ejecuta el notebook `balanceo_dataset.ipynb` para aplicar técnicas de balanceo, como SMOTE, y ajustar la proporción de la variable objetivo (fraude/no fraude).

### 4. Análisis Mensual (Opcional)

Este paso es opcional. Si deseas realizar un análisis mensual de las transacciones, ejecuta el notebook `analisisMensual.ipynb`. Este notebook generará gráficos mensuales de las transacciones fraudulentas y no fraudulentas.

### 5. Implementación de ANN

Ejecuta el notebook `implementacionANN.ipynb` para entrenar y evaluar un modelo de Redes Neuronales Artificiales (ANN) utilizando el enfoque incremental y secuencial.

### 6. Implementación de LightGBM

Finalmente, ejecuta el notebook `implementacionLGBM.ipynb` para entrenar y evaluar un modelo LightGBM utilizando el enfoque incremental y secuencial.

## Notas

- Asegúrate de ejecutar los notebooks en el orden especificado para garantizar que los datos y modelos se procesen correctamente.
- Los archivos generados, como gráficos y métricas, se guardarán en las carpetas correspondientes dentro del directorio del proyecto.

¡Gracias por usar este proyecto de detección de fraude en transacciones!