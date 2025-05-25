## Graph regularization weighted nonnegative matrix factorization for link prediction in weighted complex network (2019)
- Authors = Chen, Guangfu and Xu, Chen and Wang, Jingyi and Feng, Jianwen and Feng, Jiqiang
- Journal = Neurocomputing
### Abstract
In weight networks, both link weights and topological structure are important features for link prediction. Currently, almost all existing weighted network link prediction algorithms only focused on naturally existed link weight but ignored the topological structure information. Therefore, these methods will suffer from the challenge of network sparsity and insufficient topology information. In this paper, we propose a novel Graph Regularization Weighted Nonnegative Matrix Factorization(GWNMF) model to integrate local topology information with link weights information for link prediction. Specifically, this model integrates two types of information: local topology and link weight information, and utilizes the weighted cosine similarity(WCS) method to calculate the weight similarity between local nodes. The WCS score matrix as the indicator weighted matrix to capture more useful link weight information. While graph regularization technology combines WCS score matrix to capture the local information. Besides, we derive the multiplicative updating rules to learn the parameter of this model. Empirically, we conduct the experiments on eight real-world weighted networks demonstrate that GWNMF remarkably outperforms the state-of-the-arts methods for weighted link prediction tasks.

If you find this implementation helpful in your work, please consider citing both the original paper and our related research on **Link prediction by adversarial NMF**:

## Original Paper:

```
@article{chen2019graph,
  title={Graph regularization weighted nonnegative matrix factorization for link prediction in weighted complex network},
  author={Chen, Guangfu and Xu, Chen and Wang, Jingyi and Feng, Jianwen and Feng, Jiqiang},
  journal={Neurocomputing},
  volume={369},
  pages={50--60},
  year={2019},
  publisher={Elsevier}
}
```

## Our Paper:
```
@article{mahmoodi2024enhancing,
  title={Enhancing link prediction through adversarial training in deep Nonnegative Matrix Factorization},
  author={Mahmoodi, Reza and Seyedi, Seyed Amjad and Abdollahpouri, Alireza and Tab, Fardin Akhlaghian},
  journal={Engineering Applications of Artificial Intelligence},
  volume={133},
  pages={108641},
  year={2024},
  publisher={Elsevier}
}
```
