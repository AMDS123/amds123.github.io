---
layout: post
title: "RGB-D Salient Object Detection Based on Discriminative Cross-modal Transfer Learning"
date: 2017-05-31 03:51:50
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection CNN Transfer_Learning Classification Detection
author: Hao Chen, Y.F. Li, Dan Su
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose to utilize Convolutional Neural Networks to boost the performance of depth-induced salient object detection by capturing the high-level representative features for depth modality. We formulate the depth-induced saliency detection as a CNN-based cross-modal transfer problem to bridge the gap between the "data-hungry" nature of CNNs and the unavailability of sufficient labeled training data in depth modality. In the proposed approach, we leverage the auxiliary data from the source modality effectively by training the RGB saliency detection network to obtain the task-specific pre-understanding layers for the target modality. Meanwhile, we exploit the depth-specific information by pre-training a modality classification network that encourages modal-specific representations during the optimizing course. Thus, it could make the feature representations of the RGB and depth modalities as discriminative as possible. These two modules are pre-trained independently and then stitched to initialize and optimize the eventual depth-induced saliency detection model. Experiments demonstrate the effectiveness of the proposed novel pre-training strategy as well as the significant and consistent improvements of the proposed approach over other state-of-the-art methods.

##### Abstract (translated by Google)
在这项工作中，我们建议利用卷积神经网络，通过捕获深度模态的高级代表特征来提高深度诱发的显着物体检测的性能。我们将深度诱发的显着性检测制定为基于CNN的跨模态转移问题，以弥合CNN的“数据饥饿”特性和深度模式中缺乏足够标记的训练数据之间的差距。在提出的方法中，我们通过训练RGB显着性检测网络来有效地利用来源模式的辅助数据，以获得目标模式的任务特定的预先理解层。同时，我们通过预训练优化过程中鼓励特定模态表示的模态分类网络来利用深度特定的信息。因此，可以尽可能区分RGB和深度模式的特征表示。这两个模块是独立预先训练，然后缝合，初始化和优化最终的深度诱发显着性检测模型。实验证明了所提出的新型预训练策略的有效性以及所提出的方法相对于其他现有技术方法的显着和一致的改进。

##### URL
[https://arxiv.org/abs/1703.00122](https://arxiv.org/abs/1703.00122)

##### PDF
[https://arxiv.org/pdf/1703.00122](https://arxiv.org/pdf/1703.00122)

