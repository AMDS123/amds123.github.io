---
layout: post
title: "AutoLoc: Weakly-supervised Temporal Action Localization"
date: 2018-07-22 18:14:45
categories: arXiv_CV
tags: arXiv_CV
author: Zheng Shou, Hang Gao, Lei Zhang, Kazuyuki Miyazawa, Shih-Fu Chang
mathjax: true
---

* content
{:toc}

##### Abstract
Temporal Action Localization (TAL) in untrimmed video is important for many applications. But it is very expensive to annotate the segment-level ground truth (action class and temporal boundary). This raises the interest of addressing TAL with weak supervision, namely only video-level annotations are available during training). However, the state-of-the-art weakly-supervised TAL methods only focus on generating good Class Activation Sequence (CAS) over time but conduct simple thresholding on CAS to localize actions. In this paper, we first develop a novel weakly-supervised TAL framework called AutoLoc to directly predict the temporal boundary of each action instance. We propose a novel Outer-Inner-Contrastive (OIC) loss to automatically discover the needed segment-level supervision for training such a boundary predictor. Our method achieves dramatically improved performance: under the IoU threshold 0.5, our method improves mAP on THUMOS'14 from 13.7% to 21.2% and mAP on ActivityNet from 7.4% to 27.3%. It is also very encouraging to see that our weakly-supervised method achieves comparable results with some fully-supervised methods.

##### Abstract (translated by Google)
未修剪视频中的时间动作定位（TAL）对于许多应用来说很重要。但是，注释段级基础事实（动作类和时间边界）是非常昂贵的。这提高了在弱监督下解决TAL的兴趣，即在训练期间只能提供视频级注释。然而，最先进的弱监督TAL方法仅关注于随着时间的推移产生良好的类激活序列（CAS），而是对CAS进行简单的阈值处理以定位动作。在本文中，我们首先开发一种新的弱监督TAL框架，称为AutoLoc，以直接预测每个动作实例的时间边界。我们提出了一种新颖的外部内部对比（OIC）损失，以自动发现训练这种边界预测器所需的分段级监督。我们的方法实现了显着改善的性能：在IoU阈值0.5下，我们的方法将THUMOS'14上的mAP从13.7％提高到21.2％，并将ActivityNet上的mAP从7.4％提高到27.3％。看到我们的弱监督方法与一些完全监督的方法取得了可比较的结果，这也是非常令人鼓舞的。

##### URL
[http://arxiv.org/abs/1807.08333](http://arxiv.org/abs/1807.08333)

##### PDF
[http://arxiv.org/pdf/1807.08333](http://arxiv.org/pdf/1807.08333)

