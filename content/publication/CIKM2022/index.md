---
title: 'ContrastVAE: Contrastive Variational AutoEncoder for Sequential Recommendation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yu Wang
  - Hengrui Zhang
  - Zhiwei Liu
  - admin
  - Philip S. Yu

date: '2022-08-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: The 31st ACM International Conference on Information and Knowledge Management
publication_short: In CIKM 2022

abstract: Aiming at exploiting the rich information in user behaviour sequences, sequential recommendation has been widely adopted in real-world recommender systems. However, current methods suffer from the following issues 1) sparsity of user-item interactions, 2) uncertainty of sequential records, 3) long-tail items. In this paper, we propose to incorporate contrastive learning into the framework of Variational AutoEncoders to address these challenges simultaneously. Firstly, we introduce ContrastELBO, a novel training objective that extends the conventional single-view ELBO to two-view case and theoretically builds a connection between VAE and contrastive learning from a two-view perspective. Then we propose Contrastive Variational AutoEncoder (ContrastVAE in short), a two-branched VAE model with contrastive regularization as an embodiment of ContrastELBO for sequential recommendation. We further introduce two simple yet effective augmentation strategies named model augmentation and variational augmentation to create a second view of a sequence and thus making contrastive learning possible. Experiments on four benchmark datasets demonstrate the effectiveness of ContrastVAE and the proposed augmentation methods. Codes are available at https://github.com/YuWang-1024/ContrastVAE.

tags: []
---

