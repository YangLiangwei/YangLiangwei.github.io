---
title: 'Unified Pretraining for Recommendation via Task Hypergraphsn'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Mingdai Yang
  - Zhiwei Liu
  - admin
  - Xiaolong Liu
  - Chen Wang
  - Hao Peng
  - Philip S. Yu

date: '2024-03-25T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: Proceedings of the 17th ACM International Conference on Web Search and Data Mining
publication_short: In WSDM 2024

abstract:  Although pretraining has garnered significant attention and popularity in recent years, its application in graph-based recommender systems is relatively limited. It is challenging to exploit prior knowledge by pretraining in widely used ID-dependent datasets. On the one hand, user-item interaction history in one dataset can hardly be transferred to other datasets through pretraining, where IDs are different. On the other hand, pretraining and finetuning on the same dataset leads to a high risk of overfitting. In this paper, we propose a novel multitask pretraining framework named Unified Pretraining for Recommendation via Task Hypergraphs. For a unified learning pattern to handle diverse requirements and nuances of various pretext tasks, we design task hypergraphs to generalize pretext tasks to hyperedge prediction. A novel transitional attention layer is devised to discriminatively learn the relevance between each pretext task and recommendation. Experimental results on three benchmark datasets verify the superiority of UPRTH. Additional detailed investigations are conducted to demonstrate the effectiveness of the proposed framework.



tags: ["Recommendation", "Hypergraph"]
---

