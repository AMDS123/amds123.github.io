---
layout: post
title: "Adversarially Tuned Scene Generation"
date: 2017-07-07 14:28:40
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN
author: V S R Veeravasarapu, Constantin Rothkopf, Ramesh Visvanathan
mathjax: true
---

* content
{:toc}

##### Abstract
Generalization performance of trained computer vision systems that use computer graphics (CG) generated data is not yet effective due to the concept of 'domain-shift' between virtual and real data. Although simulated data augmented with a few real world samples has been shown to mitigate domain shift and improve transferability of trained models, guiding or bootstrapping the virtual data generation with the distributions learnt from target real world domain is desired, especially in the fields where annotating even few real images is laborious (such as semantic labeling, and intrinsic images etc.). In order to address this problem in an unsupervised manner, our work combines recent advances in CG (which aims to generate stochastic scene layouts coupled with large collections of 3D object models) and generative adversarial training (which aims train generative models by measuring discrepancy between generated and real data in terms of their separability in the space of a deep discriminatively-trained classifier). Our method uses iterative estimation of the posterior density of prior distributions for a generative graphical model. This is done within a rejection sampling framework. Initially, we assume uniform distributions as priors on the parameters of a scene described by a generative graphical model. As iterations proceed the prior distributions get updated to distributions that are closer to the (unknown) distributions of target data. We demonstrate the utility of adversarially tuned scene generation on two real-world benchmark datasets (CityScapes and CamVid) for traffic scene semantic labeling with a deep convolutional net (DeepLab). We realized performance improvements by 2.28 and 3.14 points (using the IoU metric) between the DeepLab models trained on simulated sets prepared from the scene generation models before and after tuning to CityScapes and CamVid respectively.

##### Abstract (translated by Google)
使用计算机图形（CG）生成的数据的经过训练的计算机视觉系统的泛化性能由于虚拟数据和真实数据之间的“域转移”概念而不是有效的。尽管用少量现实世界样本增加的模拟数据已经被证明可以缓解域转移并提高训练模型的可转移性，但是期望引导或引导虚拟数据世代与从目标真实世界领域学习的分布，尤其是在注释均匀很少有真实的图像是费力的（比如语义标签，内在图像等）。为了以无监督的方式解决这个问题，我们的工作结合了CG（旨在生成随机场景布局，加上大量的3D对象模型）和生成对抗训练（其目标是通过测量生成的差异和真实的数据就其在深度判别训练分类器的空间中的可分离性而言）。我们的方法使用先验分布的后验密度的迭代估计来生成图形模型。这是在拒绝抽样框架内完成的。最初，我们假设均匀分布作为由生成图形模型描述的场景的参数。随着迭代的进行，先验分布更新到更接近目标数据（未知）分布的分布。我们演示了在两个真实世界基准数据集（CityScapes和CamVid）上使用深卷积网（DeepLab）进行交通场景语义标记的敌对调整场景生成的效用。在分别调整到CityScapes和CamVid之前和之后，使用从场景生成模型准备的模拟集合训练的DeepLab模型之间，我们实现了性能提升2.28和3.14点（使用IoU度量）。

##### URL
[https://arxiv.org/abs/1701.00405](https://arxiv.org/abs/1701.00405)

##### PDF
[https://arxiv.org/pdf/1701.00405](https://arxiv.org/pdf/1701.00405)

