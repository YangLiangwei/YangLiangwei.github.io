---
title: 'Do We Really Need Graph Convolution During Training? Light Post-Training Graph-ODE for Efficient Recommendation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Weizhi Zhang
  - admin
  - Zihe Song
  - Henry Peng Zhou
  - Ke Xu
  - Liancheng Fang
  - Philip S. yu

date: '2024-10-25T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: Proceedings of the 33rd ACM International Conference on Information and Knowledge Management
publication_short: In CIKM 2024

abstract:  The efficiency and scalability of graph convolution networks (GCNs) in training recommender systems (RecSys) have been persistent concerns, hindering their deployment in real-world applications. This paper presents a critical examination of the necessity of graph convolutions during the training phase and introduces an innovative alternative the Light Post-Training Graph Ordinary-Differential-Equation (LightGODE). Our investigation reveals that the benefits of GCNs are more pronounced during testing rather than training. Motivated by this, LightGODE utilizes a novel post-training graph convolution method that bypasses the computation-intensive message passing of GCNs and employs a non-parametric continuous graph ordinary-differential-equation (ODE) to dynamically model node representations. This approach drastically reduces training time while achieving fine-grained post-training graph convolution to avoid the distortion of the original training embedding space, termed the embedding discrepancy issue. We validate our model across several real-world datasets of different scales, demonstrating that LightGODE not only outperforms GCN-based models in terms of efficiency and effectiveness but also significantly mitigates the embedding discrepancy commonly associated with deeper graph convolution layers. Our LightGODE challenges the prevailing paradigms in RecSys training and suggests re-evaluating the role of graph convolutions, potentially guiding future developments of efficient large-scale graph-based RecSys.

tags: ["Graph Neural Network", "Recommendation"]
---

