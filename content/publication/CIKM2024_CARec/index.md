---
title: 'Collaborative Alignment for Recommendation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Chen Wang
  - admin
  - Zhiwei Liu
  - Xiaolong Liu
  - Mingdai Yang
  - Yueqing Liang
  - Philip S. Yu

date: '2024-10-25T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: Proceedings of the 33rd ACM International Conference on Information and Knowledge Management
publication_short: In CIKM 2024

abstract:  Traditional recommender systems have primarily relied on identity representations (IDs) to model users and items. Recently, the integration of pre-trained language models (PLMs) has enhanced the capability to capture semantic descriptions of items. However, while PLMs excel in few-shot, zero-shot, and unified modeling scenarios, they often overlook the crucial signals from collaborative filtering (CF), resulting in suboptimal performance when sufficient training data is available. To effectively combine semantic representations with the CF signal and enhance recommender system performance in both warm and cold settings, two major challenges must be addressed (1) bridging the gap between semantic and collaborative representation spaces, and (2) refining while preserving the integrity of semantic representations. In this paper, we introduce CARec, a novel model that adeptly integrates collaborative filtering signals with semantic representations, ensuring alignment within the semantic space while maintaining essential semantics. We present experimental results from four real-world datasets, which demonstrate significant improvements. By leveraging collaborative alignment, CARec also shows remarkable effectiveness in cold-start scenarios, achieving notable enhancements in recommendation performance. The code is available at https://github.com/ChenMetanoia/CARec **REMOVE 2nd URL**://github.com/ChenMetanoia/CARec.


tags: ["Alignment", "Recommendation", "Large Language Model"]
---

