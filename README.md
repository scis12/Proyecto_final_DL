# Proyecto_final_DL
Proyecto final para la diplomatura en Deep Learning del ITBA

El objetivo del proyecto fue entender la bioactividad de una molecúla (molecule_chembl_id) sobre una encima (Acetylcholinesterase), medida a través del indicador IC50 (standard_value).

Para lograrlo, se trabajó con los smiles de la formula química de las moléculas con técnicas de NLP: Principalmente la utilización de redes neuronales LSTM y de arquitecturas de Text CNN. 

En las notebook 1 y 2, se trabaja en la extracción y exploración básica de datos.

En la notebook 3, se experimenta con varias arquitecturas de redes LSTM, llegando a un R2 de 0.61.

En la notebook 4, se experimenta con varias posibilidades de arquitecturas de text CNN, llegando a un R2 de 0.66.

En la notebook 5, se hace una exploratoria de los embeddings entrenados en el modelo de text CNN mediante una representación en dos dimensiones obtenida a través de TSNE para interpretar espacialmente la ubicación de los embeddings.

En la notebook 6, se prueba una arquitectura prearmada para resolver este problema para entender cómo performa.

