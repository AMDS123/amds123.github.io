---
layout: post
title: "UnFlow: Unsupervised Learning of Optical Flow with a Bidirectional Census Loss"
date: 2017-11-21 15:19:26
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Simon Meister, Junhwa Hur, Stefan Roth
mathjax: true
---

* content
{:toc}

##### Abstract
In the era of end-to-end deep learning, many advances in computer vision are driven by large amounts of labeled data. In the optical flow setting, however, obtaining dense per-pixel ground truth for real scenes is difficult and thus such data is rare. Therefore, recent end-to-end convolutional networks for optical flow rely on synthetic datasets for supervision, but the domain mismatch between training and test scenarios continues to be a challenge. Inspired by classical energy-based optical flow methods, we design an unsupervised loss based on occlusion-aware bidirectional flow estimation and the robust census transform to circumvent the need for ground truth flow. On the KITTI benchmarks, our unsupervised approach outperforms previous unsupervised deep networks by a large margin, and is even more accurate than similar supervised methods trained on synthetic datasets alone. By optionally fine-tuning on the KITTI training data, our method achieves competitive optical flow accuracy on the KITTI 2012 and 2015 benchmarks, thus in addition enabling generic pre-training of supervised networks for datasets with limited amounts of ground truth.

##### Abstract (translated by Google)
在端到端深度学习的时代，计算机视觉方面的许多进步是由大量的标记数据驱动的。然而，在光流设置中，为实际场景获得密集的每像素的地面实况是困难的，因此这样的数据是罕见的。因此，最近的用于光流的端到端卷积网络依赖于合成数据集进行监督，但是训练和测试场景之间的域不匹配仍然是一个挑战。受传统的基于能量的光流方法的启发，我们设计了一个基于遮挡感知的双向流动估计的无监督损失和鲁棒的人口普查变换来规避对地面真实流量的需求。在KITTI基准测试中，我们的无监督方法大大优于先前的无监督深度网络，并且比仅在合成数据集上训练的类似监督方法更精确。通过对KITTI培训数据进行可选的微调，我们的方法在KITTI 2012和2015基准测试中实现了具有竞争力的光学流量精度，从而为有限量的地面实况的数据集启用通用的监督网络预训练。

##### URL
[https://arxiv.org/abs/1711.07837](https://arxiv.org/abs/1711.07837)

##### PDF
[https://arxiv.org/pdf/1711.07837](https://arxiv.org/pdf/1711.07837)

