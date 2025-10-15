---
title: "MCL-DMD: Multi-modal Contrastive Learning for
Drug-Microbe-Disease Association Prediction"
authors:
  - Niecia Say
  - Farhan Tanvir
  - Moctar Keita
  - Lilia Chebbah
  - Muhammad Ifte Khairul Islam and Esra Akbas
author_notes: []
publication_short: "In BCB 2025"
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
publication: "BCB 2025"
featured: true
date: 2025-10-14T02:33:00.000Z
url_slides: ""
publishDate: "2025-10-14T00:00:00.000Z"
url_poster: ""
url_code: ""
---
Modeling interactions between drugs, microbes, and diseases is
essential for advancing drug discovery and precision medicine. Although most existing computational approaches focus on pairwise
association prediction, such as drug–microbe or microbe–disease associations, they often overlook the interdependencies among all
three entities. In real-world biomedical systems, drug–microbiome interactions can modulate treatment efficacy, influence toxicity, and shape disease trajectories. Moving beyond binary relationships to
explore triplet-level associations is essential for uncovering drugs’
mechanisms of action (MoAs). Recent advances in Graph Neural
Networks (GNNs) have significantly improved the modeling of complex molecular structures, enabling more accurate property
prediction. However, molecular and biomedical data extend beyond graph structures, encompassing diverse modalities such as molecular sequences, taxonomic hierarchies, and ontological descriptors— features that GNNs cannot fully capture. To address these limitations, we propose MCL-DMD (Multi-modal Contrastive Learning for
Drug-Microbe-Disease Association Prediction), a novel framework that combines heterogeneous graph modeling with domain-specific
biomedical knowledge. MCL-DMD employs HeTAN (Heterogeneous Triple Attention Network) to model the interconnectedness of all
entities in a heterogeneous graph and augments it with a biomedical knowledge encoder that leverages SMILES representations,
microbial taxonomies, and MeSH disease descriptors. Through multi-modal contrastive learning, MCL-DMD aligns cross-modal representations to improve semantic consistency and predictive robustness. Experimental results demonstrate that MCL-DMD significantly outperforms state-of-the-art baselines in both classification and
ranking metrics, offering a powerful framework to uncover novel drug–microbe–disease associations.
