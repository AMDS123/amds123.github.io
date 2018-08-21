---
layout: post
title: "Distractor-aware Siamese Networks for Visual Object Tracking"
date: 2018-08-18 06:38:10
categories: arXiv_CV
tags: arXiv_CV Attention Tracking Embedding Object_Tracking Inference
author: Zheng Zhu, Qiang Wang, Bo Li, Wei Wu, Junjie Yan, Weiming Hu
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, Siamese networks have drawn great attention in visual tracking community because of their balanced accuracy and speed. However, features used in most Siamese tracking approaches can only discriminate foreground from the non-semantic backgrounds. The semantic backgrounds are always considered as distractors, which hinders the robustness of Siamese trackers. In this paper, we focus on learning distractor-aware Siamese networks for accurate and long-term tracking. To this end, features used in traditional Siamese trackers are analyzed at first. We observe that the imbalanced distribution of training data makes the learned features less discriminative. During the off-line training phase, an effective sampling strategy is introduced to control this distribution and make the model focus on the semantic distractors. During inference, a novel distractor-aware module is designed to perform incremental learning, which can effectively transfer the general embedding to the current video domain. In addition, we extend the proposed approach for long-term tracking by introducing a simple yet effective local-to-global search region strategy. Extensive experiments on benchmarks show that our approach significantly outperforms the state-of-the-arts, yielding 9.6% relative gain in VOT2016 dataset and 35.9% relative gain in UAV20L dataset. The proposed tracker can perform at 160 FPS on short-term benchmarks and 110 FPS on long-term benchmarks.

##### Abstract (translated by Google)
最近，由于其平衡的准确性和速度，暹罗网络在视觉跟踪社区中引起了极大的关注。但是，大多数Siamese跟踪方法中使用的功能只能区分前景和非语义背景。语义背景总是被视为干扰者，这阻碍了暹罗追踪者的健壮性。在本文中，我们专注于学习干扰器感知的Siamese网络，以实现准确和长期的跟踪。为此，首先分析传统暹罗追踪器中使用的功能。我们观察到训练数据的不均衡分布使得学习的特征不那么具有辨别力。在离线训练阶段，引入有效的采样策略来控制这种分布，并使模型专注于语义干扰。在推理期间，设计了一种新颖的干扰物感知模块来执行增量学习，其可以有效地将一般嵌入转移到当前视频域。此外，我们通过引入简单而有效的本地到全球搜索区域战略，扩展了建议的长期跟踪方法。基准测试的广泛实验表明，我们的方法明显优于现有技术，VOT2016数据集的相对增益为9.6％，UAV20L数据集的相对增益为35.9％。建议的跟踪器可以在短期基准测试中以160 FPS执行，在长期基准测试中可以执行110 FPS。

##### URL
[http://arxiv.org/abs/1808.06048](http://arxiv.org/abs/1808.06048)

##### PDF
[http://arxiv.org/pdf/1808.06048](http://arxiv.org/pdf/1808.06048)

