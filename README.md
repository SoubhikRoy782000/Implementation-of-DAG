# Implementation-of-DAG

Aim - 

To implement DAG (Directed Acyclic Graph)


Algorithm -

Step 1 – Create a function named procedure Depth_First
Step 2 – if not visited[i] then visited[i] := true; with Tree traversals.
Step 3 – for all edge <i,j> Depth_First(j) , j must follow i in top'-sort
Step 4 – end for; save(i), record or process Vertex i
Step 5 – end Depth_First;
Step 6 – for all i :Vertex visited[i] := false ,initialise visited[]; been nowhere! 
Step 7 – end for; for all i :Vertex Depth_First(i) ,try all possible starting points
Step 8 – end for Depth-First Traversal of a Graph from a given Vertex.
