---
title: 'Multi-View Graph Convolution for Participant Recommendation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xiaolong Liu
  - admin
  - Chen Wang
  - Mingdai Yang
  - Zhiwei Liu
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

abstract: Social networks have become essential for people’s lives. The proliferation of web services further expands social networks at an unprecedented scale, leading to immeasurable commercial value for online platforms. Recently, the group buying (GB) business mode is prevalent and also becoming more popular in E-commerce. GB explicitly forms groups of users with similar interests to secure better discounts from the merchants, often operating within social networks. It is a novel way to further unlock the commercial value by explicitly utilizing the online social network in E-commerce. Participant recommendation, a fundamental problem emerging together with GB, aims to find the participants for a launched group buying process with an initiator and a target item to increase the GB success rate. This paper proposes Multi-View Graph Convolution for Participant Recommendation (MVPRec) to tackle this problem. To differentiate the roles of users (Initiator/Participant) within the GB process, we explicitly reconstruct historical GB data into initiator-view and participant-view graphs. Together with the social graph, we obtain a multi-view user representation with graph encoders. Then MVPRec fuses the GB and social representation with an attention module to obtain the user representation and learns a matching score with the initiator’s social friends via a multi-head attention mechanism. Social friends with the Top-k matching score are recommended for the corresponding GB process. Experiments on three datasets justify the effectiveness of MVPRec in the emerging participant recommendation problem. MVPRec is open-sourced at https://github.com/Xiaolong-Liu-bdsc/MVPRec to inspire further research in the new group buying E-commerce business mode.

tags: []
---

