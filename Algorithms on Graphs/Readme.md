##Algorithms on Graphs

###What are graphs?
A Graph is a collection of abstract objects called as nodes that represent points of connection. They are then connected via paths or edges. 
Operations include traversing the graph, checking whether two nodes share an edge i.e. are connected, retreiving values from nodes or edges and
the deletion of nodes or edges from the graph.

The Internet can be thought of as a graph. Social networks can be thought of as a graph.

Apart from edges, there can be loops which connects a vertex to itself. Also there can be multiple edges between the same vertices.

###How are graphs stored in memory?
1. Create an adjacency matrix storing 0,1 representations of edges. Note that this cannot be used if there are multiple edges between same vertices.
2. Store ab edge list- all edges as (A,B), (B,C) etc. 
3. Store an adjacency list

