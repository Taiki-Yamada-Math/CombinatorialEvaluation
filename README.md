# CombinatorialEvaluation 
A python library to compute combinatorial evaluation. This is based on [our paper](https://arxiv.org/abs/2110.06506).

---

Combinatorial evaluation is a quantitative measure that combines the discrete geometry concept of Forman Ricci curvature and the game theory concept of Shapley value, and is useful for identifying the most important vertices in a network. It has a high correlation with network centrality and can be defined for more complex networks, making it highly versatile and applicable to a wide range of fields.

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

See [my homepage](https://researchmap.jp/taikiyamada?lang=en).

# Cite
If you use this code in your research, please considering cite our paper:

```
@misc{yamada2023newallocationruledirected,
      title={New allocation rule of directed hypergraphs}, 
      author={Taiki Yamada},
      year={2023},
      eprint={2110.06506},
      archivePrefix={arXiv},
      primaryClass={cs.GT},
      url={https://arxiv.org/abs/2110.06506}, 
}
```
