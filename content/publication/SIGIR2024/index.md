---
title: 'Instruction-based Hypergraph Pretraining'

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
  - Philip S. yu

date: '2024-07-18T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: Proceedings of the 47th International ACM SIGIR Conference on Research and Development in Information Retrieval
publication_short: In SIGIR 2024

abstract:  Pretraining has been widely explored to augment the adaptability of graph learning models to transfer knowledge from large datasets to a downstream task, such as link prediction or classification. However, the gap between training objectives and the discrepancy between data distributions in pretraining and downstream tasks hinders the transfer of the pre-trained knowledge. Inspired by instruction-based prompts widely used in pre-trained language models, we introduce instructions into graph pertaining. In this paper, we propose a novel pretraining framework named Instruction-based Hypergraph Pretraining. To overcome the discrepancy between pretraining and downstream tasks, text-based instructions provide explicit guidance on specific tasks for representation learning. Compared to learnable prompts, whose effectiveness depends on the quality and diversity of training data, text-based instructions intrinsically encapsulate task information and support the model's generalization beyond the structure seen during pretraining. To capture high-order relations with task information in a context-aware manner, a novel prompting hypergraph convolution layer is devised to integrate instructions into information propagation in hypergraphs. Extensive experiments conducted on three public datasets verify the superiority of IHP in various scenarios.


tags: ["Instruction Pretraining", "HyperGraph", "Recommendation"]
---

