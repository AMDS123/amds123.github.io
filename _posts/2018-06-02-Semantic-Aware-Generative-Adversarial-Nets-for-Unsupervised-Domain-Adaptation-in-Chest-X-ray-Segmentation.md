---
layout: post
title: "Semantic-Aware Generative Adversarial Nets for Unsupervised Domain Adaptation in Chest X-ray Segmentation"
date: 2018-06-02 07:59:55
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN Transfer_Learning
author: Cheng Chen, Qi Dou, Hao Chen, Pheng-Ann Heng
mathjax: true
---

* content
{:toc}

##### Abstract
In spite of the compelling achievements that deep neural networks (DNNs) have made in medical image computing, these deep models often suffer from degraded performance when being applied to new test datasets with domain shift. In this paper, we present a novel unsupervised domain adaptation approach for segmentation tasks by designing semantic-aware generative adversarial networks (GANs). Specifically, we transform the test image into the appearance of source domain, with the semantic structural information being well preserved, which is achieved by imposing a nested adversarial learning in semantic label space. In this way, the segmentation DNN learned from the source domain is able to be directly generalized to the transformed test image, eliminating the need of training a new model for every new target dataset. Our domain adaptation procedure is unsupervised, without using any target domain labels. The adversarial learning of our network is guided by a GAN loss for mapping data distributions, a cycle-consistency loss for retaining pixel-level content, and a semantic-aware loss for enhancing structural information. We validated our method on two different chest X-ray public datasets for left/right lung segmentation. Experimental results show that the segmentation performance of our unsupervised approach is highly competitive with the upper bound of supervised transfer learning.

##### Abstract (translated by Google)
尽管深度神经网络（DNN）在医学图像计算中取得了令人瞩目的成就，但这些深度模型在应用于具有域偏移的新测试数据集时往往遭受性能下降的困扰。在本文中，我们通过设计语义感知生成对抗网络（GAN），提出了一种新的无监督领域适应分割任务的方法。具体而言，我们将测试图像转换成源域的外观，并且语义结构信息得到很好的保留，这是通过在语义标签空间中施加嵌套对抗学习来实现的。通过这种方式，从源域学习到的分割DNN能够被直接推广到变换后的测试图像，从而无需为每个新的目标数据集训练一个新的模型。我们的域名适应程序是无监督的，没有使用任何目标域名标签。我们网络的对抗性学习受GAN损失（用于映射数据分布），保留像素级内容的循环一致性损失和用于增强结构信息的语义感知损失的指导。我们验证了我们的方法在两个不同的胸部X射线公共数据集上进行左/右肺分割。实验结果表明，我们的无监督方法的分割性能与监督传递学习的上界高度竞争。

##### URL
[http://arxiv.org/abs/1806.00600](http://arxiv.org/abs/1806.00600)

##### PDF
[http://arxiv.org/pdf/1806.00600](http://arxiv.org/pdf/1806.00600)

