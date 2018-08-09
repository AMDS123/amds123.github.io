---
layout: post
title: "Unsupervised/Semi-supervised Deep Learning for Low-dose CT Enhancement"
date: 2018-08-08 02:23:37
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Mingrui Geng, Yun Deng, Qian Zhao, Qi Xie, Dong Zeng, Dong Zeng, Wangmeng Zuo, Deyu Meng
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, deep learning(DL) methods have been proposed for the low-dose computed tomography(LdCT) enhancement, and obtain good trade-off between computational efficiency and image quality. Most of them need large number of pre-collected ground-truth/high-dose sinograms with less noise, and train the network in a supervised end-to-end manner. This may bring major limitations on these methods because the number of such low-dose/high-dose training sinogram pairs would affect the network's capability and sometimes the ground-truth sinograms are hard to be obtained in large scale. Since large number of low-dose ones are relatively easy to obtain, it should be critical to make these sources play roles in network training in an unsupervised learning manner. To address this issue, we propose an unsupervised DL method for LdCT enhancement that incorporates unlabeled LdCT sinograms directly into the network training. The proposed method effectively considers the structure characteristics and noise distribution in the measured LdCT sinogram, and then learns the proper gradient of the LdCT sinogram in a pure unsupervised manner. Similar to the labeled ground-truth, the gradient information in an unlabeled LdCT sinogram can be used for sufficient network training. The experiments on the patient data show effectiveness of the proposed method.

##### Abstract (translated by Google)
最近，已经提出了用于低剂量计算机断层摄影（LdCT）增强的深度学习（DL）方法，并且在计算效率和图像质量之间获得了良好的折衷。他们中的大多数需要大量预先收集的地面实况/高剂量正弦图，噪声较小，并以受监督的端到端方式训练网络。这可能会对这些方法带来重大限制，因为这种低剂量/高剂量训练正弦图对的数量会影响网络的能力，有时很难获得大规模的地面真实正弦图。由于大量低剂量的剂量相对容易获得，因此以无监督学习方式使这些源在网络训练中发挥作用至关重要。为了解决这个问题，我们提出了一种用于LdCT增强的无监督DL方法，该方法将未标记的LdCT正弦图直接结合到网络训练中。该方法有效地考虑了测量的LdCT正弦图中的结构特征和噪声分布，然后以纯无监督的方式学习了LdCT正弦图的适当梯度。与标记的地面实况类似，未标记的LdCT正弦图中的梯度信息可用于充分的网络训练。对患者数据的实验表明了该方法的有效性。

##### URL
[http://arxiv.org/abs/1808.02603](http://arxiv.org/abs/1808.02603)

##### PDF
[http://arxiv.org/pdf/1808.02603](http://arxiv.org/pdf/1808.02603)

