---
layout: post
title: "Tversky as a Loss Function for Highly Unbalanced Image Segmentation using 3D Fully Convolutional Deep Networks"
date: 2018-03-28 16:29:54
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Prediction
author: Seyed Raein Hashemi, Seyed Sadegh Mohseni Salehi, Deniz Erdogmus, Sanjay P. Prabhu, Simon K. Warfield, Ali Gholipour
mathjax: true
---

* content
{:toc}

##### Abstract
Fully convolutional deep neural networks have been asserted to be fast and precise frameworks with great potential in image segmentation. One of the major challenges in utilizing such networks is data imbalance, which is especially restraining in medical imaging applications such as lesion segmentation where lesion class voxels are often much less than non-lesion voxels. A trained network with unbalanced data may make predictions toward high precision and low recall, being severely biased towards the non-lesion class which is particularly undesired in medical applications where false negatives are actually more important than false positives. Several methods have been proposed to deal with this problem including balanced sampling, two step training, sample re-weighting, and similarity loss functions. We propose a generalized loss function based on the Tversky index to mitigate the issue of data imbalance and achieve much better trade-off between precision and recall in training 3D fully convolutional deep neural networks. Moreover, we extend our preliminary work on using Tversky loss function for U-net to a patch-wise 3D densely connected network, where we use overlapping image patches for intrinsic and extrinsic data augmentation. To this end, we propose a patch prediction fusion strategy based on B-spline weighted soft voting to take into account the uncertainty of prediction in patch borders. Lesion segmentation results obtained from our patch-wise 3D densely connected network are superior to the reported results in the literature on multiple sclerosis lesion segmentation on magnetic resonance imaging dataset, namely MSSEG 2016, in which we obtained average Dice coefficient of 69.8\%. Significant improvement in $F_1$ and $F_2$ scores and the area under the precision-recall curve was achieved in test using the Tversky loss layer and via our 3D patch prediction fusion method.

##### Abstract (translated by Google)
完全卷积深度神经网络被认为是图像分割具有巨大潜力的快速精确框架。利用这种网络的主要挑战之一是数据不平衡，这在医学成像应用中尤其受限，例如病变类别体素通常比非病变体元低得多的病变分割。训练有素的网络数据不平衡可能会导致对高精度和低回忆的预测，严重偏向于非病变类别，这在医学应用中尤为不受欢迎，其中假阴性实际上比假阳性更重要。已经提出了几种方法来处理这个问题，包括平衡采样，两步训练，样本重新加权和相似性损失函数。我们提出了一个基于Tversky指数的广义损失函数来缓解数据不平衡问题，并在训练3D完全卷积深度神经网络时在精度和召回率之间取得更好的平衡。此外，我们将使用U-net的Tversky损失函数的初步工作扩展到贴片式3D密集连接网络，在这里我们使用重叠图像补丁来进行内部和外部数据增强。为此，我们提出了一种基于B样条加权软投票的贴片预测融合策略，以考虑贴片边界预测的不确定性。从我们的贴片3D密集连接网络获得的病变分割结果优于文献中关于磁共振成像数据集上的多发性硬化病变分割的报道结果，即MSSEG2016，其中我们获得了69.8％的平均Dice系数。在使用Tversky损失层和我们的3D贴片预测融合方法的测试中，$ F_1 $和$ F_2 $得分的显着改善以及精度 - 召回曲线下的面积得以实现。

##### URL
[http://arxiv.org/abs/1803.11078](http://arxiv.org/abs/1803.11078)

##### PDF
[http://arxiv.org/pdf/1803.11078](http://arxiv.org/pdf/1803.11078)

