---
title: 'Apigen: Automated pipeline for generating verifiable and diverse function-calling datasets'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zuxin Liu
  - Thai Hoang
  - Jianguo Zhang
  - Ming Zhu
  - Tian Lan
  - Juntao Tan
  - Weiran Yao
  - Zhiwei Liu
  - Yihao Feng
  - Rithesh RN
  - admin
  - Silvio Savarese
  - Juan Carlos Niebles
  - Huan Wang
  - Shelby Heinecke
  - Caiming Xiong

date: '2024-12-16T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: Advances in Neural Information Processing Systems 2024
publication_short: In NIPS 2024

abstract:  The advancement of function-calling agent models requires diverse, reliable, and high-quality datasets. This paper presents APIGen, an automated data generation pipeline designed to synthesize high-quality datasets for function-calling applications. We leverage APIGen and collect 3,673 executable APIs across 21 different categories to generate diverse function-calling datasets in a scalable and structured manner. Each data in our dataset is verified through three hierarchical stages: format checking, actual function executions, and semantic verification, improving its reliability and correctness. We demonstrate that models trained with our curated datasets, even with only 7B parameters, can achieve state-of-the-art performance on the Berkeley Function-Calling Benchmark, outperforming multiple GPT-4 models. Moreover, our 1B model achieves exceptional performance, surpassing GPT-3.5-Turbo and Claude-3 Haiku. We release a dataset containing 60,000 high-quality entries, aiming to advance the field of function-calling agent domains. The dataset and models are available on the project homepage\url {https://apigen-pipeline. github. io/}.


tags: ["Function Call", "Agent", "LLM"]
---

