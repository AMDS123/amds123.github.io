---
layout: post
title: "Saliency Guided End-to-End Learning for Weakly Supervised Object Detection"
date: 2017-06-21 07:29:21
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised Detection
author: Baisheng Lai, Xiaojin Gong
mathjax: true
---

* content
{:toc}

##### Abstract
Weakly supervised object detection (WSOD), which is the problem of learning detectors using only image-level labels, has been attracting more and more interest. However, this problem is quite challenging due to the lack of location supervision. To address this issue, this paper integrates saliency into a deep architecture, in which the location in- formation is explored both explicitly and implicitly. Specifically, we select highly confident object pro- posals under the guidance of class-specific saliency maps. The location information, together with semantic and saliency information, of the selected proposals are then used to explicitly supervise the network by imposing two additional losses. Meanwhile, a saliency prediction sub-network is built in the architecture. The prediction results are used to implicitly guide the localization procedure. The entire network is trained end-to-end. Experiments on PASCAL VOC demonstrate that our approach outperforms all state-of-the-arts.

##### Abstract (translated by Google)
弱监督目标检测（WSOD）是仅使用图像级标签学习检测器的问题，已经引起越来越多的关注。但是由于缺乏地点监督，这个问题相当具有挑战性。为了解决这个问题，本文将显着性集成到一个深层次的体系结构中，其中位置信息被明确地和隐含地探索。具体而言，我们在类特定的显着图的指导下选择高度自信的对象提议。所选提议的位置信息连同语义和显着性信息随后被用来通过施加两个额外的损失来明确地监督网络。同时，架构中建立了显着性预测子网络。预测结果被用来隐含地指导本地化程序。整个网络是端到端的训练。 PASCAL VOC的实验表明，我们的方法胜过了所有的艺术。

##### URL
[https://arxiv.org/abs/1706.06768](https://arxiv.org/abs/1706.06768)

