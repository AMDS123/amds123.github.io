---
layout: post
title: "Deep Scene Text Detection with Connected Component Proposals"
date: 2017-08-17 04:44:03
categories: arXiv_CV
tags: arXiv_CV CNN Classification Detection
author: Fan Jiang, Zhihui Hao, Xinran Liu
mathjax: true
---

* content
{:toc}

##### Abstract
A growing demand for natural-scene text detection has been witnessed by the computer vision community since text information plays a significant role in scene understanding and image indexing. Deep neural networks are being used due to their strong capabilities of pixel-wise classification or word localization, similar to being used in common vision problems. In this paper, we present a novel two-task network with integrating bottom and top cues. The first task aims to predict a pixel-by-pixel labeling and based on which, word proposals are generated with a canonical connected component analysis. The second task aims to output a bundle of character candidates used later to verify the word proposals. The two sub-networks share base convolutional features and moreover, we present a new loss to strengthen the interaction between them. We evaluate the proposed network on public benchmark datasets and show it can detect arbitrary-orientation scene text with a finer output boundary. In ICDAR 2013 text localization task, we achieve the state-of-the-art performance with an F-score of 0.919 and a much better recall of 0.915.

##### Abstract (translated by Google)
由于文本信息在场景理解和图像索引中起着重要的作用，计算机视觉社区已经看到了对自然场景文本检测的需求日益增长。深度神经网络由于其强大的逐像素分类或词语定位功能而被使用，类似于常见的视力问题。在本文中，我们提出了一个集成了底线和顶线的新型双任务网络。第一项任务旨在预测一个逐像素的标签，并在此基础上，使用典型连通分量分析生成文字提议。第二项任务的目的是输出一批字符候选人以后用来验证单词建议。这两个子网共享基卷积特征，而且为了加强它们之间的交互，我们提出了新的损失。我们评估提出的公共基准数据集的网络，并显示它可以检测任意方向的场景文本具有更精细的输出边界。在ICDAR 2013文本本地化任务中，我们实现了最新的性能，F评分为0.919，召回为0.915。

##### URL
[https://arxiv.org/abs/1708.05133](https://arxiv.org/abs/1708.05133)

##### PDF
[https://arxiv.org/pdf/1708.05133](https://arxiv.org/pdf/1708.05133)

