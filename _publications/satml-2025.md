---
title: "FairDP: Achieving Fairness Certification with Differential Privacy"
collection: publications
category: conferences
permalink: /publication/satml-2025
# excerpt: 'This paper is about fixing template issue #693.'
date: 2025-04-01
venue: 'IEEE Conference on Secure and Trustworthy Machine Learning (SaTML)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10992461'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Authors
======
**K. Tran**, F. Fioretto, I. Khalil, M. Thai, T.X.L. Phan N.H. Phan


------

Abstract
======

This paper introduces FairDP, a novel training mechanism designed to provide group fairness certification for the trained model's decisions, along with a differential privacy (DP) guarantee to protect training data. The key idea of FairDP is to train models for distinct individual groups independently, add noise to each group's gradient for data privacy protection, and progressively integrate knowledge from group models to formulate a comprehensive model that balances privacy, utility, and fairness in downstream tasks. By doing so, FairDP ensures equal contribution from each group while gaining control over the amount of DP-preserving noise added to each group's contribution. To provide fairness certification, FairDP leverages the DP-preserving noise to statistically quantify and bound fairness metrics. An extensive theoretical and empirical analysis using benchmark datasets validates the efficacy of FairDP and improved trade-offs between model utility, privacy, and fairness compared with existing methods. Our empirical results indicate that FairDP can improve fairness metrics by more than 65% on average while attaining marginal utility drop (less than 4% on average) under a rigorous DP-preservation across benchmark datasets compared with existing baselines.

