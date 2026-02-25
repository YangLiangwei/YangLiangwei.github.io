---
title: 'Personabench: Evaluating ai models on understanding personal information through accessing (synthetic) private user data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Juntao Tan
  - admin
  - Zuxin Liu
  - Zhiwei Liu
  - Rithesh RN
  - Tulika Manoj Awalgaonkar
  - Jianguo Zhang
  - Weiran Yao
  - Ming Zhu
  - Shirley Kokane
  - Silvio Savarese
  - Huan Wang
  - Caiming Xiong
  - Shelby Heinecke


date: '2025-7-16T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: "Findings of the Association for Computational Linguistics: ACL 2025"
publication_short: "In ACL 2025"

abstract:  Personalization is essential for AI assistants, especially in private AI settings where models are expected to interpret users’ personal data (eg, conversations, app usage) to understand their background, preferences, and social context. However, due to privacy concerns, existing academic research lacks direct access to such data, making benchmarking difficult. To fill this gap, we propose a synthetic data pipeline that generates realistic user profiles and private documents, enabling the creation of PersonaBench—a benchmark for evaluating models’ ability to understand personal information. Using this benchmark, we assess Retrieval-Augmented Generation (RAG) pipelines on personalized questions and find that current models struggle to accurately extract and answer questions even when provided with the full set of user documents, highlighting the need for improved personalization methods.


tags: ["Personalization", "LLM", "RAG"]
---

