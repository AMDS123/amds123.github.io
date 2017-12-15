---
layout: post
title: "Temporal Pyramid Pooling Based Convolutional Neural Networks for Action Recognition"
date: 2015-04-16 12:18:46
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Image_Classification Classification Recognition
author: Peng Wang, Yuanzhouhan Cao, Chunhua Shen, Lingqiao Liu, Heng Tao Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Encouraged by the success of Convolutional Neural Networks (CNNs) in image classification, recently much effort is spent on applying CNNs to video based action recognition problems. One challenge is that video contains a varying number of frames which is incompatible to the standard input format of CNNs. Existing methods handle this issue either by directly sampling a fixed number of frames or bypassing this issue by introducing a 3D convolutional layer which conducts convolution in spatial-temporal domain. To solve this issue, here we propose a novel network structure which allows an arbitrary number of frames as the network input. The key of our solution is to introduce a module consisting of an encoding layer and a temporal pyramid pooling layer. The encoding layer maps the activation from previous layers to a feature vector suitable for pooling while the temporal pyramid pooling layer converts multiple frame-level activations into a fixed-length video-level representation. In addition, we adopt a feature concatenation layer which combines appearance information and motion information. Compared with the frame sampling strategy, our method avoids the risk of missing any important frames. Compared with the 3D convolutional method which requires a huge video dataset for network training, our model can be learned on a small target dataset because we can leverage the off-the-shelf image-level CNN for model parameter initialization. Experiments on two challenging datasets, Hollywood2 and HMDB51, demonstrate that our method achieves superior performance over state-of-the-art methods while requiring much fewer training data.

##### Abstract (translated by Google)
受到卷积神经网络（CNN）在图像分类方面的成功的鼓舞，最近花费在将CNN应用于基于视频的动作识别问题上的努力。一个挑战是视频包含不同于CNN的标准输入格式的不同数量的帧。现有方法通过直接采样固定数量的帧或者通过引入在时空域中进行卷积的3D卷积层来绕过这个问题来处理这个问题。为了解决这个问题，在这里我们提出一种新颖的网络结构，允许任意数量的帧作为网络输入。我们的解决方案的关键是引入一个由编码层和时间金字塔池层组成的模块。编码层将来自先前层的激活映射到适于汇集的特征向量，而时间金字塔池化层将多个帧级激活转换为固定长度的视频级表示。另外，我们采用一个结合了外观信息和运动信息的特征拼接层。与帧采样策略相比，我们的方法避免了丢失任何重要帧的风险。与需要庞大的视频数据集进行网络训练的三维卷积方法相比，我们的模型可以在小的目标数据集上学习，因为我们可以利用现成的图像级CNN进行模型参数初始化。在两个具有挑战性的数据集Hollywood2和HMDB51上的实验表明，我们的方法比现有技术的方法实现了更好的性能，同时需要更少的训练数据。

##### URL
[https://arxiv.org/abs/1503.01224](https://arxiv.org/abs/1503.01224)

##### PDF
[https://arxiv.org/pdf/1503.01224](https://arxiv.org/pdf/1503.01224)

