---
layout: post
title: "End to End Brain Fiber Orientation Estimation using Deep Learning"
date: 2018-06-04 18:07:25
categories: arXiv_CV
tags: arXiv_CV GAN Tracking Deep_Learning
author: Nandakishore Puttashamachar, Ulas Bagci
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we explore the various Brain Neuron tracking techniques, which is one of the most significant applications of Diffusion Tensor Imaging. Tractography provides us with a non-invasive method to analyze underlying tissue micro-structure. Understanding the structure and organization of the tissues facilitates us with a diagnosis method to identify any aberrations and provide acute information on the occurrences of brain ischemia or stroke, the mutation of neurological diseases such as Alzheimer, multiple sclerosis and so on. Time if of essence and accurate localization of the aberrations can help save or change a diseased life. Following up with the limitations introduced by the current Tractography techniques such as computational complexity, reconstruction errors during tensor estimation and standardization, we aim to elucidate these limitations through our research findings. We introduce an end to end Deep Learning framework which can accurately estimate the most probable likelihood orientation at each voxel along a neuronal pathway. We use Probabilistic Tractography as our baseline model to obtain the training data and which also serve as a Tractography Gold Standard for our evaluations. Through experiments we show that our Deep Network can do a significant improvement over current Tractography implementations by reducing the run-time complexity to a significant new level. Our architecture also allows for variable sized input DWI signals eliminating the need to worry about memory issues as seen with the traditional techniques. The advantage of this architecture is that it is perfectly desirable to be processed on a cloud setup and utilize the existing multi GPU frameworks to perform whole brain Tractography in minutes rather than hours. We evaluate our network with Gold Standard and benchmark its performance across several parameters.

##### Abstract (translated by Google)
在这项工作中，我们探索了各种脑部神经元跟踪技术，这是扩散张量成像最重要的应用之一。 Tractography为我们提供了一种无创方法来分析潜在的组织微观结构。了解组织的结构和组织，有助于我们采用诊断方法来识别任何畸变，并提供有关脑缺血或中风，神经系统疾病如阿尔茨海默病，多发性硬化等突变的信息。时间如果精华和像差的准确定位可以帮助拯救或改变患病的生活。继续介绍当前Tractography技术所带来的局限性，如计算复杂性，张量估计和标准化过程中的重建误差，我们的目标是通过我们的研究结果阐明这些局限性。我们引入了一个端到端的深度学习框架，该框架可以准确估计沿着神经元路径的每个体素的最可能的可能性方向。我们使用Probabilistic Tractography作为我们的基准模型来获取训练数据，并将其作为我们评估的Tractography黄金标准。通过实验，我们发现，通过将运行时复杂性降低到重要的新水平，我们的Deep Network可以对目前的Tractography实现做出重大改进。我们的架构还允许可变尺寸的输入DWI信号，无需担心传统技术中出现的内存问题。这种架构的优势在于，它非常适合在云安装上进行处理，并利用现有的多GPU架构在几分钟内完成全脑Tractography，而不是几个小时。我们使用黄金标准评估我们的网络，并在多个参数上测试其性能。

##### URL
[http://arxiv.org/abs/1806.03969](http://arxiv.org/abs/1806.03969)

##### PDF
[http://arxiv.org/pdf/1806.03969](http://arxiv.org/pdf/1806.03969)

