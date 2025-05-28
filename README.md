# CombinatorialEvaluation 
A python library to compute combinatorial evaluation

![Image](https://github.com/user-attachments/assets/19550769-4831-4a13-8e66-00b2f0335246)

# Simple Example
```
#Create a graph with edge weight
G = nx.Graph()
G.add_edge("1", "2", weight=0.6)
G.add_edge("1", "3", weight=0.2)
G.add_edge("3", "4", weight=0.1)
G.add_edge("3", "5", weight=0.7)
G.add_edge("3", "6", weight=0.9)
G.add_edge("1", "4", weight=0.3)
#Give a vertex weight = 1
create_constant_vertex_list(G)

#Calculate combinatorial evaluation
CE = Combinatorial_Evaluation_list(G, create_constant_vertex_list(G))
CE
```

# Contact

# Cite
If you use this code in your research, please considering cite our paper:
