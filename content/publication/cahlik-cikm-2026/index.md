---
title: 'From Counterfactual Edits to Human Narratives: LLM-Driven Interpretations
  for Recommender System Explanations'
authors:
- Vojtech Cahlik
- Amir Reza Mohammadi
- Rodrigo Alves
- Pavel Kordik
- Eva Zangerle
date: '2026-01-01'
publishDate: '2026-11-09T09:36:13.532394Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 35th ACM International Conference on Information
  and Knowledge Management*'
doi: 10.1145/3799682.3839968
abstract: Recommender systems increasingly influence what users discover and consume
  online, yet the decision logic behind their outputs often remains opaque. Counterfactual
  explanation (CFX) methods provide an effective way to show which changes to a user's
  interaction history would alter a recommendation. In recommendation settings, however,
  CFXs often require many edits, producing long, low-level lists that are hard for
  users to interpret. Moreover, most evaluations emphasize edit counts while largely
  overlooking whether the resulting CFXs are coherent and actionable for users. We
  argue that this gap between generating valid CFXs and communicating model behavior
  stems from the lack of user-centered abstraction and limited qualitative evaluation.
  To bridge this gap, we investigate large language models as mediators that summarize
  raw CFX interaction edit lists into concise natural language explanations describing
  higher-level preference patterns. We optimize these mediators for correctness, informativeness,
  and linguistic quality through preference optimization, and evaluate the resulting
  explanations with human-calibrated metrics derived from separate human-labeled datasets.
  On the MovieLens-1M dataset, across multiple counterfactual generators and language
  models, the resulting summaries achieve high overall linguistic quality, while the
  strongest semantic results are obtained with high-success CFX methods such as ACCENT
  and SPINRec. Direct Preference Optimization improves the semantic metrics in almost
  all evaluated settings.
tags:
- recommender systems
- counterfactual explanations
- natural language explanations
- large language models
links:
- name: URL
  url: https://doi.org/10.1145/3799682.3839968
---
