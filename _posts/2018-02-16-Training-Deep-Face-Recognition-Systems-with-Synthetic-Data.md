---
layout: post
title: "Training Deep Face Recognition Systems with Synthetic Data"
date: 2018-02-16 11:05:18
categories: arXiv_CV
tags: arXiv_CV Face Deep_Learning Recognition Face_Recognition
author: Adam Kortylewski, Andreas Schneider, Thomas Gerig, Bernhard Egger, Andreas Morel-Forster, Thomas Vetter
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in deep learning have significantly increased the performance of face recognition systems. The performance and reliability of these models depend heavily on the amount and quality of the training data. However, the collection of annotated large datasets does not scale well and the control over the quality of the data decreases with the size of the dataset. In this work, we explore how synthetically generated data can be used to decrease the number of real-world images needed for training deep face recognition systems. In particular, we make use of a 3D morphable face model for the generation of images with arbitrary amounts of facial identities and with full control over image variations, such as pose, illumination, and background. In our experiments with an off-the-shelf face recognition software we observe the following phenomena: 1) The amount of real training data needed to train competitive deep face recognition systems can be reduced significantly. 2) Combining large-scale real-world data with synthetic data leads to an increased performance. 3) Models trained only on synthetic data with strong variations in pose, illumination, and background perform very well across different datasets even without dataset adaptation. 4) The real-to-virtual performance gap can be closed when using synthetic data for pre-training, followed by fine-tuning with real-world images. 5) There are no observable negative effects of pre-training with synthetic data. Thus, any face recognition system in our experiments benefits from using synthetic face images. The synthetic data generator, as well as all experiments, are publicly available.

##### Abstract (translated by Google)
深度学习的最新进展显着提高了人脸识别系统的性能。这些模型的性能和可靠性在很大程度上取决于培训数据的数量和质量。然而，注解的大型数据集的集合并不能很好地扩展，并且数据质量的控制随着数据集的大小而降低。在这项工作中，我们将探讨如何使用合成生成的数据来减少训练深度人脸识别系统所需的真实世界图像的数量。特别是，我们利用3D形变人脸模型生成具有任意数量面部身份的图像，并完全控制图像变化，如姿势，照明和背景。在我们使用现成的人脸识别软件进行的实验中，我们观察到以下现象：1）训练竞争性深度人脸识别系统所需的实际训练数据量可显着减少。 2）将大规模真实世界的数据与合成数据相结合，可以提高性能。 3）仅在姿态，光照和背景变化较大的合成数据上训练的模型在不同数据集中表现良好，即使没有数据集适应也是如此。 4）在使用合成数据进行预训练时，可以关闭实际到虚拟的性能差距，然后使用真实世界的图像进行微调。 5）用合成数据预训练没有明显的负面影响。因此，我们实验中的任何人脸识别系统都可以使用合成人脸图像。合成数据生成器以及所有实验都是公开可用的。

##### URL
[https://arxiv.org/abs/1802.05891](https://arxiv.org/abs/1802.05891)

##### PDF
[https://arxiv.org/pdf/1802.05891](https://arxiv.org/pdf/1802.05891)

