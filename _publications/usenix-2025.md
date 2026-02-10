---
title: "LLMxCPG: Context-Aware Vulnerability Detection Through Code Property Graph-Guided Large Language Models"
collection: publications
category: conferences
permalink: /publication/usenix-2025
# excerpt: 'This paper is about fixing template issue #693.'
date: 2025-07-01
venue: 'The 34th USENIX Security Symposium'
paperurl: 'https://www.usenix.org/system/files/usenixsecurity25-lekssays.pdf'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Authors
======
A. Lekssays, H. Mouhcine, **K. Tran**, T. Yu, I. Khalil


------

Abstract
======

Software vulnerabilities present a persistent security challenge, with over 25,000 new vulnerabilities reported in the Common Vulnerabilities and Exposures (CVE) database in 2024 alone. While deep learning based approaches show promise for vulnerability detection, recent studies reveal critical limitations in terms of accuracy and robustness: accuracy drops by up to 45% on rigorously verified datasets, and performance degrades significantly under simple code modifications. This paper presents LLMxCPG, a novel framework integrating Code Property Graphs (CPG) with Large Language Models (LLM) for robust vulnerability detection. Our CPG-based slice construction technique reduces code size by 67.84 to 90.93% while preserving vulnerability-relevant context. Our approach’s ability to provide a more concise and accurate representation of code snippets enables the analysis of larger code segments, including entire projects. This concise representation is a key factor behind the improved detection capabilities of our method, as it can now identify vulnerabilities that span multiple functions. Empirical evaluation demonstrates LLMxCPG’s effectiveness across verified datasets, achieving 15-40% improvements in F1-score over state-of-the-art baselines. Moreover, LLMxCPG maintains high performance across function-level and multi-function codebases while exhibiting robust detection efficacy under various syntactic code modifications.

