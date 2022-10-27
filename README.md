# One-Class Recommendation through Unsupervised Graph Neural Networks for Link Prediction

- Marcos Gôlo (ICMC/USP) | marcosgolo@usp.br (corresponding author)
- Leonardo Moraes (ICMC/USP) | leonardo.g.moraes@usp.br
- Rudinei Goularte (ICMC/USP) | rudinei@icmc.usp.br
- Ricardo Marcacini (ICMC/USP) | ricardo.marcacini@icmc.usp.br

# Abstract
Recommender systems play a key role in every online platform to provide users a better experience. Many classic recommendation approaches might find issues, mainly modeling user relations. Graphs can naturally model these relations since we can connect users interacting with items. On the other hand, when we model user-item relations through graphs, we do not have interactions between all users and items. Furthermore, it is difficult to cover the scope of non-recommendations, i.e., every item that the user does not want to be recommended and there are few interactions of this type. An alternative is One-Class Learning (OCL) which is able to recommend or not an item for a user only with the recommendations, mitigating the needing to cover the scope of non-recommendations and the imbalance scenario. Before using OCL to recommend, we must obtain a representation through the graph for the users and items. In this sense, we propose the one-class recommendation via representations learned by unsupervised graph neural networks (GNNs) for link prediction to generate a more robust and meaningful representation of users and items in the one-class recommendation. In the results, comparing the representations in the one-class recommendation, our GNNs for link prediction outperform other methods to represent the users and items in the one-class recommendation. Furthermore, our proposal, a GNN for link prediction and a OCL algorithm, also outperform a end-to-end GNN for link prediction. Thus, our proposal recommended better and learned more robust representations.

# Proposal: Mutlimodal One-Class Learning
![Proposal](/images/proposal.png)

# Results
![Results](/images/results.png)

# File Organization
- Dataset: Dataset files
- Results: total results of each method in each scenario considering all parameters used
- Code: source codes used for the study experiments and result analysis
