---
layout: post
title: "Video Representation Learning Using Discriminative Pooling"
date: 2018-03-26 18:32:04
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Represenation_Learning Prediction Recognition
author: Jue Wang, Anoop Cherian, Fatih Porikli, Stephen Gould
mathjax: true
---

* content
{:toc}

##### Abstract
Popular deep models for action recognition in videos generate independent predictions for short clips, which are then pooled heuristically to assign an action label to the full video segment. As not all frames may characterize the underlying action---indeed, many are common across multiple actions---pooling schemes that impose equal importance on all frames might be unfavorable. In an attempt to tackle this problem, we propose discriminative pooling, based on the notion that among the deep features generated on all short clips, there is at least one that characterizes the action. To this end, we learn a (nonlinear) hyperplane that separates this unknown, yet discriminative, feature from the rest. Applying multiple instance learning in a large-margin setup, we use the parameters of this separating hyperplane as a descriptor for the full video segment. Since these parameters are directly related to the support vectors in a max-margin framework, they serve as robust representations for pooling of the features. We formulate a joint objective and an efficient solver that learns these hyperplanes per video and the corresponding action classifiers over the hyperplanes. Our pooling scheme is end-to-end trainable within a deep framework. We report results from experiments on three benchmark datasets spanning a variety of challenges and demonstrate state-of-the-art performance across these tasks.

##### Abstract (translated by Google)
流行的视频动作识别深度模型为短片生成独立预测，然后将其合并为启发式分配动作标签至完整视频片段。由于不是所有的框架都可能表现出潜在的行为 - 事实上，许多行为在多个行动中都很常见 - 对所有框架施加同等重要性的集合计划可能是不利的。为了解决这个问题，我们提出了歧视性池化，基于这样一个概念，即在所有短片上生成的深层特征中，至少有一个特征描述了该行为。为此，我们学习了一个（非线性）超平面，它将这个未知的但有区别的特征与其他特征分开。我们使用这个分离超平面的参数作为整个视频片段的描述符，在大容量设置中应用多个实例学习。由于这些参数与最大边界框架中的支持向量直接相关，因此它们可用作特征汇集的健壮表示。我们制定了一个联合目标和一个高效的求解器，可以学习每个视频的这些超平面以及超平面上的相应动作分类器。我们的合并计划是在深层框架内进行端对端培训。我们在三个基准数据集上报告实验结果，涵盖各种挑战，并展示这些任务的最新性能。

##### URL
[https://arxiv.org/abs/1803.10628](https://arxiv.org/abs/1803.10628)

##### PDF
[https://arxiv.org/pdf/1803.10628](https://arxiv.org/pdf/1803.10628)

