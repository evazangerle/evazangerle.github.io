---
title: Efficient Session-based Recommendation with Contrastive Graph-based Shortest
  Path Search
authors:
- Andreas Peintner
- Amir Reza Mohammadi
- Eva Zangerle
date: '2024-10-01'
publishDate: '2024-11-13T14:53:09.639462Z'
publication_types:
- article-journal
publication: '*ACM Transactions on Recommder Systems*'
doi: 10.1145/3701764
abstract: Session-based recommendation aims to predict the next item based on a set
  of anonymous sessions. Capturing user intent from a short interaction sequence imposes
  a variety of challenges since no user profiles are available and interaction data
  is naturally sparse. Recent approaches relying on graph neural networks (GNNs) for
  session-based recommendation use global item relations to explore collaborative
  information from different sessions. These methods capture the topological structure
  of the graph and rely on multi-hop information aggregation in GNNs to exchange information
  along edges. Consequently, graph-based models suffer from noisy item relations in
  the training data and introduce high complexity for large item catalogs. We propose
  to explicitly model the multi-hop information aggregation mechanism over multiple
  layers via shortest-path edges based on knowledge from the sequential recommendation
  domain. Our approach does not require multiple layers to exchange information and
  ignores unreliable item-item relations. Furthermore, to address inherent data sparsity,
  we are the first to apply supervised contrastive learning by mining data-driven
  positive and hard negative item samples from the training data. Extensive experiments
  on four different datasets show that the proposed approach outperforms almost all
  of the state-of-the-art methods.
tags:
- Recommender Systems
- Session-based Recommendation
- Graph Neural Network
- Supervised Contrastive Learning
links:
- name: URL
  url: https://doi.org/10.1145/3701764
---
