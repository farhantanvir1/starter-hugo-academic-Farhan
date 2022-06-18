---
title: Drug-Drug Interaction Prediction: a Purely SMILES Based Approach
publication_types:
  - "2"
authors:
  - Bri Bumgardner
  - Farhan Tanvir
  - Khaled Mohammed Saifuddin
  - Esra Akbas
doi: 10.1109/BigData52589.2021.9671766
publication: IEEE Big Data 2021
abstract: ""
draft: false
featured: true
image:
  filename: featured
  focal_point: Smart
  preview_only: false
summary: "We propose a novel Network Embedding method, NECL, to generate
  embedding more efficiently or effectively. Our goal is to answer the following
  two questions: 1) Does the network Compression significantly boost Learning?
  2) Does network compression improve the quality of the representation? For
  these goals, first, we propose a novel graph compression method based on the
  neighborhood similarity that compresses the input graph to a smaller graph
  with incorporating local proximity of its vertices into super-nodes; second,
  we employ the compressed graph for network embedding instead of the original
  large graph to bring down the embedding cost and also to capture the global
  structure of the original graph; third, we refine the embeddings from the
  compressed graph to the original graph."
date: 2021-09-12T02:20:48.643Z
---
A drug-drug interaction (DDI) occurs when a drug is combined with other drug(s). DDIs have the potential to obstruct, increase, or diminish the intended impact of a drug or, in the worst-case scenario, induce an undesirable side effect. While it is critical to discover DDIs during clinical trials, it is impractical and expensive to detect all possible DDIs for a drug. Although several computational approaches for this problem have been developed, many of these methods need external biomedical knowledge that makes them difficult to generalize to drugs in early development phase. In this paper, we propose a novel method for predicting DDIs based on the vital chemical substructure of drugs extracted from their SMILES strings. We construct a graph that connects drugs based on their common functional chemical substructures. Furthermore, we apply different well-known graph neural network (GNN) methods to generate drug embeddings. Drug embeddings of individual drugs are concatenated to generate features of drug pairs. Finally, drug pair features are fed to different machine learning (ML) classifiers for DDI prediction. We evaluate our model on DrugBank dataset. Our result shows promising results and our model outperforms a baseline model based on different DDI representation creation methods.