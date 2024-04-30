---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Height Optimized Tries
subtitle: ''
summary: ''
authors:
- Robert Binna
- Eva Zangerle
- Martin Pichl
- Günther Specht
- Viktor Leis
tags:
- Height optimized trie
- main memory
- index structure
- SIMD
categories: []
date: '2022-04-01'
lastmod: 2022-04-07T19:51:33+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-04-07T17:51:21.185273Z'
publication_types: ["article-journal"]
abstract: We present the Height Optimized Trie (HOT), a fast and space-efficient in-memory
  index structure. The core algorithmic idea of HOT is to dynamically vary the number
  of bits considered at each node, which enables a consistently high fanout and thereby
  good cache efficiency. For a fixed maximum node fanout, the overall tree height
  is minimal and its structure is deterministically defined. Multiple carefully engineered
  node implementations using SIMD instructions or lightweight compression schemes
  provide compactness and fast search and optimize HOT structures for different usage
  scenarios. Our experiments, which use a wide variety of workloads and data sets,
  show that HOT outperforms other state-of-the-art index structures for string keys
  both in terms of search performance and memory footprint, while being competitive
  for integer keys.
publication: '*ACM Transactions on Database Systems*'
doi: 10.1145/3506692
links:
- name: URL
  url: https://doi.org/10.1145/3506692
---
