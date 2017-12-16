---
layout: post
title: "Learning without Prejudice: Avoiding Bias in Webly-Supervised Action Recognition"
date: 2017-06-14 17:10:59
categories: arXiv_CV
tags: arXiv_CV Video_Caption Action_Recognition Detection Recognition
author: Christian Rupprecht, Ansh Kapil, Nan Liu, Lamberto Ballan, Federico Tombari
mathjax: true
---

* content
{:toc}

##### Abstract
Webly-supervised learning has recently emerged as an alternative paradigm to traditional supervised learning based on large-scale datasets with manual annotations. The key idea is that models such as CNNs can be learned from the noisy visual data available on the web. In this work we aim to exploit web data for video understanding tasks such as action recognition and detection. One of the main problems in webly-supervised learning is cleaning the noisy labeled data from the web. The state-of-the-art paradigm relies on training a first classifier on noisy data that is then used to clean the remaining dataset. Our key insight is that this procedure biases the second classifier towards samples that the first one understands. Here we train two independent CNNs, a RGB network on web images and video frames and a second network using temporal information from optical flow. We show that training the networks independently is vastly superior to selecting the frames for the flow classifier by using our RGB network. Moreover, we show benefits in enriching the training set with different data sources from heterogeneous public web databases. We demonstrate that our framework outperforms all other webly-supervised methods on two public benchmarks, UCF-101 and Thumos'14.

##### Abstract (translated by Google)
Webly监督学习最近已经成为基于大规模数据集和手工注释的传统监督学习的替代范例。关键的想法是，CNN等模型可以从网络上可用的嘈杂的视觉数据中学习。在这项工作中，我们旨在利用网络数据进行视频理解任务，如动作识别和检测。网络监督学习中的主要问题之一是清除网络中带噪标签的数据。最先进的范例依赖于对噪声数据训练第一个分类器，然后用它来清理剩余的数据集。我们的主要观点是，这个程序偏向于第一个可以理解的样本的第二个分类器。在这里，我们训练两个独立的CNN，一个RGB网络的网络图像和视频帧，第二个网络使用光流的时间信息。我们表明，独立训练网络比通过使用RGB网络选择流分类器的框架要优越得多。此外，我们还展示了利用来自异构公共Web数据库的不同数据源丰富培训集的好处。我们证明，我们的框架在两个公共基准UCF-101和Thumos'14上优于所有其他web-supervised方法。

##### URL
[https://arxiv.org/abs/1706.04589](https://arxiv.org/abs/1706.04589)

##### PDF
[https://arxiv.org/pdf/1706.04589](https://arxiv.org/pdf/1706.04589)

