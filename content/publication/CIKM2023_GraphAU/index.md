---
title: 'Graph-based Alignment and Uniformity for Recommendation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Zhiwei Liu
  - Chen Wang
  - Mingdai Yang
  - Xiaolong Liu
  - Jing Ma
  - Philip S. Yu

date: '2023-10-25T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: The 32nd ACM International Conference on Information and Knowledge Management
publication_short: In CIKM 2023

abstract: Collaborative filtering-based recommender systems (RecSys) rely on learning representations for users and items to predict preferences accurately. Representation learning on the hypersphere is a promising approach due to its desirable properties, such as alignment and uniformity. However, the sparsity issue arises when it encounters RecSys. To address this issue, we propose a novel approach, graph-based alignment and uniformity (GraphAU), that explicitly considers high-order connectivities in the user-item bipartite graph. GraphAU aligns the user/item embedding to the dense vector representations of high-order neighbors using a neighborhood aggregator, eliminating the need to compute the burdensome alignment to high-order neighborhoods individually. To address the discrepancy in alignment losses, GraphAU includes a layer-wise alignment pooling module to integrate alignment losses layer-wise. Experiments on four datasets show that GraphAU significantly alleviates the sparsity issue and achieves state-of-the-art performance. We open-source GraphAU at https://github.com/YangLiangwei/GraphAU.

tags: []
---

