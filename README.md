# Encrypted-Traffic-Classification-with-Deep-Learning

El presente trabajo de investigación aborda una forma de clasificar tráfico encriptado a través del uso de técnicas de inteligencia artificial, específicamente de aprendizaje profundo. Para ello, se propuso tres escenarios de experimentación en donde se probaron tres modelos: CNN, Random Forest, y SVM. Los datasets utilizados para el entrenamiento de los modelos anteriores corresponden al ISCXTor2016 y al UNSW-NB15, debido a los datos relevantes que contienen para la clasificación de tráfico, como direcciones IP, tipo de tráfico, si es un tráfico legítimo o proveniente de un ataque, entre otros. Se realizó una recolección de datos, preprocesamiento y extracción de característica antes del modelado y el entrenamiento. Finalmente, se evaluó los resultados de los modelos y se comparó su rendimiento. En términos generales, CNN obtuvo la mejor puntuación respecto a los demás modelos en el escenario 1 con una exactitud del 99,91\%, en el escenario 2 la exactitud es del 76,38\% superando también las métricas de exactitud obtenidas por el resto de modelos, en el escenario 3 los resultados varían considerablemente, siendo que los modelos RF y SVM obtienen puntajes relativamente mejores que CNN tanto en puntuación de exactitud y precisión. El presente trabajo concluye que CNN es el modelo más adecuado para clasificación de tráfico TOR/no TOR y clasificación multiclase (tipo de tráfico de red), pero tiene ligeras deficiencias para clasificar si el tráfico es legítimo/no legítimo. Es posible que esto se dé debido a una limitación del modelo CNN propuesto o a factores como el sobreajuste de los modelos tradicionales.
