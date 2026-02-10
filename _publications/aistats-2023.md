---
title: "Active Membership Inference Attack under Local Differential Privacy in Federated Learning"
collection: publications
category: conferences
permalink: /publication/aistats-2023
# excerpt: 'This paper is about fixing template issue #693.'
date: 2023-12-01
venue: 'Proceedings of The 26th International Conference on Artificial Intelligence and Statistics'
paperurl: 'https://proceedings.mlr.press/v206/nguyen23e.html'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Authors
======
T. Nguyen, P. Lai, **K. Tran**, N.H. Phan, M. Thai,


------

Abstract
======

Federated learning (FL) was originally regarded as a framework for collaborative learning among clients with data privacy protection through a coordinating server. In this paper, we propose a new active membership inference (AMI) attack carried out by a dishonest server in FL. In AMI attacks, the server crafts and embeds malicious parameters into global models to effectively infer whether a target data sample is included in a client’s private training data or not. By exploiting the correlation among data features through a non-linear decision boundary, AMI attacks with a certified guarantee of success can achieve severely high success rates under rigorous local differential privacy (LDP) protection; thereby exposing clients’ training data to significant privacy risk. Theoretical and experimental results on several benchmark datasets show that adding sufficient privacy-preserving noise to prevent our attack would significantly damage FL’s model utility.


