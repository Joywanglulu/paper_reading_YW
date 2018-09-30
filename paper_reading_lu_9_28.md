# 9.28.2018 recommendation day
## [A review on deep learning for recommender systems: challenges and remedies](https://link.springer.com/content/pdf/10.1007%2Fs10462-018-9654-y.pdf)
***
Overview: This paper reviews DL methods for recommendation.  Autoencoders are used for feature extracting, dimensionality reduction, and producing predictions. RNNs are utilized to integrate historical views to obtain the evolution of users tastes coevolution between user and item (especially for session-based recommendation which integrates users's implicit behaviors to their preferences). CNNs are mainly used for extracting latent factors and features from data, especially from images and text.

## [Next Item Recommendation with Self-Attention, arXiv 2018.](https://arxiv.org/pdf/1808.06414.pdf)
***
Overview: To exploit users' historical interactions for sequential recommendation task, this paper proposes a ``local-global" approach which consists of a self-attention module to capture user short-term intent, and a collaborative metric learning to model user long-term preference. 
Something interesting:
1. Dot product violate the important inequality property of metric function and will lead to sub-optimal solutions. Because it is known that dot product does not satisfy the triangle inequality which is defined as: “the distance between two points cannot be larger than the sum of their distances from a third point”.

## [Metric Factorization: Recommendation beyond Matrix Factorization, arXiv 2018.](https://arxiv.org/pdf/1802.04606.pdf)
***
Overview: Matrix factorization (MF) methods with dot product violate the inequality property. This paper proposes a novel metric factorization (MF_E) method to replace the dot product of MF with Euclidean distance. This method consists of two steps: 1. convert rating/interaction matrix R into distance matrix Y; 2. Factorize Y (the only difference between MF loss and MF_E loss is that the dot product with Euclidean distance).




## [RippleNet: Propagating User Preferences on the Knowledge Graph for Recommender Systems, CIKM 2018](https://arxiv.org/pdf/1803.03467.pdf)
***
Overview: This paper considers KG as side information to address the sparsity and cold start problem of collaborative filtering.




