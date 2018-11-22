---
layout: post
title: "Neural Collective Entity Linking"
date: 2018-11-21 06:00:23
categories: arXiv_CL
tags: arXiv_CL Knowledge Attention CNN
author: Yixin Cao, Lei Hou, Juanzi Li, Zhiyuan Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Entity Linking aims to link entity mentions in texts to knowledge bases, and neural models have achieved recent success in this task. However, most existing methods rely on local contexts to resolve entities independently, which may usually fail due to the data sparsity of local information. To address this issue, we propose a novel neural model for collective entity linking, named as NCEL. NCEL applies Graph Convolutional Network to integrate both local contextual features and global coherence information for entity linking. To improve the computation efficiency, we approximately perform graph convolution on a subgraph of adjacent entity mentions instead of those in the entire text. We further introduce an attention scheme to improve the robustness of NCEL to data noise and train the model on Wikipedia hyperlinks to avoid overfitting and domain bias. In experiments, we evaluate NCEL on five publicly available datasets to verify the linking performance as well as generalization ability. We also conduct an extensive analysis of time complexity, the impact of key modules, and qualitative results, which demonstrate the effectiveness and efficiency of our proposed method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08603](http://arxiv.org/abs/1811.08603)

##### PDF
[http://arxiv.org/pdf/1811.08603](http://arxiv.org/pdf/1811.08603)

