---
title: 'Federated Social Recommendation with Graph Neural Network'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zhiwei Liu
  - admin
  - Ziwei Fan
  - Hao Peng
  - Philip S. Yu

date: '2022-02-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: ACM Transactions on Intelligent Systems and Technology
publication_short: In TIST

abstract: Recommender systems have become prosperous nowadays, designed to predict users’ potential interests in items by learning embeddings. Recent developments of the Graph Neural Networks (GNNs) also provide recommender systems with powerful backbones to learn embeddings from a user-item graph. However, only leveraging the user-item interactions suffers from the cold-start issue due to the difficulty in data collection. Hence, current endeavors propose fusing social information with user-item interactions to alleviate it, which is the social recommendation problem. Existing work employs GNNs to aggregate both social links and user-item interactions simultaneously. However, they all require centralized storage of the social links and item interactions of users, which leads to privacy concerns. Additionally, according to strict privacy protection under General Data Protection Regulation, centralized data storage may not be feasible in the future, urging a decentralized framework of social recommendation. As a result, we design a federated learning recommender system for the social recommendation task, which is rather challenging because of its heterogeneity, personalization, and privacy protection requirements. To this end, we devise a novel framework Fe drated So cial recommendation with G raph neural network ( FeSoG ). Firstly, FeSoG adopts relational attention and aggregation to handle heterogeneity. Secondly, FeSoG infers user embeddings using local data to retain personalization. Last but not least, the proposed model employs pseudo-labeling techniques with item sampling to protect the privacy and enhance training. Extensive experiments on three real-world datasets justify the effectiveness of FeSoG in completing social recommendation and privacy protection. We are the first work proposing a federated learning framework for social recommendation to the best of our knowledge.

tags: []
---

