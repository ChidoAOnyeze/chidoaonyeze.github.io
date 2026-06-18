---
title: "Dynamic Allocation of Public Goods with Approximate Core Equilibria"
authors: "Chido Onyeze, David X. Lin, Siddhartha Banerjee, Eva Tardos"
collection: preprint
category: preprint
external_reference: 'https://arxiv.org/abs/2511.04817'
date: 2025-11-10
venue: 'arXiv preprint arXiv:2511.04817'
publication_year: "2026"

permalink: /publication/dynamic_allocation_of_public_goods
excerpt: 'In this paper, we investigate the problem of allocating a public good in an online setting with strategic agents and give a mechanism that achieves strong fairness and efficiency guarantees at equilibrium.'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
# paperurl: 'http://academicpages.github.io/files/paper1.pdf'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Onyeze, Chido., et al. "Dynamic Allocation of Public Goods with Approximate Core Equilibria." arXiv preprint arXiv:2511.04817 (2025).'
---
We consider the problem of repeatedly allocating multiple shareable public goods that have limited availability in an online setting without the use of money. In our setting, agents have additive values, and the value each agent receives from getting access to the goods in each period is drawn i.i.d. from some joint distribution (that can be arbitrarily correlated between agents). The principal also has global constraints on the set of goods they can select over the horizon, which is represented via a submodular allocation-cost function. Our goal is to select the periods to allocate the good to ensure high value for each group of agents.

We develop mechanisms for this problem using an artificial currency, where we give each agent a budget proportional to their (exogenous) fair share. The correlated value distribution makes this an especially challenging problem, as agents may attempt to free-ride by declaring low valuations for the good when they know other agents have high values-hoping those agents will bear a larger share of the cost of the resource. We offer a black-box reduction from monetary mechanisms for the allocation of a costly excludable public good. We focus on pacing strategies, the natural strategies when using AI agents, where agents report a scaled version of their value to the mechanism. Our main results show that when using a truthful monetary mechanism as our building block, the resulting online mechanism has a focal equilibrium in which each agent plays a pacing strategy whose outcome results in an allocation that is a O(log n)-approximation of the core, where n is the number of agents. Remarkably, we are able to achieve an approximate core solution as a Nash outcome without explicit collaboration or coordination between the agents.