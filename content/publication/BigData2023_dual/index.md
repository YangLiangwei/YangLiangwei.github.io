---
title: 'Dual-Teacher Knowledge Distillation for Strict Cold-Start Recommendation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Weizhi Zhang
  - admin
  - Yuwei Cao
  - Ke Xu
  - Yuanjie Zhu
  - Philip S. Yu

date: '2023-10-25T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 2023 IEEE International Conference on Big Data (BigData)
publication_short: In IEEE BigData 2023

abstract: Recommender systems (RecSys) aim to predict users’ preferences based on historical interactions and content profiles, and they are vital components of many online services. However, the strict cold-start (SCS) issue, i.e., users/items have no prior interactions, poses significant challenges for RecSys. The existing methods seek to transfer content knowledge, collaborative filtering (CF) knowledge, or combine the two from the warm-start scenario towards the (strict) cold-start scenarios. However, these approaches either ignore the available information or model the information in rough manners such that the two types of knowledge interfere with each other, leading to ineffective and uncontrolled knowledge transfer. In this work, we propose a novel dual-teacher knowledge distillation (DTKD) framework that simultaneously and effectively transfers both content and CF knowledge. The proposed DTKD framework contains two teachers, one for each knowledge type, that is specifically designed according to the characteristics of the content and CF data to distill the knowledge fully. Soft scoring is calculated during the distillation to denoise and augment the original hard-labeled interactions. A knowledge fusion module is then proposed to collect the consensus of the two teachers’ opinions. Finally, DTKD transfers both content and CF knowledge into a student module that learns the shared viewpoints of the teachers. We conduct extensive experiments on real-world datasets under the warm-start as well as three different SCS settings (i.e., strict cold users, strict cold items, and strict cold users & items). Experimental results show that DTKD outperforms strong baselines by large margins under all settings, especially the SCS ones.

tags: []
---

