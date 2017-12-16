---
layout: post
title: "Efficient Action Detection in Untrimmed Videos via Multi-Task Learning"
date: 2017-04-04 17:49:19
categories: arXiv_CV
tags: arXiv_CV Summarization Action_Recognition Detection Recognition
author: Yi Zhu, Shawn Newsam
mathjax: true
---

* content
{:toc}

##### Abstract
This paper studies the joint learning of action recognition and temporal localization in long, untrimmed videos. We employ a multi-task learning framework that performs the three highly related steps of action proposal, action recognition, and action localization refinement in parallel instead of the standard sequential pipeline that performs the steps in order. We develop a novel temporal actionness regression module that estimates what proportion of a clip contains action. We use it for temporal localization but it could have other applications like video retrieval, surveillance, summarization, etc. We also introduce random shear augmentation during training to simulate viewpoint change. We evaluate our framework on three popular video benchmarks. Results demonstrate that our joint model is efficient in terms of storage and computation in that we do not need to compute and cache dense trajectory features, and that it is several times faster than its sequential ConvNets counterpart. Yet, despite being more efficient, it outperforms state-of-the-art methods with respect to accuracy.

##### Abstract (translated by Google)
本文研究了动作识别和时间定位在长时间未修剪的视频中的联合学习。我们采用多任务学习框架，并行执行三个高度相关的行动建议，行动识别和行动本地化细化的步骤，而不是按顺序执行步骤的标准顺序管线。我们开发了一种新颖的时间动作回归模块，用于估计剪辑包含动作的比例。我们使用它来进行时间定位，但它可能有其他应用程序，如视频检索，监视，汇总等。我们还介绍了在训练过程中随机剪切增强来模拟视点变化。我们评估我们的三个流行的视频基准框架。结果表明，我们的联合模型在存储和计算方面是高效的，因为我们不需要计算和缓存密集的轨迹特征，而且它比它的顺序ConvNets对应物快几倍。然而，尽管效率更高，但在准确性方面却超越了最先进的方法。

##### URL
[https://arxiv.org/abs/1612.07403](https://arxiv.org/abs/1612.07403)

##### PDF
[https://arxiv.org/pdf/1612.07403](https://arxiv.org/pdf/1612.07403)

