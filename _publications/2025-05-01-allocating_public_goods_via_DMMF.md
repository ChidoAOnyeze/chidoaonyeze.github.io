---
title: "Allocating Public Goods via Dynamic Max-Min Fairness: Long-Run Behavior and Competitive Equilibria"
authors: "Chido Onyeze, Siddhartha Banerjee, Giannis Fikioris, Eva Tardos"
collection: publications
category: manuscripts
external_reference: 'https://dl.acm.org/doi/abs/10.1145/3711695'
date: 2025-05-01
venue: 'Proceedings of the ACM on Measurement and Analysis of Computing Systems'
publication_year: "2025"

permalink: /publication/allocating_public_goods_via_DMMF
excerpt: 'In this paper, we investigate equilibrium outcomes under the Dynamic max-min fair allocation mechanism.'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
# paperurl: 'http://academicpages.github.io/files/paper1.pdf'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Onyeze, Chido, et al. "Allocating Public Goods via Dynamic Max-Min Fairness: Long-Run Behavior and Competitive Equilibria." Proceedings of the ACM on Measurement and Analysis of Computing Systems 9.1 (2025): 1-45.'
---
Dynamic max-min fair allocation (DMMF) is a simple and popular mechanism for the repeated allocation of a shared resource among competing agents: in each round, each agent can choose to request or not for the resource, which is then allocated to the requesting agent with the least number of allocations received till then. Recent work has shown that under DMMF, a simple threshold-based request policy enjoys surprisingly strong robustness properties, wherein each agent can realize a significant fraction of her optimal utility irrespective of how other agents' behave. While this goes some way in mitigating the possibility of a 'tragedy of the commons' outcome, the robust policies require that an agent defend against arbitrary (possibly adversarial) behavior by other agents. This however may be far from optimal compared to real world settings, where other agents are selfish optimizers rather than adversaries. Therefore, robust guarantees give no insight on how agents behave in an equilibrium, and whether outcomes are improved under one.

Our work aims to bridge this gap by studying the existence and properties of equilibria under DMMF. To this end, we first show that despite the strong robustness guarantees of the threshold based strategies, no Nash equilibrium exists when agents participate in DMMF, each using some fixed threshold-based policy. On the positive side, however, we show that for the symmetric case, a simple data-driven request policy guarantees that no agent benefits from deviating to a different fixed threshold policy. In our proposed policy agents aim to match the historical allocation rate with a vanishing drift towards the rate optimizing overall welfare for all users. Furthermore, the resulting equilibrium outcome can be significantly better compared to what follows from the robustness guarantees.

Our results are built on a complete characterization of the steady-state distribution under DMMF, as well as new techniques for analyzing strategic agent outcomes under dynamic allocation mechanisms; we hope these may prove of independent interest in related problems.