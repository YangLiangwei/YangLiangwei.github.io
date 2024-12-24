---
title: 'Pre-Training with Transferable Attention for Addressing Market Shifts in Cross-Market Sequential Recommendation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Chen Wang
  - Ziwei Fan
  - admin
  - Mingdai Yang
  - Xiaolong Liu
  - Zhiwei Liu
  - Philip S. yu

date: '2024-08-25T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: Proceedings of the 30th ACM SIGKDD Conference on Knowledge Discovery and Data Mining
publication_short: In KDD 2024

abstract:  Cross-market recommendation (CMR) involves selling the same set of items across multiple nations or regions within a transfer learning framework. However, CMR's distinctive characteristics, including limited data sharing due to privacy policies, absence of user overlap, and a shared item set between markets present challenges for traditional recommendation methods. Moreover, CMR experiences market shifts, leading to differences in item popularity and user preferences among different markets. This study focuses on cross-market sequential recommendation (CMSR) and proposes the Cross-market Attention Transferring with Sequential Recommendation (CAT-SR) framework to address these challenges and market shifts. CAT-SR incorporates a pre-training strategy emphasizing item-item correlation, selective self-attention transferring for effective transfer learning, and query and key adapters for market-specific user preferences. Experimental results on real-world cross-market datasets demonstrate the superiority of CAT-SR, and ablation studies validate the benefits of its components across different geographical continents. CAT-SR offers a robust and adaptable solution for cross-market sequential recommendation. The code is available at https://github.com/ChenMetanoia/CATSR-KDD/.


tags: ["Cross-Market", "Attention", "Recommendation"]
---

