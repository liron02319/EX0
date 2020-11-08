# EX0

Ex0
The task deals with the development of a data structure of an unweighted and unintentional graph

Example of unintentional graph:
 
 [URL=http://www.siz.co.il/][IMG]http://up419.siz.co.il/up1/2yzqwyd2vk4y.png[/IMG][/URL]
 

in this task we have three classes: NodeData, GraphDS, GraphAlgo
and three interfaces  : Node_data, graph, graph_algorithms
Each class implements an interface
NodeData implement Node_data.*
* Graph_DS implement graph.
 *Graph_Algo  implement , graph_algorithms.

The class NodeData  Represents a vertex.
Every vertex is a unique key, and every vertex contains:
Key-number of the vertex(and a unique key to use hashmap).
Tag-distance from the parent vertex.
Info-color of the vertex. 
Have 3 colors: White color, Gray color, Black color.
(we used it at algorithm BFS-An explanation of this algorithm is below).
Hashmap<Integer,node_data>- represent the neighbors that connected to this vertex(between that vertex have a edge)
The class Graph_DS Represents a graph that contains vertexs that they can be with edges( connected/not connected) and MC that is  the Mode Count - for testing changes in the graph. Any change in the inner state of the graph should cause an increment in the ModeCount

The class Graph_Algo have some algorithms on the graph.
Example of algorithms:  BFS, check if the graph is unweighted.
bfs at this task


The realization of this task was done by having a graph inside which there is hashmap that each key displays the number of the vertex and the value within it is the vertex itself (node) ie the address
In addition to each vertex there is also a hashmap that represents the list of neighbors of the vertex 
 That is, the list of vertices that have with the vertex itself a rib
Each key represents the vertex number, for example key 1 i.e. vertex with the number 1 and the value within it is the vertex itself (node) i.e. the address

Above each method there is an explanation in the task itself. 






An explanation of an algorithm in this task:
 
 
