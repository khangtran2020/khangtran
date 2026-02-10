---
title: "Heterogeneous Randomized Response for Differential Privacy in Graph Neural Networks"
collection: publications
category: conferences
permalink: /publication/bigdata-2022
# excerpt: 'This paper is about fixing template issue #693.'
date: 2022-12-01
venue: 'IEEE International Conference on Big Data (BigData)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10020501'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Authors
======
**K. Tran**, P. Lai, N.H. Phan, I. Khalil, Y. Ma, A. Khreishah, M. Thai, X. Wu


------

Abstract
======

Graph neural networks (GNNs) are susceptible to privacy inference attacks (PIAS) given their ability to learn joint representation from features and edges among nodes in graph data. To prevent privacy leakages in GNNs, we propose a novel heterogeneous randomized response (HeteroRR) mechanism to protect nodes’ features and edges against PIAS under differential privacy (DP) guarantees, without an undue cost of data and model utility in training GNNs. Our idea is to balance the importance and sensitivity of nodes’ features and edges in redistributing the privacy budgets since some features and edges are more sensitive or important to the model utility than others. As a result, we derive significantly better randomization probabilities and tighter error bounds at both levels of nodes’ features and edges departing from existing approaches, thus enabling us to maintain high data utility for training GNNs. An extensive theoretical and empirical analysis using benchmark datasets shows that HeteroRR significantly outperforms various baselines in terms of model utility under rigorous privacy protection for both nodes’ features and edges. That enables us to defend PIAs in DP-preserving GNNs effectively.