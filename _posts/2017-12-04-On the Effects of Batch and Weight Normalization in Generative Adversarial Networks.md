---
layout: post
title: 'On the Effects of Batch and Weight Normalization in Generative Adversarial Networks'
date: 2017-12-05 21:10:17
categories: arXiv_CV
tags: arXiv_CV GAN
author: Sitao Xiang, Hao Li
---

* content
{:toc}

##### Abstract
Generative adversarial networks (GANs) are highly effective unsupervised learning frameworks that can generate very sharp data, even for data such as images with complex, highly multimodal distributions. However GANs are known to be very hard to train, suffering from problems such as mode collapse and disturbing visual artifacts. Batch normalization (BN) techniques have been introduced to address the training. Though BN accelerates the training in the beginning, our experiments show that the use of BN can be unstable and negatively impact the quality of the trained model. The evaluation of BN and numerous other recent schemes for improving GAN training is hindered by the lack of an effective objective quality measure for GAN models. To address these issues, we first introduce a weight normalization (WN) approach for GAN training that significantly improves the stability, efficiency and the quality of the generated samples. To allow a methodical evaluation, we introduce squared Euclidean reconstruction error on a test set as a new objective measure, to assess training performance in terms of speed, stability, and quality of generated samples. Our experiments with a standard DCGAN architecture on commonly used datasets (CelebA, LSUN bedroom, and CIFAR-10) indicate that training using WN is generally superior to BN for GANs, achieving 10% lower mean squared loss for reconstruction and significantly better qualitative results than BN. We further demonstrate the stability of WN on a 21-layer ResNet trained with the CelebA data set. The code for this paper is available at https://github.com/stormraiser/gan-weightnorm-resnet

##### Abstract (translated by Google)
生成对抗网络（GAN）是非常有效的无监督学习框架，可以生成非常清晰的数据，甚至对于具有复杂，高度多模式分布的图像等数据。然而，已知GAN非常难以训练，遭遇诸如模式崩溃和令人不安的视觉伪影之类的问题。批量标准化（BN）技术已被引入到培训中。尽管BN在一开始就加速训练，但是我们的实验表明BN的使用可能不稳定，并且对训练模型的质量有负面影响。对国民阵和最近提出的其他改进GAN训练方案的评估受到GAN模型缺乏有效客观质量测量的阻碍。为了解决这些问题，我们首先引入了用于GAN训练的权重归一化（WN）方法，其显着提高了生成的样本的稳定性，效率和质量。为了进行有条理的评估，我们引入了测试集上的欧式重建误差平方作为一个新的客观量度，从速度，稳定性和生成样本的质量来评估训练性能。我们在常用数据集（CelebA，LSUN卧室和CIFAR-10）上使用标准DCGAN架构进行的实验表明，使用WN进行的训练对于GAN来说总体上优于BN，相比于重构的均方损失低10％，定性结果明显好于BN。我们进一步证明了用CelebA数据集训练的21层ResNet上的WN的稳定性。本文的代码可以在https://github.com/stormraiser/gan-weightnorm-resnet上找到

##### URL
[http://arxiv.org/abs/1704.03971](http://arxiv.org/abs/1704.03971)

