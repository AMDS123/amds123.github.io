---
layout: post
title: "Truncating Wide Networks using Binary Tree Architectures"
date: 2017-04-03 10:11:10
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification
author: Yan Zhang, Mete Ozay, Shuohao Li, Takayuki Okatani
mathjax: true
---

* content
{:toc}

##### Abstract
Recent study shows that a wide deep network can obtain accuracy comparable to a deeper but narrower network. Compared to narrower and deeper networks, wide networks employ relatively less number of layers and have various important benefits, such that they have less running time on parallel computing devices, and they are less affected by gradient vanishing problems. However, the parameter size of a wide network can be very large due to use of large width of each layer in the network. In order to keep the benefits of wide networks meanwhile improve the parameter size and accuracy trade-off of wide networks, we propose a binary tree architecture to truncate architecture of wide networks by reducing the width of the networks. More precisely, in the proposed architecture, the width is continuously reduced from lower layers to higher layers in order to increase the expressive capacity of network with a less increase on parameter size. Also, to ease the gradient vanishing problem, features obtained at different layers are concatenated to form the output of our architecture. By employing the proposed architecture on a baseline wide network, we can construct and train a new network with same depth but considerably less number of parameters. In our experimental analyses, we observe that the proposed architecture enables us to obtain better parameter size and accuracy trade-off compared to baseline networks using various benchmark image classification datasets. The results show that our model can decrease the classification error of baseline from 20.43% to 19.22% on Cifar-100 using only 28% of parameters that baseline has. Code is available at this https URL

##### Abstract (translated by Google)
最近的研究表明，广泛的深度网络可以获得与更深更窄的网络相当的准确性。与较窄和较深的网络相比，宽网络采用相对较少的层数并具有各种重要的优点，使得它们在并行计算设备上运行时间较少，并且受梯度消失问题影响较小。但是，由于网络中每个层的宽度较大，因此宽网络的参数大小可能非常大。为了保持宽带网络的优势，同时提高宽带网络的参数尺寸和精度折衷，本文提出了一种通过减小网络宽度来截断宽带网络结构的二叉树结构。更准确地说，在所提出的架构中，宽度从低层到高层不断减小，以增加网络的表现能力，而参数大小的增加较少。此外，为了缓解梯度消失问题，不同层次获得的特征被连接起来以形成我们架构的输出。通过在基线宽网络上采用所提出的体系结构，我们可以构建和训练具有相同深度但参数数量相当少的新网络。在我们的实验分析中，我们观察到，提出的架构使我们能够获得更好的参数大小和精度权衡相比，使用各种基准图像分类数据集的基线网络。结果表明，我们的模型可以将Cifar-100的基线分类误差从20.43％降低到19.22％，仅使用28％的基​​线参数。代码可在此https网址获得

##### URL
[https://arxiv.org/abs/1704.00509](https://arxiv.org/abs/1704.00509)

##### PDF
[https://arxiv.org/pdf/1704.00509](https://arxiv.org/pdf/1704.00509)

