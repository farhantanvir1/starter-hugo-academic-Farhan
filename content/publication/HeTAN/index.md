---
title: "HeTAN: Heterogeneous Graph Triplet Attention Network for Drug Repurposing"
authors:
  - Farhan Tanvir
  - Khaled Mohammed Saifuddin
  - Tanvir Hossain
  - Arunkumar Bagavathi and Esra Akbas
author_notes: []
publication_short: "In DSAA 2023"
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
summary: "We propose a novel Heterogeneous Graph Triplet Attention Network (HeTAN). HeTAN leverages the power of heterogeneous graphs, representing diverse entities and their interactions, and employs a novel triplet attention mechanism to capture higher-order interactions within the drug-target-disease triplets. We capture higher-order interactions between drug, target, and disease through a triplet-wise attention mechanism. This gives us a more comprehensive understanding of drug MoAs and can accelerate drug repurposing for personalized medicine. While it is defined for drugs, targets, and diseases triplets, it is a generic model that can be applied to other triplets."
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
publication: "DSAA 2024"
featured: true
date: 2024-08-09T02:33:00.000Z
url_slides: ""
publishDate: "2024-08-09T00:00:00.000Z"
url_poster: ""
url_code: ""
---
Modeling the interactions between drugs, targets, and diseases has significant implications for drug discovery, precision medicine and personalized treatments. Current computational approaches consider pairwise interaction, including drug-target or drug-disease interaction individually. On the other hand, within human metabolic systems, the interaction of drugs with protein targets in cells influences target activities. Moving beyond binary relationships and exploring tighter relationships together as triple is essential to understanding drugs’ mechanism of action (MoAs). Moreover, considering the heterogeneity of drugs, targets, and diseases, along with their distinct characteristics, it is critical to model these complex interactions appropriately. To address these challenges, we develop a novel Heterogeneous Graph Triplet Attention Network (HeTAN) by modeling the interconnectedness of all entities in a heterogeneous graph. HeTAN introduces a novel triplet message passing and triplet-wise attention mechanism within this heterogeneous graph structure. In contrast to focusing only on pairwise attention as the importance of an entity for the other, we define triplet attention to model the importance of pairs for the other in the drug-target-disease triplet prediction problem. We perform extensive experiments on real-world datasets and our results show that HeTAN outperforms several baselines, demonstrating its superior performance in uncovering novel drug-target-disease relationships.
