El paper tiene como objetivo comparar diversos sistemas recomendadores, utilizando metricas más apropiadas para las top-N recomendaciones que las tradicionales.

El paper propone dos métricas de error para seleccion top-N, que son recall y precision. Tambien dado que un porcentaje pequeño de items suelen ser los más populares proponen utilizar precision y recall pero solo sobre el long-tail de los objetos.
Estas propuestas me parecen muy importantes, dado que la forma en que se mide el error es sumamente importante y puede permitir optimizar de forma más apropiada los problemas. Una ventaja que tiene este metodo es que no importa por cuanto acierta o falla el sistema recomendador.
Siempre y cuando sus predicciones sean apropiadas. 

Por otra parte el paper hace un estudio comparativo de los metodos más populares y unos metodos mas simplistas y mide sus desempeños utilizando estas nuevas métricas. En general se tiene que el sistema de SVD puro era el que tenía mejores resultados tanto para el total como para el long-tail. Otro resultado interesante era que recomendar los items más populares le ganaba a varios metodos cuando se consideraba el total de los datos, pero esto no se mantenía para el long-tail.
Los buenos resultados de SVD puro se podían explicar por la falta de optimización para RMSE, lo que en cierta forma habla de como los otros metodos están sobreajustados a minimizar un error que no es el relevante. Por otra parte el buen desempeño de most popular bajo el total de los items, habla de como en general los sistemas recomendadores más sosfiticados solo valen la pena si se quiere dar recomendaciones fuertemente personalizadas, dado que most popular suele hacer un buen trabajo en hacer las recomendaciones triviales.

Un trabajo futuro que se podría hacer, es alterar los metodos más tradicionales para que optimizen bajo estos criterios y ver su nuevo comportamiento.
