---
layout: post
title: "Robust Minutiae Extractor: Integrating Deep Networks and Fingerprint Domain Knowledge"
date: 2017-12-26 20:55:43
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation CNN Detection
author: Dinh-Luan Nguyen, Kai Cao, Anil K. Jain
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a fully automatic minutiae extractor, called MinutiaeNet, based on deep neural networks with compact feature representation for fast comparison of minutiae sets. Specifically, first a network, called CoarseNet, estimates the minutiae score map and minutiae orientation based on convolutional neural network and fingerprint domain knowledge (enhanced image, orientation field, and segmentation map). Subsequently, another network, called FineNet, refines the candidate minutiae locations based on score map. We demonstrate the effectiveness of using the fingerprint domain knowledge together with the deep networks. Experimental results on both latent (NIST SD27) and plain (FVC 2004) public domain fingerprint datasets provide comprehensive empirical support for the merits of our method. Further, our method finds minutiae sets that are better in terms of precision and recall in comparison with state-of-the-art on these two datasets. Given the lack of annotated fingerprint datasets with minutiae ground truth, the proposed approach to robust minutiae detection will be useful to train network-based fingerprint matching algorithms as well as for evaluating fingerprint individuality at scale. MinutiaeNet is implemented in Tensorflow: https://github.com/luannd/MinutiaeNet

##### Abstract (translated by Google)
我们提出了一种名为MinutiaeNet的全自动细节提取器，它基于具有紧凑特征表示的深度神经网络，用于快速比较细节集。具体而言，首先称为CoarseNet的网络基于卷积神经网络和指纹领域知识（增强图像，方向场和分割图）估计细节分数图和细节方向。随后，另一个名为FineNet的网络根据分数图精炼候选细节位置。我们展示了使用指纹领域知识和深度网络的有效性。潜在（NIST SD27）和普通（FVC 2004）公共领域指纹数据集的实验结果为我们的方法的优点提供了全面的经验支持。此外，我们的方法发现在这两个数据集上精确度和召回率都比现有技术更好的细节集。由于缺少具有细节地面真实性的带注释的指纹数据集，所提出的鲁棒细节检测方法将有助于训练基于网络的指纹匹配算法以及用于评估指纹个性的规模。 MinutiaeNet在Tensorflow中实现：https：//github.com/luannd/MinutiaeNet

##### URL
[http://arxiv.org/abs/1712.09401](http://arxiv.org/abs/1712.09401)

##### PDF
[http://arxiv.org/pdf/1712.09401](http://arxiv.org/pdf/1712.09401)

