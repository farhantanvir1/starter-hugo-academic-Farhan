---
title: "HyGNN: Drug-Drug Interaction Prediction via Hypergraph Neural Network"
authors:
  - Khaled Mohammed Saifuddin
  - Briana Bumgardner
  - Farhan Tanvir and Esra Akbas
doi: 10.48550/arXiv.2206.12747
author_notes: []
publication_short: "In ICDE 2023"
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
summary: "We develop a hypergraph neural network (HyGNN), a model that learns the DDIs by generating and using the representation of hyperedges as drugs. HyGNN has an encoder-decoder ar- chitecture. First, we present a novel hypergraph edge encoder to generate the embedding of drugs. Afterward, the pair-wise representations of drugs are passed through decoder functions to predict a binary score for each drug pair that represents whether two drugs interact."
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
publication: "BioKDD 2022"
featured: true
date: 2022-11-09T02:33:00.000Z
url_slides: ""
publishDate: "2022-07-11T00:00:00.000Z"
url_poster: ""
url_code: ""
doi: "10.48550/arXiv.2206.12747"
---
Drug-Drug Interactions (DDIs) may hamper the functionalities of drugs, and in the worst scenario, they may lead to adverse drug reactions (ADRs). Predicting all DDIs is a challenging and critical problem. Most existing computational models integrate drug-centric information from different sources and leverage them as features in machine learning classifiers to predict DDIs. However, these models have a high chance of failure, especially for the new drugs when all the information is unavailable. This paper proposes a novel Hypergraph Neural Network (HyGNN) model based on only the SMILES string of drugs, available for any drug, for the DDI prediction problem. To capture the drug similarities, we create a hypergraph from drugs’ chemical substructures extracted from the SMILES strings. Then, we develop HyGNN consisting of a novel attention-based hypergraph edge encoder to get the representation of drugs as hyperedges and a decoder to predict the interactions between drug pairs. Furthermore, we conduct extensive experiments to evaluate our model and compare it with several state-of-the-art methods. Experimental results demonstrate that our proposed HyGNN model effectively predicts DDIs and impressively outper- forms the baselines with a maximum F1 score, ROC-AUC, and PR-AUC of 94.61%, 98.69% and 98.68%, respectively.
