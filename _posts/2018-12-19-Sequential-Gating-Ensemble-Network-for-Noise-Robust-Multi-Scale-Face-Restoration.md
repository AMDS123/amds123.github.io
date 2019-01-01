---
layout: post
title: "Sequential Gating Ensemble Network for Noise Robust Multi-Scale Face Restoration"
date: 2018-12-19 11:53:40
categories: arXiv_CV
tags: arXiv_CV Adversarial Face Recognition
author: Zhibo Chen, Jianxin Lin, Tiankuang Zhou, Feng Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Face restoration from low resolution and noise is important for applications of face analysis recognition. However, most existing face restoration models omit the multiple scale issues in face restoration problem, which is still not well-solved in research area. In this paper, we propose a Sequential Gating Ensemble Network (SGEN) for multi-scale noise robust face restoration issue. To endow the network with multi-scale representation ability, we first employ the principle of ensemble learning for SGEN network architecture designing. The SGEN aggregates multi-level base-encoders and base-decoders into the network, which enables the network to contain multiple scales of receptive field. Instead of combining these base-en/decoders directly with non-sequential operations, the SGEN takes base-en/decoders from different levels as sequential data. Specifically, it is visualized that SGEN learns to sequentially extract high level information from base-encoders in bottom-up manner and restore low level information from base-decoders in top-down manner. Besides, we propose to realize bottom-up and top-down information combination and selection with Sequential Gating Unit (SGU). The SGU sequentially takes information from two different levels as inputs and decides the output based on one active input. Experiment results on benchmark dataset demonstrate that our SGEN is more effective at multi-scale human face restoration with more image details and less noise than state-of-the-art image restoration models. Further utilizing adversarial training scheme, SGEN also produces more visually preferred results than other models under subjective evaluation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.11834](http://arxiv.org/abs/1812.11834)

##### PDF
[http://arxiv.org/pdf/1812.11834](http://arxiv.org/pdf/1812.11834)

