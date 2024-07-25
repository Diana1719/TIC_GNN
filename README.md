# TIC_GNN

Este estudio se enfoca en el desarrollo y comparación de modelos híbridos de redes neuronales de grafos (GNN) combinados con redes neuronales recurrentes (RNN) para la predicción del tráfico urbano, evaluando su capacidad para capturar dependencias espaciales y temporales. La capacidad de predecir el tráfico es esencial para que los gobiernos y empresas privadas implementen medidas como la planificación de rutas, la expansión del transporte público y la mejora de los servicios de navegación.

Utilizando la base de datos METR-LA, se preprocesaron los datos para normalizar las características del tráfico y estructurar la red de carreteras urbanas como un grafo. En este grafo, los nodos representan los sensores de tráfico, que pueden estar ubicados en intersecciones entre dos calles, y las aristas representan las carreteras que conectan las ubicaciones de estos sensores. Las características del tráfico, como la velocidad, el flujo y la ocupación, se representaron como atributos de los nodos. En este caso, se utilizó la velocidad como la característica principal para predecir el tráfico.


Se implementaron varios modelos híbridos de GNN, incluyendo GCN-GRU, GCN-LSTM, GAT-GRU y GAT-LSTM, que consideran tanto las dimensiones espaciales como temporales. Estos modelos se entrenaron y validaron utilizando técnicas de validación cruzada para asegurar la precisión y evitar el sobreajuste. Los resultados se evaluaron mediante métricas estándar como el error cuadrático medio (MSE), el error absoluto medio (MAE) y el error cuadrático medio de la raíz (RMSE).
