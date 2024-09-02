---
title: "Seq-HyGAN: Sequence Classification via Hypergraph Attention Network"
authors:
  - Khaled Mohammed Saifuddin
  - Corey May
  - Farhan Tanvir 
  - Muhammad Ifte Khairul Islam and Esra Akbas
doi: 10.48550/arXiv.2303.02393
author_notes: []
publication_short: "In CIKM 2023"
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
summary: "We propose a novel Hypergraph Attention Network model, namely Seq-HyGAN. Our approach is built on the assumption that sequences sharing structural similarities tend to belong to the same classes, and sequences can be considered similar if they contain similar subsequences. To effectively capture the structural similarities between sequences, we represent them in a hypergraph framework, where the sequences are depicted as hyperedges that connect their respective subsequences as nodes. This construction allows us to create a single hypergraph encompassing all the sequences in the dataset. Unlike a standard graph where the degree of each edge is 2, hyperedge is degree-free; it can connect an arbitrary number of nodes. To enhance the representation of sequences and capture complex relationships among them, we introduce a novel Seq-HyGAN architecture that employs a three-level attention-based neural network. "
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
publication: "CIKM 2023"
featured: true
date: 2023-05-09T02:33:00.000Z
url_slides: ""
publishDate: "2023-07-11T00:00:00.000Z"
url_poster: ""
url_code: ""
doi: "10.48550/arXiv.2206.12747"
---
Extracting meaningful features from sequences and devising effective similarity measures are vital for sequence data mining tasks, particularly sequence classification. While neural network models are commonly used to automatically learn sequence features, they are limited to capturing adjacent structural connection information and ignoring global, higher-order information between the sequences. To address these challenges, we propose a novel
Hypergraph Attention Network model, namely Seq-HyGAN for sequence classification problems. To capture the complex structural similarity between sequence data, we create a novel hypergraph model by defining higher-order relations between subsequences extracted from sequences. Subsequently, we introduce a Sequence Hypergraph Attention Network that learns sequence features by considering the significance of subsequences and sequences to one another. Through extensive experiments, we demonstrate the effectiveness of our proposed Seq-HyGAN model in accurately classifying sequence data, outperforming several state-of-the-art methods by a significant margin.
