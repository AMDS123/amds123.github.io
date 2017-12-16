---
layout: post
title: "Dropping Activation Outputs with Localized First-layer Deep Network for Enhancing User Privacy and Data Security"
date: 2017-11-20 19:57:57
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Prediction Detection
author: Hao Dong, Chao Wu, Zhen Wei, Yike Guo
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning methods can play a crucial role in anomaly detection, prediction, and supporting decision making for applications like personal health-care, pervasive body sensing, etc. However, current architecture of deep networks suffers the privacy issue that users need to give out their data to the model (typically hosted in a server or a cluster on Cloud) for training or prediction. This problem is getting more severe for those sensitive health-care or medical data (e.g fMRI or body sensors measures like EEG signals). In addition to this, there is also a security risk of leaking these data during the data transmission from user to the model (especially when it's through Internet). Targeting at these issues, in this paper we proposed a new architecture for deep network in which users don't reveal their original data to the model. In our method, feed-forward propagation and data encryption are combined into one process: we migrate the first layer of deep network to users' local devices, and apply the activation functions locally, and then use "dropping activation output" method to make the output non-invertible. The resulting approach is able to make model prediction without accessing users' sensitive raw data. Experiment conducted in this paper showed that our approach achieves the desirable privacy protection requirement, and demonstrated several advantages over the traditional approach with encryption / decryption

##### Abstract (translated by Google)
深度学习方法可以在异常检测，预测以及支持个人保健，普及体感等应用的决策制定中发挥关键作用。然而，深度网络的当前体系结构遭受用户需要给出的隐私问题数据传输到模型（通常托管在云服务器或云中的集群上）进行培训或预测。对于那些敏感的医疗保健或医疗数据（例如功能磁共振成像或身体传感器措施，如脑电信号），这个问题变得越来越严重。除此之外，在从用户到模型的数据传输过程中（尤其是在通过互联网的情况下），这些数据也有泄漏的风险。针对这些问题，本文提出了一种深度网络的新架构，其中用户不会将原始数据泄露给模型。在我们的方法中，前馈传播和数据加密被合并为一个过程：我们将第一层深度网络迁移到用户的本地设备，并在本地应用激活函数，然后使用“下降激活输出”方法输出不可逆。所得到的方法能够在不访问用户的敏感原始数据的情况下进行模型预测。本文进行的实验表明，我们的方法达到了理想的隐私保护要求，并且证明了与传统的加密/解密方法相比的几个优点

##### URL
[https://arxiv.org/abs/1711.07520](https://arxiv.org/abs/1711.07520)

##### PDF
[https://arxiv.org/pdf/1711.07520](https://arxiv.org/pdf/1711.07520)

