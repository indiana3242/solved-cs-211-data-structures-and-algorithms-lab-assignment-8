Download Link: https://assignmentchef.com/product/solved-cs-211-data-structures-and-algorithms-lab-assignment-8
<br>
The objective of this assignment is to implement Dijkstra’s algorithm to find the shortest path distances from a source vertex to every vertex in the input graph, which is directed and has non-negative weights on edges.




<h1>Inputs</h1>




Your program should accept two command-line arguments: an input file and the label of a source vertex. A typical execution of your program will be ./a.out sample.graph 34.




The input file represents a directed graph with non-negative integer weights on edges. Every node in the graph is uniquely labelled with a non-negative integer. Every line in the input file is of the form ​<em>x y w</em>​, which represents a directed edge from node <em>x</em>​ to node <em>y</em>​ ​, where the weight of the edge is ​<em>w</em>​. No edge is repeated in the input file. The second command-line argument is the label of a source vertex, which is guaranteed to be a vertex in the given graph.




<h1>Task</h1>

<strong> </strong>

Implement Dijkstra’s algorithm to find the shortest path distances from the given source vertex to all vertices in the given graph. It is recommended that you use min-priority queue with the binary min-heap implementation, but a simpler implementation is also accepted with full credits.




<h1>Output</h1>




Your program should create a file named ‘dijkstra.txt’. Every line in the output file should corresponds to a shortest path distance from source to a vertex and should be of the form:




&lt;target&gt; &lt;shortest-path-distance-from-source&gt;




For example, if there is a line “21 10023” in the output file and 34 is the source vertex, then it implies that the shortest path distance from 34 to 21 is 10023. If there is no path from the source to a vertex, say 59, then the corresponding output line must be “59 -1”.




Shortest path distances of vertices from the source can be printed in the output file in any order.


