---
layout: post
title: "Learning Latent Spatio-Temporal Compositional Model for Human Action Recognition"
date: 2015-02-01 13:49:31
categories: arXiv_CV
tags: arXiv_CV Weakly_Supervised Action_Recognition Optimization Recognition
author: Xiaodan Liang, Liang Lin, Liangliang Cao
mathjax: true
---

* content
{:toc}

##### Abstract
Action recognition is an important problem in multimedia understanding. This paper addresses this problem by building an expressive compositional action model. We model one action instance in the video with an ensemble of spatio-temporal compositions: a number of discrete temporal anchor frames, each of which is further decomposed to a layout of deformable parts. In this way, our model can identify a Spatio-Temporal And-Or Graph (STAOG) to represent the latent structure of actions e.g. triple jumping, swinging and high jumping. The STAOG model comprises four layers: (i) a batch of leaf-nodes in bottom for detecting various action parts within video patches; (ii) the or-nodes over bottom, i.e. switch variables to activate their children leaf-nodes for structural variability; (iii) the and-nodes within an anchor frame for verifying spatial composition; and (iv) the root-node at top for aggregating scores over temporal anchor frames. Moreover, the contextual interactions are defined between leaf-nodes in both spatial and temporal domains. For model training, we develop a novel weakly supervised learning algorithm which iteratively determines the structural configuration (e.g. the production of leaf-nodes associated with the or-nodes) along with the optimization of multi-layer parameters. By fully exploiting spatio-temporal compositions and interactions, our approach handles well large intra-class action variance (e.g. different views, individual appearances, spatio-temporal structures). The experimental results on the challenging databases demonstrate superior performance of our approach over other competing methods.

##### Abstract (translated by Google)
行为识别是多媒体理解中的一个重要问题。本文通过构建表达性构图动作模型来解决这个问题。我们在视频中用一个时空组合来模拟一个动作实例：一些离散的时间锚帧，每个时间锚帧被进一步分解成可变形部分的布局。以这种方式，我们的模型可以识别时空 - 或图（STAOG）来表示动作的潜在结构。三重跳跃，摆动和高跳跃。 STAOG模型包括四个层次：（i）底部的一批叶节点，用于检测视频片中的各个动作部分; （ii）底部的节点，即用于激活其子叶节点的结构变化的开关变量; （iii）锚帧中的和节点，用于验证空间组成;和（iv）顶部的根节点用于汇总时间锚帧上的分数。而且，上下文交互被定义在空间和时间域中的叶节点之间。对于模型训练，我们开发了一种新颖的弱监督学习算法，该算法迭代地确定结构配置（例如与或节点相关联的叶节点的产生）以及多层参数的优化。通过充分利用时空组合和相互作用，我们的方法处理了很大的类内行为变化（例如不同的视图，单独的外观，时空结构）。在具有挑战性的数据库上的实验结果证明了我们的方法优于其他竞争方法的优越性能。

##### URL
[https://arxiv.org/abs/1502.00258](https://arxiv.org/abs/1502.00258)

##### PDF
[https://arxiv.org/pdf/1502.00258](https://arxiv.org/pdf/1502.00258)

