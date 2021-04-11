---
id: graph
title: Graph
sidebar_label: Graph
---

## Concept
Tree as you have seen and read is basically a graph with a well defined root node, in other words graph is an extension of trees, and are useful to represent real world connections and scenarios, for ex: connections on facebook or linkedin is a graph where you are a node and you are connected to other nodes in the graph. In order to get started with graphs you must first know the basic terminology of graphs and build a visual picture of what a graph looks like, the following articles will help you do so.

1. [Link 1](https://www.techiedelight.com/terminology-and-representations-of-graphs/)
2. [Link 2](https://www.programiz.com/dsa/graph)


## Representation of a graph

After knowing what a graph is , it’s important that you know how you can code a graph. There are 2 ways to represent graphs and you will have to learn about them in detail, each have their own advantages and disadvantages. To know you must read on, be sure to learn the basics properly.

Adjacency Matrix :
[Link 1](https://www.programiz.com/dsa/graph-adjacency-matrix)

Adjacency List :
[Link 1](https://www.programiz.com/dsa/graph-adjacency-list)




## DFS

DFS or depth first search is an algorithm for graph traversal, just like you have learnt tree traversal previously, this time you will learn about graph traversals, which are a must know because they help in solving more difficult and advanced level graph questions. So what is DFS ? What is the basic principle behind DFS ? How is it implemented ? What is the time complexity ? What are the applications of DFS ? All of these are important questions you should be able to answer once you have read about it from these good articles.
1. [Link 1](https://cp-algorithms.com/graph/depth-first-search.html)
2. [Link 2](https://www.programiz.com/dsa/graph-dfs)

QnA : Can you use stack to implement DFS ?

## Types of edges in DFS 
While performing DFS, you can store the arrival and departure times of a node/vertex which can be used to explore the type of edge between two vertices, this perspective of DFS will be critical and useful to your problem solving analysis. So don’t you wanna know the different types of edges ? if you do, you must read on.

1. [Link 1](https://www.techiedelight.com/arrival-departure-time-vertices-dfs/)
2. [Link 2](https://www.techiedelight.com/types-edges-involved-dfs-relation/)


## BFS
You have studied about DFS, now you are going to study about BFS which is another graph traversal algorithm. The questions that you have answered for DFS, the same questions must be answered for BFS, which are, what is BFS ? What is the basic principle behind BFS ? How is it implemented ? What is the time complexity ? What are the applications of BFS ? So you better start reading.

1. [Link 1](https://cp-algorithms.com/graph/breadth-first-search.html)
2. [Link 2](https://www.programiz.com/dsa/graph-bfs)


## Connected Components :

[Link 1](https://cp-algorithms.com/graph/search-for-connected-components.html)


## Finding bridges
[Link 1](https://cp-algorithms.com/graph/bridge-searching.html)


## Finding bridges online
[Link 1](https://cp-algorithms.com/graph/bridge-searching-online.html)


## Finding articulation points
[Link 1](https://www.hackerearth.com/practice/algorithms/graphs/articulation-points-and-bridges/tutorial/)<br/>
[Link 2](https://cp-algorithms.com/graph/cutpoints.html)


## Finding strongly connected component
[Link 1](https://cp-algorithms.com/graph/strongly-connected-components.html)<br/>
[Link 2](https://www.hackerearth.com/practice/algorithms/graphs/strongly-connected-components/tutorial/)


## Union-Find 
The basic use case of an edge is to connect two vertices, but if you see it’s not just connecting two vertices but all other vertices connected to these two vertices are now connected to each other via this edge, as if a union has happened. Union-find as you will see is a very useful algorithm that relates to union of two vertices whenever an edge is added between them, it helps to solve a specific pattern of questions very easily. So what is this union-find algorithm? What is the time complexity ? and how is it implemented ? All of these questions you must be able to answer after reading these wonderful articles .

1. [Link 1](https://cp-algorithms.com/data_structures/disjoint_set_union.html) ( Read upto time complexity inclusive )
2. [Link 2](https://codeforces.com/edu/course/2)
3. [Link 3](https://www.hackerearth.com/practice/notes/disjoint-set-union-union-find/)


## Dijkstra’s
How does uber know the shortest distance between your pick up point and your drop off point ? Dijkstra’s algorithm will be used whenever you want to find the shortest distance path from the source or starting vertex to all other vertices in the graph. Now that you know what Dijkstra is there are few other questions left to answer which are, what is the basic principle behind dijkstra ? how is it implemented ? What is the time complexity ? All of these questions you must be able to answer after reading these wonderful articles.

1. [Link 1](https://www.geeksforgeeks.org/dijkstras-shortest-path-algorithm-greedy-algo-7/)
2. [Link 2](https://cp-algorithms.com/graph/dijkstra.html)
3. [Link 3](https://www.techiedelight.com/single-source-shortest-paths-dijkstras-algorithm/)

:::important
This tool will help you to visualise dijkstra’s algo, be sure you are able to visualise it before proceeding any further
https://visualgo.net/en/sssp
:::

:::note
Dijkstra’s algorithm does not work when the edge weights can have negative values.
:::



## 0-1 BFS
It so happens that finding the single source shortest path using dijkstra’s can be an overkill if the edge weights contain one of only two possible values. For this special scenario 0-1 BFS can be deployed to find the SSSP ,which is easier to understand and code. So why does having this one special condition make it possible to use BFS ? The answer you will find in this articles but you must read on.

[Link 1](https://cp-algorithms.com/graph/01_bfs.html)


## Dijkstra’s on sparse graphs
When it comes to graphs based on its representation adjacency matrix or adjacency list, the dijkstra’s algorithm has different time complexity , here you will learn about the time complexity and implementation of dijkstra for sparse graphs which are represented using adjacency lists.

1. [Link 1](https://cp-algorithms.com/graph/dijkstra_sparse.html)
2. [Link 2](https://www.geeksforgeeks.org/dijkstras-algorithm-for-adjacency-list-representation-greedy-algo-8/)

:::important
The Dijkstra’s algorithm can be implemented using sets and priority with proper understanding of both containers you can use the more appropriate implementation.
1. [Link 1[(https://www.geeksforgeeks.org/dijkstras-shortest-path-algorithm-using-set-in-stl/)
2. [Link 2](https://www.geeksforgeeks.org/dijkstras-shortest-path-algorithm-using-priority_queue-stl/)
:::

## Bellman Ford’s
Bellman Ford’s algorithm overcomes the shortcoming of Dijkstra’s algorithm and enables you to find the SSSP when the graph has negative edge weights. So the questions that arise are, what is the basic principle behind Bellman Ford’s algorithm ? how is it implemented ? What is the time complexity ? All of these questions you must be able to answer after reading these wonderful articles.

1. [Link 1](https://cp-algorithms.com/graph/bellman_ford.html)
2. [Link 2](https://www.programiz.com/dsa/bellman-ford-algorithm)
3. [Link 3](https://www.techiedelight.com/single-source-shortest-paths-bellman-ford-algorithm/)
4. [Link 4](https://www.geeksforgeeks.org/bellman-ford-algorithm-dp-23/)


## Floyd-Warshall’s Algorithm
So far you have learned algorithms that find the shortest path from a single source vertex to all other vertices, but what if you have to find the shortest path from every vertex to every other vertex, is there any algorithm better than dijkstra's ? Fortunately there is , Floyd-Warshall’s is a DP based approach that will help you to find the all pair shortest path easily. You know the principle behind this approach, DP, but do you know how it is implemented or what is the time complexity ? If you don’t you must read these wonderful articles to find out.

1. [Link 1](https://cp-algorithms.com/graph/all-pair-shortest-path-floyd-warshall.html)
2. [Link 2](https://www.geeksforgeeks.org/floyd-warshall-algorithm-dp-16/)


## Spanning Tree
Spanning Tree is a type of graph which is a tree, in the sense that all the vertices will be connected and the number of edges will be one less than the vertex, building a spanning tree is usually a sub-problem to more difficult and challenging problems, but how do you build a spanning tree ? Is there any other useful variation to a spanning tree ? all  these questions will be answered, you have to just read on stay on track.

[Link 1](https://www.programiz.com/dsa/spanning-tree-and-minimum-spanning-tree)


## Kruskal’s Algo
You have learned about spanning tree and minimum spanning tree. Now you will learn how to create a minimum spanning tree from a graph. So what is the principle behind Kruskal’s algorithm ? How is it implemented ? What is the time complexity ? All these questions you must be able to answer after reading these wonderful articles. As a spoiler, Kruskal’s algorithm uses a greedy approach alongside union-find to find the minimum spanning tree. 

1. [Link 1](https://www.programiz.com/dsa/kruskal-algorithm)
2. [Link 2](https://cp-algorithms.com/graph/mst_kruskal.html)
3. [Link 3](https://cp-algorithms.com/graph/mst_kruskal_with_dsu.html)


## Prim's Algo
As an alternative to Kruskal’s algorithm to find the minimum spanning tree, you can use Prim’s Algorithm which also follows a greedy approach. So what is different about Prim’s algorithm, of course it's the principle behind Prim’s algorithm but what is this principle ? How is it implemented ? What is the time complexity ? All these questions you must be able to answer after reading these wonderful articles.
1. [Link 1](https://cp-algorithms.com/graph/mst_prim.html)
2. [Link 2](https://www.programiz.com/dsa/prim-algorithm)
3. [Link 3]( https://www.hackerearth.com/practice/algorithms/graphs/minimum-spanning-tree/tutorial/)

:::note
Incases where you can use both algorithms to find the MST, the choice of using Prim’s or Kruskal’s depends fairly on the ease of your understanding of the two and also on the ease of implementation.
:::

## Topological sort
For DAG, or Directed Acyclic Graphs you can come up with a special ordering of the vertices such that there is no backward edge. This ordering is a special condition that exists in many day to day scenarios, so it is very useful to learn about Topological sort which will help you to find this ordering of vertices. But remember that a graph must be a DAG. So what is a DAG ? How is it implemented ? What is the time complexity ? All these questions you must be able to answer after reading these wonderful articles.

1. [Link 1](https://www.hackerearth.com/practice/algorithms/graphs/topological-sort/tutorial/)
2. [Link 2](https://cp-algorithms.com/graph/topological-sort.html)
3. [Link 3](https://www.interviewcake.com/concept/java/topological-sort)
4. [Link 4](https://www.geeksforgeeks.org/topological-sorting-indegree-based-solution/)