---
layout: post
title: "Explore, Propose, and Assemble: An Interpretable Model for Multi-Hop Reading Comprehension"
date: 2019-06-12 15:26:59
categories: arXiv_AI
tags: arXiv_AI
author: Yichen Jiang, Nitish Joshi, Yen-Chun Chen, Mohit Bansal
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-hop reading comprehension requires the model to explore and connect relevant information from multiple sentences/documents in order to answer the question about the context. To achieve this, we propose an interpretable 3-module system called Explore-Propose-Assemble reader (EPAr). First, the Document Explorer iteratively selects relevant documents and represents divergent reasoning chains in a tree structure so as to allow assimilating information from all chains. The Answer Proposer then proposes an answer from every root-to-leaf path in the reasoning tree. Finally, the Evidence Assembler extracts a key sentence containing the proposed answer from every path and combines them to predict the final answer. Intuitively, EPAr approximates the coarse-to-fine-grained comprehension behavior of human readers when facing multiple long documents. We jointly optimize our 3 modules by minimizing the sum of losses from each stage conditioned on the previous stage's output. On two multi-hop reading comprehension datasets WikiHop and MedHop, our EPAr model achieves significant improvements over the baseline and competitive results compared to the state-of-the-art model. We also present multiple reasoning-chain-recovery tests and ablation studies to demonstrate our system's ability to perform interpretable and accurate reasoning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.05210](http://arxiv.org/abs/1906.05210)

##### PDF
[http://arxiv.org/pdf/1906.05210](http://arxiv.org/pdf/1906.05210)

