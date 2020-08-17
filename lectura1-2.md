La segunda lectura trata sobre el uso de singular value decomposition para resolver el problema de Netflix. El blog se centra en explicar la matematica detras del metodo utilizado. Mostrando al final los resultados obtenidos.

El blog explica relativamente bien los metodos utilizados y el razonamiento de fondo. Y esta bastante enfocado en mostrar el pseudocodigo, lo que hace más facil de entender desde un punto de vista de implemetnación, pero a veces complica la comprensión más teorica. Pero me imagino que ese era la idea original del blog.

El metodo utilizado es bastante creativo en su solución para el problema de las matrices __sparse__, dado que el metodo ignora las peliculas que no fueron rankeadas por los usuarios. También me parecío ingenioso el uso de un ajuste bayesiano para cuando hay pocos datos. Pero me parecío extraño la suposición de la distribución normal de ratings, y es posible que utlizando una distribución mejor estudiada (esto se puede dado que se conocen las distriubuciones) se obtengan mejores resultados.

el ultimo concepto interesante que muestra el blog es el uso de una función no lineal para calcular los valores. Esto ayudaria a crear una mejor aproximación de la recomendación, pero podría llegar a sobreajustar los datos si no se hace con cuidado.
