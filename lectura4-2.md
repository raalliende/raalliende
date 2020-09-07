El paper trata sobre un NMF, un metodo para hacer clustering principalmente orientado a documentos de texto. El paper parte describiendo el problema de clustering y su relevancia, luego da una explicacion de sistemas utilizados actualmente. Despues se dedica a explicar el metodo propuesto, explicando la idea general, la representacion de documentos y como hacer la factorizacion. EL paper termina evaluando resultados practicos y con un resumen.

El metodo propuesto tiene como ventaja que entrega siempre una factorizacion positiva. Lo cual ayuda a crear una representación más coherente de los documentos. Otra ventaja que tiene el metodo, es que la implementación propuesto corre en tiempo lineal al numero de datos, lo que ayuda a que pueda correr en datasets más grandes.
Por ultimo, el metodo parece ser competetivo cuando se aplica la version con pesos segun los resultados entregados por el paper.

Ahora si bien el metodo es bastante util para crear cluster de documentos, este metodo por si solo no basta para crear recomendaciones a un usuario, y debe ser complementado con algun otro metodo.
