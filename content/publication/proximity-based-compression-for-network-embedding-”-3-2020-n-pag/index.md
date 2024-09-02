---
title: Proximity-Based Compression for Network Embedding
publication_types:
  - "2"
authors:
  - Muhammad Ifte Khairul Islam
  - Farhan Tanvir
  - Ginger Johnson
  - Esra Akbas and Mehmet Aktas
doi: 10.3389/fdata.2020.608043
publication: "Frontiers in Big Data"
abstract: ""
draft: false
active: false
featured: true
image:
  filename: featured
  focal_point: Smart
  preview_only: false
summary: "We propose a novel Network Embedding method, NECL, to generate
embedding more efficiently or effectively. Our goal is to answer the following
 two questions: 1) Does the network Compression significantly boost learning? 2) Does network compression improve the quality of the representation? For these goals, first, we propose a novel graph compression method based on the
 neighborhood similarity that compresses the input graph to a smaller graph with incorporating local proximity of its vertices into super-nodes; second, we employ the compressed graph for network embedding instead of the original large graph to bring down the embedding cost and also to capture the global structure of the original graph; third, we refine the embeddings from the compressed graph to the original graph."
date: 2021-09-12T02:20:48.643Z
---
Network embedding that encodes structural information of graphs into a low-dimensional vector space has been proven to be essential for network analysis applications, including node classification and community detection. Although recent methods show promising performance for various applications, graph embedding still has some challenges; either the huge size of graphs may hinder a direct application of the existing network embedding method to them, or they suffer compromises in accuracy from locality and noise. In this paper, we propose a novel Network Embedding method, NECL, to generate embedding more efficiently or effectively. Our goal is to answer the following two questions: 1) Does the network Compression significantly boost Learning? 2) Does network compression improve the quality of the representation? For these goals, first, we propose a novel graph compression method based on the neighborhood similarity that compresses the input graph to a smaller graph with incorporating local proximity of its vertices into super- nodes; second, we employ the compressed graph for network embedding instead of the original large graph to bring down the embedding cost and also to capture the global structure of the original graph; third, we refine the embeddings from the compressed graph to the original graph. NECL is a general meta-strategy that improves the efficiency and effectiveness of many state-of-the-art graph embedding algorithms based on node proximity, including DeepWalk, Node2vec, and LINE. Extensive experiments validate the efficiency and effectiveness of our method, which decreases embedding time and improves classification accuracy as evaluated on single and multi-label classification tasks with large real-world graphs.
