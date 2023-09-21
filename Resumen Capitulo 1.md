## De que trata el libro

Un problema bastante conocido entre estudiantes de programación es el de acomodar un ***n*** cantidad de números y determinar cual es el ***k***° mas grande. A este se le conoce como un problema de selección, y existen distintas formas de solucionarlo, algunas un poco obvias (no tan obvias personalmente) una forma puede ser 
- Acomodar la ***N*** cantidad de números en un arreglo, ordenar este de mayor a menor con un método de ordenamiento como seria *bubble* e imprimir el elemento en la posición ***k*** como la respuesta.  

Otra respuesta podrida ser
- Leer los primeros elementos ***k*** ,ponerlos en un arreglo y acomodarlos de mayor a menor, para después leer los elementos restantes uno por uno. Si el siguiente elemento leído es mas pequeño que el elemento ***k***, se ignora. Si no es colocado en su lugar correcto en el arreglo, moviendo un elemento fuera de su lugar. Cuando el algoritmo se acaba, el elemento en la posición ***k*** es la respuesta (Realmente no se como quedaría esto codificado, a lo mucho hemos hecho algo *similar* pero mas sencillo que la primera opción).  

Los dos algoritmos son relativamente simple de codear sin embargo una pregunta surge de estos: ¿Cual es mejor? Y, ¿Alguno de los dos es suficientemente bueno?
En una simulación usando 30 millones de elementos y dándole a ***k*** un valor de 15,000,000 nos damos cuenta de que ninguno de los dos termina en un tiempo razonable, tomando días de procesamiento para terminar.
Un concepto importante a tener en cuenta es que en muchos problemas, escribir un programa que sirva no es suficiente. Si el programa se tiene que correr con tamaños grandes de información, el tiempo para correrlo se vuelve un problema. En este libro vamos a ver como estimar el tiempo para correr de un programa que usa inputs grandes y mas importantemente, como comparar el tiempo de dos programas sin tener que programarlos. Se verán técnicas que mejoraran drásticamente la velocidad de programas y otras que determinaran cuellos de botella en estos.

## Revision de Matemáticas
#### Exponentes
Se nos muestran resumidamente las leyes de exponentes 

$$
X^A X^B = X^{A+B}
$$ 
$$
{X^A \over X^B} = X^{A - B}
$$
$$
(X^A)^B = X^{AB}
$$
$$
X^N + X^N = 2X^N ≠ X^{2N}
$$
$$
2^N + 2 ^ N = 2^{N+1}
$$
#### Logaritmo
En la ciencia de las computadoras, todos los logaritmos son a la base de 2 a menos de que se especifique de otra forma 
###### Definición:
$$
X^A = B$$  
solo si
$$log_x B = A$$
Un logaritmo es el exponente al cual se necesita elevar una cantidad positiva para obtener como resultado un cierto número. Un exponente en tanto es el numero que denota la potencia a la cual debe elevarse otra cifra
De este modo, el logaritmo de un numero es el exponente al cual tiene que elevarse la base para llegar a dicho numero 
#### Series
Aquí vemos un breve repaso sobre series 

## Referencias
https://definicion.de/logaritmo/