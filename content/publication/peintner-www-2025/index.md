---
title: Hypergraph-based Temporal Modelling of Repeated Intent for Sequential Recommendation
authors:
- Andreas Peintner
- Amir Reza Mohammadi
- Michael Müller
- Eva Zangerle
date: '2025-01-01'
publishDate: '2025-04-23T13:45:12.036866Z'
publication_types:
- paper-conference
publication: '*Proceedings of the ACM Web Conference 2025*'
doi: 10.1145/3696410.3714896
abstract: In sequential recommendation scenarios, user intent is a key driver of consumption
  behavior. However, consumption intents are usually latent and hence, difficult to
  leverage for recommender systems. Additionally, intents can be of repeated nature
  (e.g. yearly shopping for christmas gifts or buying a new phone), which has not
  been exploited by previous approaches. To navigate these impediments we propose
  the HyperHawkes model which models user sessions via hypergraphs and extracts user
  intents via contrastive clustering. We use Hawkes Processes to model the temporal
  dynamics of intents, namely repeated consumption patterns and long-term interests
  of users. For short-term interest adaption, which is more fine-grained than intent-level
  modeling, we use a multi-level attention mixture network and fuse long-term and
  short-term signals. We use the generalized expectation-maximization (EM) framework
  for training the model by alternating between intent representation learning and
  optimizing parameters of the long- and short-term modules. Extensive experiments
  on four real-world datasets from different domains show that HyperHawkes significantly
  outperforms existing state-of-the-art methods.
tags:
- graph neural network
- hypergraph
- intent
- recommender systems
- sequential recommendation
links:
- name: URL
  url: https://doi.org/10.1145/3696410.3714896
---
