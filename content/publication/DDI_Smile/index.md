---
title: "Drug-Drug Interaction Prediction: a Purely SMILES Based Approach"
authors:
  - Bri Bumgardner
  - Farhan Tanvir
  - Khaled Mohammed Saifuddin and Esra Akbas
doi: 10.1109/BigData52589.2021.9671766
author_notes: []
publication_short: "In IEEE Big Data 2021"
abstract: ""
tags: []
projects: []
slides: ""
url_pdf: ""
publication_types:
  - "1"
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: DDI_Smile_sys_arch.jpg
summary: "We propose a new method for DDI prediction where we learn the representation of drugs by considering only drugs’ chemical structures and their similarities. We consider two drugs to be similar if they have similar functional sub-structure (i.e., functional groups). Instead of using whole chemical structures of drugs to measure their similarities, we use frequent substructures in them."
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
publication: "2021 IEEE International Conference on Big Data (Big Data)"
featured: true
date: 2021-11-12T02:33:00.000Z
url_slides: ""
publishDate: "2021-11-012T00:00:00.000Z"
url_poster: ""
url_code: ""
doi: "10.1109/BigData52589.2021.9671766"
---
A drug-drug interaction (DDI) occurs when a drug is combined with other drug(s). DDIs have the potential to obstruct, increase, or diminish the intended impact of a drug or, in the worst-case scenario, induce an undesirable side effect. While it is critical to discover DDIs during clinical trials, it is impractical and expensive to detect all possible DDIs for a drug. Although several computational approaches for this problem have been developed, many of these methods need external biomedical knowledge that makes them difficult to generalize to drugs in early development phase. In this paper, we propose a novel method for predicting DDIs based on the vital chemical substructure of drugs extracted from their SMILES strings. We construct a graph that connects drugs based on their common functional chemical substructures. Furthermore, we apply different well-known graph neural network (GNN) methods to generate drug embeddings. Drug embeddings of individual drugs are concatenated to generate features of drug pairs. Finally, drug pair features are fed to different machine learning (ML) classifiers for DDI prediction. We evaluate our model on DrugBank dataset. Our result shows promising results and our model outperforms a baseline model based on different DDI representation creation methods.
