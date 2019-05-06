---
layout: post
title: "IRLAS: Inverse Reinforcement Learning for Architecture Search"
date: 2019-03-11 05:26:56
categories: arXiv_CV
tags: arXiv_CV Knowledge GAN NAS Reinforcement_Learning Inference
author: Minghao Guo, Zhao Zhong, Wei Wu, Dahua Lin, Junjie Yan
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose an inverse reinforcement learning method for architecture search (IRLAS), which trains an agent to learn to search network structures that are topologically inspired by human-designed network. Most existing architecture search approaches totally neglect the topological characteristics of architectures, which results in complicated architecture with a high inference latency. Motivated by the fact that human-designed networks are elegant in topology with a fast inference speed, we propose a mirror stimuli function inspired by biological cognition theory to extract the abstract topological knowledge of an expert human-design network (ResNeXt). To avoid raising a too strong prior over the search space, we introduce inverse reinforcement learning to train the mirror stimuli function and exploit it as a heuristic guidance for architecture search, easily generalized to different architecture search algorithms. On CIFAR-10, the best architecture searched by our proposed IRLAS achieves 2.60% error rate. For ImageNet mobile setting, our model achieves a state-of-the-art top-1 accuracy 75.28%, while being 2~4x faster than most auto-generated architectures. A fast version of this model achieves 10% faster than MobileNetV2, while maintaining a higher accuracy.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1812.05285](https://arxiv.org/abs/1812.05285)

##### PDF
[https://arxiv.org/pdf/1812.05285](https://arxiv.org/pdf/1812.05285)

