---
title: 'Diversified recommendation with weighted hypergraph embedding: Case study in music'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Chaoguang Luo
  - Liuying Wen
  - Yong Qin
  - Philip S. Yu
  - admin
  - Zhineng Hu

date: '2025-01-25T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Neurocomputing
publication_short: Neurocomputing

abstract:  Recommender systems serve a dual purpose for users sifting out inappropriate or mismatched information while accurately identifying items that align with their preferences. Numerous recommendation algorithms rely on rich feature data to deliver personalized suggestions. However, in scenarios without explicit features, balancing accuracy and diversity in recommendations is a pressing concern. To address this challenge, exemplified by music recommendation, we introduce the Diversified Weighted Hypergraph Recommendation algorithm (DWHRec). In DWHRec, the initial connections between users and items are modeled using a weighted hypergraph, where additional entities linked to users and items, such as artists, albums, and tags, are simultaneously integrated into the hypergraph structure. To capture users’ latent preferences, a random-walk embedding method is applied to the hypergraph. Accuracy is measured by the match between users and items, and diversity is gauged by the variety of recommended item types. Extensive experiments conducted on two real-world music datasets show that DWHRec substantially outperforms eight state-of-the-art algorithms in terms of accuracy and diversity. Beyond music recommendation, DWHRec is a versatile framework that can be applied to other domains with similar data structures. The algorithm code is available on GitHub.1



tags: ["HyperGraph", "Recommendation"]
---

