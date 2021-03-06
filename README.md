#Algoritmo de Dijkstra en C++
## Sobre el Programa 
El programa va solicitando en momento de ejecución
los datos necesarios para aplicar el algoritmo de Dijkstra.

Limitación Técnica:

Los Vértices deben ser númericos y comenzar desde cero.

100 // Maxima cantidad de vertices.

Codigo Fuente Original: http://www.widget-101.com/codigo/algoritmo-de-dijkstra/

## Algoritmo de Dijkstra
Como sucede con los algoritmos de Kruskal y Prim para encontrar el árbol de expansión mínima hay una simple pero ineficiente manera de encontrar el camino mas corto de A hacia Z. Que es, Usando el Algoritmo de Dijkstra el cual consiste en ir explorando todos los caminos más cortos que parten del vértice origen y que llevan a todos los demás vértices; cuando se obtiene el camino más corto desde el vértice origen, al resto de vértices que componen el grafo, el algoritmo se detiene.
El problema es que incluso para los grafos pequeños usando Kruskal o Prim podría tomar mucho tiempo.
Mientras que el algoritmo de Dijkstra podría hacer el trabajo en pocos segundos.

##Dijkstra en Funcionamiento

![Dijkstra](http://upload.wikimedia.org/wikipedia/commons/thumb/5/57/Dijkstra_Animation.gif/270px-Dijkstra_Animation.gif)

##Dijkstra comparado con Prim y Kruskal
El proceso que subyace en el algoritmo de Dijkstra es similar al proceso utilizado en el algoritmo de Prim. El Propósito de Prim es encontrar un árbol de expansión mínimo que conecta todos los vértices del grafo; Dijkstra se ocupa sólo de dos vértices. Prim parte de un vertice y va añadiendo vertices cuyo coste sea minimo, así llegando a obtener todos los vértices. Kruskal el fin es el mismo que Prim, solo que parte con todos los vértices y ordena el coste de las aristas y va eligiendo las aristas de menor coste con dos premisas, no repetir vértices y sin hacer ningun bucle...

##Bibliografía: 

[Matemáticas Discretas con Aplicaciones, 4a. Ed. Susana S. Epp](http://www.cengage.com.mx/ls/matematicas-discretas-con-aplicaciones-4a-ed/)

[Algoritmo de Dijkstra - Wikipedia](http://es.wikipedia.org/wiki/Algoritmo_de_Dijkstra)
