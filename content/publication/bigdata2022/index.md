---
title: 'MetaKRec: Collaborative Meta-Knowledge Enhanced Recommender System'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Shen Wang
  - Jibing Gong
  - Shaojie Zheng
  - Shuying Du
  - Zhiwei Liu
  - Philip S. Yu

date: '2022-12-15T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: IEEE International Conference on Big Data
publication_short: In IEEE BigData 2022

abstract: Knowledge graph (KG) enhanced recommendation has demonstrated improved performance in the recommendation system (RecSys) and attracted considerable research interest. Recently the literature has adopted neural graph networks (GNNs) on the collaborative knowledge graph and built an end-to-end KG-enhanced RecSys. However, the majority of these approaches have three limitations (1) treat the collaborative knowledge graph as a homogeneous graph and overlook the highly heterogeneous relationships among items, (2)lack of design to explicitly leverage the rich side information, and (3) overlook the rich knowledge in user preference. To fill this gap, in this paper, we explore the rich, heterogeneous relationship among items and propose a new KG-enhanced recommendation model called Collaborative Meta-Knowledge Enhanced Recommender System (MetaKRec). In particular, we focus on modeling the rich, heterogeneous semantic relationships among items and construct several collaborative Meta-KGs to explicitly depict the relatedness of the items under the guidance of meta-knowledge.  In addition to the knowledge obtained from KG, we leverage user knowledge that extracts from user preference to construct the Meta-KGs. The constructed Meta-KGs can capture the knowledge from both the knowledge graph and user preference. Furthermore. we utilize a light convolution encoder to recursively integrate the item relationship in each collaborative Meta-KGs. This scheme allows us to explicitly gather the heterogeneous semantic relationships among items and encode them into the representations of items. In addition, we propose channel attention to fuse the item and user representations from different Meta-KGs. Extensive experiments are conducted on four real-world benchmark datasets, demonstrating significant gains over the state-of-the-art baselines on both regular and cold-start recommendation settings. 

tags: []
---

