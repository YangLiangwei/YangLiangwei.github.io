---
title: 'Personalized Multi-task Training for Recommender System'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Zhiwei Liu
  - Jianguo Zhang
  - Rithesh Murthy
  - Shelbu Heinecke
  - Huan Wang
  - Caiming Xiong
  - Philip S. Yu

date: '2024-12-15T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 2024 IEEE International Conference on Big Data (BigData)
publication_short: In IEEE BigData 2024

abstract: In the vast landscape of internet information, recommender systems (RecSys) have become essential for guiding users through a sea of choices aligned with their preferences. These systems have applications in diverse domains. Personalization is a key technique in RecSys, where modern methods leverage representation learning to encode user/item interactions into embeddings, forming the foundation for personalized recommendations. However, integrating information from multiple sources to enhance recommendation performance remains challenging. This paper introduces a novel approach named PMTRec, the first personalized multi-task learning algorithm to obtain comprehensive user/item embeddings from various information sources. Addressing challenges specific to personalized RecSys, we develop modules to handle personalized task weights, diverse task orientations, and variations in gradient magnitudes across tasks. PMTRec dynamically adjusts task weights based on gradient norms for each user/item, employs a Task Focusing module to align gradient combinations with the main recommendation task, and uses a Gradient Magnitude Balancing module to ensure balanced training across tasks. Through extensive experiments on three real-world datasets with different scales, we demonstrate that PMTRec significantly outperforms existing multi-task learning methods, showcasing its effectiveness in achieving enhanced recommendation accuracy by leveraging multiple tasks simultaneously. Our contributions open new avenues for advancing personalized multi-task training in RecSys.


tags: ['RecSys', 'Multi-task Learning']
---

