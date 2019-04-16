---
layout: post
title: "Collaborative Memory Network for Recommendation Systems"
date: 2018-06-21 00:02:12
categories: arXiv_CV
tags: arXiv_CV Attention Deep_Learning Relation Memory_Networks Recommendation
author: Travis Ebesu, Bin Shen, Yi Fang
mathjax: true
---

* content
{:toc}

##### Abstract
Recommendation systems play a vital role to keep users engaged with personalized content in modern online platforms. Deep learning has revolutionized many research fields and there is a recent surge of interest in applying it to collaborative filtering (CF). However, existing methods compose deep learning architectures with the latent factor model ignoring a major class of CF models, neighborhood or memory-based approaches. We propose Collaborative Memory Networks (CMN), a deep architecture to unify the two classes of CF models capitalizing on the strengths of the global structure of latent factor model and local neighborhood-based structure in a nonlinear fashion. Motivated by the success of Memory Networks, we fuse a memory component and neural attention mechanism as the neighborhood component. The associative addressing scheme with the user and item memories in the memory module encodes complex user-item relations coupled with the neural attention mechanism to learn a user-item specific neighborhood. Finally, the output module jointly exploits the neighborhood with the user and item memories to produce the ranking score. Stacking multiple memory modules together yield deeper architectures capturing increasingly complex user-item relations. Furthermore, we show strong connections between CMN components, memory networks and the three classes of CF models. Comprehensive experimental results demonstrate the effectiveness of CMN on three public datasets outperforming competitive baselines. Qualitative visualization of the attention weights provide insight into the model's recommendation process and suggest the presence of higher order interactions.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1804.10862](https://arxiv.org/abs/1804.10862)

##### PDF
[https://arxiv.org/pdf/1804.10862](https://arxiv.org/pdf/1804.10862)

