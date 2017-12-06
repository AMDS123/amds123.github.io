---
layout: post
title: "Object Detection Using Deep CNNs Trained on Synthetic Images"
date: 2017-09-18 11:42:06
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Param S. Rajpura, Hristo Bojinov, Ravi S. Hegde
mathjax: true
---

* content
{:toc}

##### Abstract
The need for large annotated image datasets for training Convolutional Neural Networks (CNNs) has been a significant impediment for their adoption in computer vision applications. We show that with transfer learning an effective object detector can be trained almost entirely on synthetically rendered datasets. We apply this strategy for detecting pack- aged food products clustered in refrigerator scenes. Our CNN trained only with 4000 synthetic images achieves mean average precision (mAP) of 24 on a test set with 55 distinct products as objects of interest and 17 distractor objects. A further increase of 12% in the mAP is obtained by adding only 400 real images to these 4000 synthetic images in the training set. A high degree of photorealism in the synthetic images was not essential in achieving this performance. We analyze factors like training data set size and 3D model dictionary size for their influence on detection performance. Additionally, training strategies like fine-tuning with selected layers and early stopping which affect transfer learning from synthetic scenes to real scenes are explored. Training CNNs with synthetic datasets is a novel application of high-performance computing and a promising approach for object detection applications in domains where there is a dearth of large annotated image data.

##### Abstract (translated by Google)
用于训练卷积神经网络（CNN）的大型注释图像数据集的需求一直是其在计算机视觉应用中被采用的重要障碍。我们证明，使用传输学习，一个有效的对象检测器几乎可以完全在合成渲染的数据集上进行训练。我们将这一策略应用于检测集群在冰箱场景中的包装食品。我们的CNN训练只有4000个合成图像，在55个不同产品作为感兴趣的对象和17个干扰对象的测试集上达到24的平均平均精度（mAP）。通过在训练集中的这4000个合成图像中仅添加400个真实图像来获得mAP的进一步增加12％。在合成图像中高度的真实感并不是实现这种性能所必需的。我们分析了训练数据集大小和3D模型字典大小等因素对检测性能的影响。此外，还探索了如何对所选图层进行微调以及如何早期停止这些影响从合成场景到真实场景的转换学习的培训策略。使用合成数据集对CNN进行培训是高性能计算的一种新颖应用，也是在大量注释图像数据缺乏的领域中用于对象检测应用的一种有前途的方法。

##### URL
[https://arxiv.org/abs/1706.06782](https://arxiv.org/abs/1706.06782)

