# Repositorio TFM

Repositorio del TFM del **Máster en Ciencia de Datos de la UOC**.

El título del TFM es:

> **"Predicción del consumo eléctrico en dispositivos IoT alimentados con baterías aplicando algoritmos de Machine Learning"**.

Todos los ficheros con elementos de programación son cuadernos **Jupyter Notebook**.

## Estructura del repositorio

Los ficheros y carpetas que componen el presente repositorio son:

- **`1_data_download.ipynb`**: Cuaderno para la descarga de datos del repositorio.
- **`2_pre_analisis_V2.ipynb`**: Cuaderno con el preanálisis de los datos.
- **`3_pre_procesado_V5_Gen15min.ipynb`**: Cuaderno con el preprocesado de los datos. *15 min* indica el tiempo de redondeo de la fecha utilizado, que fue el intervalo seleccionado para hacer el resto del desarrollo del TFM.
- **`4_analisis_datos_V1_15min.ipynb`**: Cuaderno con el análisis de los datos.
- **`LICENSE`**: Licencia del repositorio.
- **`README.md`**: Archivo README con la descripción del repositorio.
- **`gru_model.tflite`**: Mejor modelo GRU en formato **TFLite**.
- **`lstm_model.tflite`**: Mejor modelo LSTM en formato **TFLite**.
- **`model_gru_lite.h`**: Mejor modelo GRU en formato **C/C++**.
- **`model_lstm_lite.h`**: Mejor modelo LSTM en formato **C/C++**.
- **`xgboost_best_model.pkl`**: Mejor modelo XGBoost en archivo de serialización Python (**Pickle file**).

## Carpetas

- **`📁 modelo_GRU/`**: Carpeta con el mejor modelo GRU en formato TensorFlow.
- **`📁 modelo_LSTM/`**: Carpeta con el mejor modelo LSTM en formato TensorFlow.
- **`📁 notebooks/`**: Carpeta con el resto de notebooks utilizados en el TFM.
  - **`📁 LR/`**: Cuadernos de algoritmos de Regresión Logística.
  - **`📁 PCA/`**: Cuadernos con Análisis de Componentes Principales (PCA).
  - **`📁 XGBoost/`**: Cuadernos con algoritmos de XGBoost.
  - **`📁 cuantizacion/`**: Ficheros de cuantización del mejor modelo GRU y LSTM.
  - **`📁 escenario_120/`**: Cuadernos con el entrenamiento de los modelos con secuencias de 120 horas para las combinaciones de datos A-F.
  - **`📁 escenario_24/`**: Cuadernos con el entrenamiento de los modelos con secuencias de 24 horas para las combinaciones de datos A-F.
  - **`📁 escenario_72/`**: Cuadernos con el entrenamiento de los modelos con secuencias de 72 horas para las combinaciones de datos A-F.
  - **`📁 preprocesado/`**: Cuadernos con el preprocesado de datos con el resto de redondeos probados de 1, 30 y 45 minutos.
