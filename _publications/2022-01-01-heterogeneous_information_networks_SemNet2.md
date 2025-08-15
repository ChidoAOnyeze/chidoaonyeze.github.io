---
title: "Optimizations for computing relatedness in biomedical heterogeneous information networks: SemNet 2.0"
authors: "Anna Kirkpatrick, Chido Onyeze, David Kartchner, Stephen Allegri, Davi Nakajima An, Kevin McCoy, Evie Davalbhakta, Cassie S Mitchell"
collection: publications
category: manuscripts
external_reference: 'https://www.mdpi.com/2504-2289/6/1/27'
date: 2022-01-01
venue: 'Big Data and Cognitive Computing'
publication_year: "2022"

permalink: /publication/heterogeneous_information_networks_SemNet2
excerpt: 'In this paper, we improve on the SemNet, a tool for analyzing simitarity in information networks, using techniques from randomizes algorithms to improve its efficacy and efficiency.' 

#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
#paperurl: 'http://academicpages.github.io/files/paper1.pdf'
#bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Kirkpatrick, Anna, et al. "Optimizations for computing relatedness in biomedical heterogeneous information networks: SemNet 2.0." Big data and cognitive computing 6.1 (2022): 27.'
---

Literature-based discovery (LBD) summarizes information and generates insight from large text corpuses. The SemNet framework utilizes a large heterogeneous information network or “knowledge graph” of nodes and edges to compute relatedness and rank concepts pertinent to a user-specified target. SemNet provides a way to perform multi-factorial and multi-scalar analysis of complex disease etiology and therapeutic identification using the 33+ million articles in PubMed. The present work improves the efficacy and efficiency of LBD for end users by augmenting SemNet to create SemNet 2.0. A custom Python data structure replaced reliance on Neo4j to improve knowledge graph query times by several orders of magnitude. Additionally, two randomized algorithms were built to optimize the HeteSim metric calculation for computing metapath similarity. The unsupervised learning algorithm for rank aggregation (ULARA), which ranks concepts with respect to the user-specified target, was reconstructed using derived mathematical proofs of correctness and probabilistic performance guarantees for optimization. The upgraded ULARA is generalizable to other rank aggregation problems outside of SemNet. In summary, SemNet 2.0 is a comprehensive open-source software for significantly faster, more effective, and user-friendly means of automated biomedical LBD. An example case is performed to rank relationships between Alzheimer’s disease and metabolic co-morbidities.
