# Clusters_FC25
Proyecto de aprendizaje no supervisado que busca clasificar los jugadores del popular juego FC25 (Fifa) en 4 clusters, usando el algoritmo k-means con 4 variantes del mismo, aplicando 3 tipos de métricas diferentes para medir la similitud (Euclideana, Mahalanobis y L1). Se hace la visualización usando PCA.


Descripción del conjunto de datos (2 renglones)
- Se hace un EDA
Descripción del workflow:
Con cuantas variables se trabaja (cuantas se escogen), la escala.
- Se imputan los datos faltantes, se codifica la variable pie preferido a una variabale binaria.
- Implementación del k-means usando librerías
- Implementación manual del algoritmo usando 3 tipos de distancias diferentes (eu, mh, l1)
- Descripción del algoritmo (como el video). (ejercicio de clasificación, no supervisado, no sirve para estructuras convexas, es sensible a la inicialización, los datos deben estar escalados)
- Se usa PCA (reducción de dimensionalidad), para visualizar la clusterización en 2D y 3D. Se escogen 3 componenentes principales que conservan el 80% de la varianza de los datos, los centroides se transforman en dicho espacio para poderlos visualizar.