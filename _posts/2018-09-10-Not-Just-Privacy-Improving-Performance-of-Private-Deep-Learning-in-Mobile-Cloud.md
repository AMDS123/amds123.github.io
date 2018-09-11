---
layout: post
title: "Not Just Privacy: Improving Performance of Private Deep Learning in Mobile Cloud"
date: 2018-09-10 16:09:58
categories: arXiv_AI
tags: arXiv_AI Inference Deep_Learning
author: Ji Wang, Jianguo Zhang, Weidong Bao, Xiaomin Zhu, Bokai Cao, Philip S. Yu
mathjax: true
---

* content
{:toc}

##### Abstract
The increasing demand for on-device deep learning services calls for a highly efficient manner to deploy deep neural networks (DNNs) on mobile devices with limited capacity. The cloud-based solution is a promising approach to enabling deep learning applications on mobile devices where the large portions of a DNN are offloaded to the cloud. However, revealing data to the cloud leads to potential privacy risk. To benefit from the cloud data center without the privacy risk, we design, evaluate, and implement a cloud-based framework ARDEN which partitions the DNN across mobile devices and cloud data centers. A simple data transformation is performed on the mobile device, while the resource-hungry training and the complex inference rely on the cloud data center. To protect the sensitive information, a lightweight privacy-preserving mechanism consisting of arbitrary data nullification and random noise addition is introduced, which provides strong privacy guarantee. A rigorous privacy budget analysis is given. Nonetheless, the private perturbation to the original data inevitably has a negative impact on the performance of further inference on the cloud side. To mitigate this influence, we propose a noisy training method to enhance the cloud-side network robustness to perturbed data. Through the sophisticated design, ARDEN can not only preserve privacy but also improve the inference performance. To validate the proposed ARDEN, a series of experiments based on three image datasets and a real mobile application are conducted. The experimental results demonstrate the effectiveness of ARDEN. Finally, we implement ARDEN on a demo system to verify its practicality.

##### Abstract (translated by Google)
对设备上深度学习服务的不断增长的需求要求在容量有限的移动设备上部署深度神经网络（DNN）的高效方式。基于云的解决方案是一种在移动设备上启用深度学习应用程序的有前景的方法，其中大部分DNN被卸载到云。但是，向云中显示数据会导致潜在的隐私风险。为了从没有隐私风险的云数据中心中受益，我们设计，评估和实施基于云的框架ARDEN，该框架在移动设备和云数据中心之间划分DNN。在移动设备上执行简单的数据转换，而资源匮乏的培训和复杂的推断依赖于云数据中心。为了保护敏感信息，引入了由任意数据无效和随机噪声添加组成的轻量级隐私保护机制，提供了强大的隐私保障。提供严格的隐私预算分析。尽管如此，对原始数据的私人扰动不可避免地对云端的进一步推断的性能产生负面影响。为了减轻这种影响，我们提出了一种噪声训练方法，以增强云端网络对扰动数据的鲁棒性。通过精密的设计，ARDEN不仅可以保护隐私，还可以提高推理性能。为了验证所提出的ARDEN，进行了基于三个图像数据集和真实移动应用的一系列实验。实验结果证明了ARDEN的有效性。最后，我们在演示系统上实现ARDEN以验证其实用性。

##### URL
[http://arxiv.org/abs/1809.03428](http://arxiv.org/abs/1809.03428)

##### PDF
[http://arxiv.org/pdf/1809.03428](http://arxiv.org/pdf/1809.03428)

