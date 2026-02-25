---
title: 'PRACT: Optimizing Principled Reasoning and Acting of LLM Agent'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zhiwei Liu
  - Weiran Yao
  - Jianguo Zhang
  - Rithesh Murthy
  - admin
  - Zuxin Liu
  - Tian Lan
  - Ming Zhu
  - Juntao Tan
  - "et al."

date: '2024-12-25T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 33rd ACM International Conference on Information and Knowledge Management"
publication_short: "In CONLL 2024"

abstract:  We introduce the Principled Reasoning and Acting (PRAct) framework, a novel method for learning and enforcing action principles from trajectory data. Central to our approach is the use of text gradients from a reflection and optimization engine to derive these action principles. To adapt action principles to specific task requirements, we propose a new optimization framework, Reflective Principle Optimization (RPO). After execution, RPO employs a reflector to critique current action principles and an optimizer to update them accordingly.We investigate the RPO framework under two scenarios: Reward-RPO, which uses environmental rewards for reflection, and Self-RPO, which conducts self-reflection without external rewards. Additionally, we developed two RPO methods, RPO-Traj and RPO-Batch, to adapt to different settings.Experimental results across four environments demonstrate that the PRAct agent, leveraging the RPO framework, can effectively learn and apply action principles to enhance performance.


tags: ["Agent", "Optimization", "Large Language Model"]
---

