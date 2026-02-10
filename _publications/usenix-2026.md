---
title: "NOIR: Privacy-Preserving Generation of Code with Open-Source LLMs"
collection: publications
category: conferences
permalink: /publication/usenix-2026
# excerpt: 'This paper is about fixing template issue #693.'
date: 2026-01-01
venue: 'The 35th USENIX Security Symposium'
paperurl: 'https://arxiv.org/pdf/2601.16354'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Authors
======
K. Nguyen\*, K. Ton\*, N.H. Phan, I. Khalil, K. Tran\*, C. Borcea, R. Jin, A. Khreishah, M. Thai (\* Equal Contribution)


------

Abstract
======

Although boosting software development performance, large language model (LLM)-powered code generation introduces intellectual property and data security risks rooted in the fact that a service provider (cloud) observes a client's prompts and generated code, which can be proprietary in commercial systems. To mitigate this problem, we propose NOIR, the first framework to protect the client's prompts and generated code from the cloud. NOIR uses an encoder and a decoder at the client to encode and send the prompts' embeddings to the cloud to get enriched embeddings from the LLM, which are then decoded to generate the code locally at the client. Since the cloud can use the embeddings to infer the prompt and the generated code, NOIR introduces a new mechanism to achieve indistinguishability, a local differential privacy protection at the token embedding level, in the vocabulary used in the prompts and code, and a data-independent and randomized tokenizer on the client side. These components effectively defend against reconstruction and frequency analysis attacks by an honest-but-curious cloud. Extensive analysis and results using open-source LLMs show that NOIR significantly outperforms existing baselines on benchmarks, including the Evalplus (MBPP and HumanEval, Pass@1 of 76.7 and 77.4), and BigCodeBench (Pass@1 of 38.7, only a 1.77% drop from the original LLM) under strong privacy against attacks.

