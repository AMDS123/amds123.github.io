---
layout: post
title: "Playing for Data: Ground Truth from Computer Games"
date: 2016-08-07 08:20:14
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Stephan R. Richter, Vibhav Vineet, Stefan Roth, Vladlen Koltun
mathjax: true
---

* content
{:toc}

##### Abstract
Recent progress in computer vision has been driven by high-capacity models trained on large datasets. Unfortunately, creating large datasets with pixel-level labels has been extremely costly due to the amount of human effort required. In this paper, we present an approach to rapidly creating pixel-accurate semantic label maps for images extracted from modern computer games. Although the source code and the internal operation of commercial games are inaccessible, we show that associations between image patches can be reconstructed from the communication between the game and the graphics hardware. This enables rapid propagation of semantic labels within and across images synthesized by the game, with no access to the source code or the content. We validate the presented approach by producing dense pixel-level semantic annotations for 25 thousand images synthesized by a photorealistic open-world computer game. Experiments on semantic segmentation datasets show that using the acquired data to supplement real-world images significantly increases accuracy and that the acquired data enables reducing the amount of hand-labeled real-world data: models trained with game data and just 1/3 of the CamVid training set outperform models trained on the complete CamVid training set.

##### Abstract (translated by Google)
计算机视觉方面的最新进展受到在大型数据集上训练的高容量模型的推动。不幸的是，由于需要大量人力，创建具有像素级标签的大型数据集的成本非常高。在本文中，我们提出了一种快速创建从现代电脑游戏中提取的图像像素准确的语义标签地图的方法。尽管商业游戏的源代码和内部操作是不可访问的，但是我们表明，图像补丁之间的关联可以通过游戏和图形硬件之间的通信来重建。这使得能够快速传播由游戏合成的图像内和之间的语义标签，而不访问源代码或内容。我们验证了所提出的方法，通过产生密集的像素级的语义注释，通过照片级的开放式世界计算机游戏合成的2.5万个图像。语义分割数据集的实验表明，使用获取的数据来补充真实世界的图像显着提高了准确性，并且所获得的数据能够减少手标记的真实世界数据的数量：用游戏数据训练的模型， CamVid训练集优于在完整CamVid训练集上训练的模型。

##### URL
[https://arxiv.org/abs/1608.02192](https://arxiv.org/abs/1608.02192)

##### PDF
[https://arxiv.org/pdf/1608.02192](https://arxiv.org/pdf/1608.02192)

