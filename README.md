# Dijkstra-s-Algorithm
assignment 4 part2     


Dijstra's algorithm is an algorithm for finding the shortes oath between vertexs in a graph. this algorith will create a tree of shortest paths from the starting vertex or source to all other vertexs on the graph. the ay this is done is by having minimum distnace from the source by building a set of vertexs.

algorithm steps:
1. set the source to 0 while all other vertexs become a very large number.
2. the source vertex will go into a minimum priority queue in form of ditance to vertexs
3. then the vertex with minimum distnace from the priority queue will be poped the first one will be the source.
4. then the distances from the connected vertices will be updated to the popped vertex  through the formula vertex + weight < vertex2 distance.
5. push the vertex with new distnace into the priority queue
6. if the vertex was visited before then continue without using that vertex.
7. keep applying this algorith until the queue becomes empty.
