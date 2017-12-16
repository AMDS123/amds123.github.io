---
layout: post
title: "Tversky loss function for image segmentation using 3D fully convolutional deep networks"
date: 2017-06-18 20:35:27
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Prediction
author: Seyed Sadegh Mohseni Salehi, Deniz Erdogmus, Ali Gholipour
mathjax: true
---

* content
{:toc}

##### Abstract
Fully convolutional deep neural networks carry out excellent potential for fast and accurate image segmentation. One of the main challenges in training these networks is data imbalance, which is particularly problematic in medical imaging applications such as lesion segmentation where the number of lesion voxels is often much lower than the number of non-lesion voxels. Training with unbalanced data can lead to predictions that are severely biased towards high precision but low recall (sensitivity), which is undesired especially in medical applications where false negatives are much less tolerable than false positives. Several methods have been proposed to deal with this problem including balanced sampling, two step training, sample re-weighting, and similarity loss functions. In this paper, we propose a generalized loss function based on the Tversky index to address the issue of data imbalance and achieve much better trade-off between precision and recall in training 3D fully convolutional deep neural networks. Experimental results in multiple sclerosis lesion segmentation on magnetic resonance images show improved F2 score, Dice coefficient, and the area under the precision-recall curve in test data. Based on these results we suggest Tversky loss function as a generalized framework to effectively train deep neural networks.

##### Abstract (translated by Google)
完全卷积深度神经网络为快速精确的图像分割提供了极好的潜力。训练这些网络的主要挑战之一是数据不平衡，这在医学成像应用中是特别成问题的，例如损伤体素的数量通常远远低于非损伤体素的数量的损伤分割。使用不平衡数据进行训练可能会导致预测严重偏向于高精度但回忆（灵敏度）较低，这在医疗应用中是非常不希望的，特别是在医疗应用中，假阴性比假阳性更不容忍。已经提出了几种方法来处理这个问题，包括平衡采样，两步训练，样本重新加权和相似性损失函数。在本文中，我们提出了一个基于Tversky指数的广义损失函数来解决数据不平衡问题，并且在训练三维全卷积深度神经网络的过程中，在精度和召回率之间取得了更好的平衡。在磁共振图像的多发性硬化病变分割中的实验结果显示在测试数据中改进的F2分数，Dice系数和精度 - 回忆曲线下的面积。基于这些结果，我们建议Tversky损失函数作为有效训练深度神经网络的广义框架。

##### URL
[https://arxiv.org/abs/1706.05721](https://arxiv.org/abs/1706.05721)

##### PDF
[https://arxiv.org/pdf/1706.05721](https://arxiv.org/pdf/1706.05721)

