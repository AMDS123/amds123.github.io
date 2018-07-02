---
layout: post
title: "Action Recognition for Depth Video using Multi-view Dynamic Images"
date: 2018-06-29 05:27:26
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Recognition
author: Yang Xiao, Jun Chen, Zhiguo Cao, Joey Tianyi Zhou, Xiang Bai
mathjax: true
---

* content
{:toc}

##### Abstract
Dynamic image is the recently emerged action representation paradigm able to compactly capture the temporal evolution, especially in context of deep Convolutional Neural Network(CNN). Inspired by its preliminary success towards RGB videos, we propose its extension to the depth domain. To better exploit the 3D characteristics of depth video to leverage the performance, multi-view dynamic image is proposed by us. In particular, the raw depth video will be densely projected onto the different imaging view-points by rotating the virtual camera around the specific instances within the 3D space. Dynamic images are then extracted from the yielded multi-view depth videos respectively to constitute the multi-view dynamic images. In this way, more view-tolerant representative information can be involved in multiview dynamic images than the single-view counterpart. A novel CNN learning model is consequently proposed to execute feature learning on multi-view dynamic images. The dynamic images from different views will share the same convolutional layers, but with the different fully-connected layers. This model aims to enhance the tuning of shallow convolutional layers by alleviating gradient vanishing. Furthermore, to address the effect of spatial variation an action proposal method based on faster R-CNN is proposed. The dynamic images will be extracted only from the action proposal regions. In experiments, our approach can achieve the state-of-the-art performance on 3 challenging datasets (i.e., NTU RGB-D, Northwestern-UCLA and UWA3DII).

##### Abstract (translated by Google)
动态图像是最近出现的动作表示范式，能够紧凑地捕捉时间演变，特别是在深度卷积神经网络（CNN）的背景下。受到其对RGB视频的初步成功的启发，我们建议将其扩展到深度域。为了更好地利用深度视频的3D特性来利用性能，我们提出了多视图动态图像。具体而言，通过在3D空间内围绕特定实例旋转虚拟相机，将原始深度视频密集投影到不同的成像视点上。然后分别从产生的多视点深度视频中提取动态图像以构成多视点动态图像。以这种方式，与单视图对应物相比，多视图动态图像中可以涉及更多视图容忍的代表信息。因此提出了一种新颖的CNN学习模型来对多视图动态图像执行特征学习。来自不同视图的动态图像将共享相同的卷积层，但具有不同的完全连接的层。该模型旨在通过减轻梯度消失来增强浅层卷积层的调整。此外，为了解决空间变化的影响，提出了一种基于更快的R-CNN的行动建议方法。动态图像将仅从行动建议地区提取。在实验中，我们的方法可以在3个具有挑战性的数据集（即NTU RGB-D，Northwestern-UCLA和UWA3DII）上实现最先进的性能。

##### URL
[http://arxiv.org/abs/1806.11269](http://arxiv.org/abs/1806.11269)

##### PDF
[http://arxiv.org/pdf/1806.11269](http://arxiv.org/pdf/1806.11269)

