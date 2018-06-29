---
layout: post
title: "Differentiable Learning-to-Normalize via Switchable Normalization"
date: 2018-06-28 05:55:57
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Image_Classification Classification Detection
author: Ping Luo, Jiamin Ren, Zhanglin Peng
mathjax: true
---

* content
{:toc}

##### Abstract
We address a learning-to-normalize problem by proposing Switchable Normalization (SN), which learns to select different operations for different normalization layers of a deep neural network (DNN). The statistics (means and variances) of SN are computed in three scopes, including a channel, a layer, and a minibatch. SN selects them by learning their importance weights in an end-to-end manner. It has several appealing benefits. First, SN adapts to various network architectures and tasks. Second, it is robust to a wide range of batch sizes, maintaining high performance when small minibatch is presented (e.g. 2 images/GPU). Third, the above benefits of SN are obtained by treating all channels as a group, unlike group normalization that searches the number of groups as the hyper-parameter. Extensive evaluations demonstrate that SN outperforms its counterparts on various challenging problems, such as image classification in ImageNet, object detection and segmentation in COCO, artistic image stylization, and neural architecture search. The code of SN will be made available in https://github.com/switchablenorms/.

##### Abstract (translated by Google)
我们通过提出可切换标准化（SN）来解决学习到标准化问题，其可学习为深度神经网络（DNN）的不同标准化层选择不同的操作。 SN的统计量（均值和差异）在三个范围内计算，包括通道，图层和小批次。 SN通过以端到端的方式学习其重要性权重来选择它们。它有几个吸引人的好处。首先，SN适应各种网络体系结构和任务。其次，它适用于各种批量大小，在提供小型小型批次（例如2个图像/ GPU）时保持高性能。第三，SN的上述优点是通过将所有通道视为一个组来获得的，这与将组数目搜索作为超参数的组标准化不同。大量的评估表明SN在诸如ImageNet中的图像分类，COCO中的对象检测和分割，艺术图像程式化以及神经架构搜索等各种具有挑战性的问题上优于其同行。 SN的代码将在https://github.com/switchablenorms/中提供。

##### URL
[http://arxiv.org/abs/1806.10779](http://arxiv.org/abs/1806.10779)

##### PDF
[http://arxiv.org/pdf/1806.10779](http://arxiv.org/pdf/1806.10779)

