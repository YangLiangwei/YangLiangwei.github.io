---
title: 'Llminit: A free lunch from large language models for selective initialization of recommendation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Weizhi Zhang
  - admin
  - Wooseong Yang
  - Henry Peng Zou
  - Yuqing Liu
  - Ke Xu
  - Sourav Medya
  - Philip S Yu


date: '2025-11-22T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing: Industry Track"
publication_short: "In EMNLP 2025"

abstract: |
 Collaborative filtering (CF) is widely adopted in industrial recommender systems (RecSys) for modeling user-item interactions across numerous applications, but often struggles with cold-start and data-sparse scenarios. Recent advancements in pre-trained large language models (LLMs) with rich semantic knowledge, offer promising solutions to these challenges. However, deploying LLMs at scale is hindered by their significant computational demands and latency. In this paper, we propose a novel and scalable LLM-RecSys framework, LLMInit, designed to integrate pretrained LLM embeddings into CF models through selective initialization strategies. Specifically, we identify the embedding collapse issue observed when CF models scale and match the large embedding sizes in LLMs and avoid the problem by introducing efficient sampling methods, including, random, uniform, and variance-based selections. Comprehensive experiments conducted on multiple real-world datasets demonstrate that LLMInit significantly improves recommendation performance while maintaining low computational costs, offering a practical and scalable solution for industrial applications. com/DavidZWZ/LLMInit.



tags: ["RecSys", "LLM", "Collaborative Filtering"]
---

