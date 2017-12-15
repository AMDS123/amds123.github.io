---
layout: post
title: "A Light CNN for Deep Face Representation with Noisy Labels"
date: 2017-04-24 01:54:33
categories: arXiv_CV
tags: arXiv_CV Face Embedding CNN Prediction Relation Recognition Face_Recognition
author: Xiang Wu, Ran He, Zhenan Sun, Tieniu Tan
mathjax: true
---

* content
{:toc}

##### Abstract
Convolution neural network (CNN) has significantly pushed forward the development of face recognition and analysis techniques. Current CNN models tend to be deeper and larger to better fit large amounts of training data. When training data are from internet, their labels are often ambiguous and inaccurate. This paper presents a light CNN framework to learn a compact embedding on the large-scale face data with massive noisy labels. First, we introduce the concept of maxout activation into each convolutional layer of CNN, which results in a Max-Feature-Map (MFM). Different from Rectified Linear Unit that suppresses a neuron by a threshold (or bias), MFM suppresses a neuron by a competitive relationship. MFM can not only separate noisy signals and informative signals but also plays a role of feature selection. Second, a network of five convolution layers and four Network in Network (NIN) layers are implemented to reduce the number of parameters and improve performance. Lastly, a semantic bootstrapping method is accordingly designed to make the prediction of the models be better consistent with noisy labels. Experimental results show that the proposed framework can utilize large-scale noisy data to learn a light model in terms of both computational cost and storage space. The learnt single model with a 256-D representation achieves state-of-the-art results on five face benchmarks without fine-tuning. The light CNN model is released on this https URL

##### Abstract (translated by Google)
卷积神经网络（CNN）大大推动了人脸识别和分析技术的发展。目前的CNN模型往往越来越大，以更好地适应大量的训练数据。当训练数据来自互联网时，他们的标签通常是模棱两可和不准确的。本文提出了一个轻量级的CNN框架来学习一个紧凑的嵌入大规模人脸数据的大规模噪声标签。首先，我们将Maxout激活的概念引入到CNN的每个卷积层，从而产生最大特征映射（MFM）。与通过阈值（或偏差）抑制神经元的整流线性单位不同，MFM通过竞争关系抑制神经元。 MFM不仅可以分离噪声信号和信息信号，还可以起到特征选择的作用。其次，实现了五个卷积层和四个网络网络（NIN）层的网络，以减少参数数量并提高性能。最后，相应地设计语义引导方法以使得模型的预测与噪声标签更好地一致。实验结果表明，所提出的框架可以利用大规模的噪声数据在计算成本和存储空间方面学习一个轻量级模型。具有256-D表示的学习单一模型无需微调即可在五个基准面上获得最新的结果。轻型CNN模型在这个https URL上发布

##### URL
[https://arxiv.org/abs/1511.02683](https://arxiv.org/abs/1511.02683)

##### PDF
[https://arxiv.org/pdf/1511.02683](https://arxiv.org/pdf/1511.02683)

