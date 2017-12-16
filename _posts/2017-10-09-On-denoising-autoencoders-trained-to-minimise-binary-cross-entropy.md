---
layout: post
title: "On denoising autoencoders trained to minimise binary cross-entropy"
date: 2017-10-09 08:40:39
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Antonia Creswell, Kai Arulkumaran, Anil A. Bharath
mathjax: true
---

* content
{:toc}

##### Abstract
Denoising autoencoders (DAEs) are powerful deep learning models used for feature extraction, data generation and network pre-training. DAEs consist of an encoder and decoder which may be trained simultaneously to minimise a loss (function) between an input and the reconstruction of a corrupted version of the input. There are two common loss functions used for training autoencoders, these include the mean-squared error (MSE) and the binary cross-entropy (BCE). When training autoencoders on image data a natural choice of loss function is BCE, since pixel values may be normalised to take values in [0,1] and the decoder model may be designed to generate samples that take values in (0,1). We show theoretically that DAEs trained to minimise BCE may be used to take gradient steps in the data space towards regions of high probability under the data-generating distribution. Previously this had only been shown for DAEs trained using MSE. As a consequence of the theory, iterative application of a trained DAE moves a data sample from regions of low probability to regions of higher probability under the data-generating distribution. Firstly, we validate the theory by showing that novel data samples, consistent with the training data, may be synthesised when the initial data samples are random noise. Secondly, we motivate the theory by showing that initial data samples synthesised via other methods may be improved via iterative application of a trained DAE to those initial samples.

##### Abstract (translated by Google)
去噪自动编码器（DAE）是用于特征提取，数据生成和网络预训练的强大的深度学习模型。 DAE由一个编码器和解码器组成，可以同时训练，以最大限度地减少输入和重构损坏版本的输入之间的损失（功能）。有两种用于训练自编码器的常见损失函数，其中包括均方误差（MSE）和二元交叉熵（BCE）。当在图像数据上训练自编码器时，损失函数的自然选择是BCE，因为像素值可以被归一化以获取[0,1]中的值，并且解码器模型可以被设计为生成取（0,1）中的值的样本。我们从理论上表明，经过训练以使BCE最小化的DAEs可用于在数据生成分布下向数据空间中的高概率区域采取梯度步骤。以前只有使用MSE训练过的D​​AE才能显示。作为该理论的结果，经过训练的DAE的迭代应用将数据样本从低概率区域移动到数据生成分布下的较高概率区域。首先，我们验证了理论，证明了当初始数据样本是随机噪声时，可以合成与训练数据一致的新的数据样本。其次，我们通过展示通过其他方法合成的初始数据样本可以通过迭代应用经过训练的DAE到那些初始样本来改进理论。

##### URL
[https://arxiv.org/abs/1708.08487](https://arxiv.org/abs/1708.08487)

##### PDF
[https://arxiv.org/pdf/1708.08487](https://arxiv.org/pdf/1708.08487)

