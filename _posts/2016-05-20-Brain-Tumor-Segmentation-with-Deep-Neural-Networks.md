---
layout: post
title: "Brain Tumor Segmentation with Deep Neural Networks"
date: 2016-05-20 06:30:23
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Mohammad Havaei, Axel Davy, David Warde-Farley, Antoine Biard, Aaron Courville, Yoshua Bengio, Chris Pal, Pierre-Marc Jodoin, Hugo Larochelle
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a fully automatic brain tumor segmentation method based on Deep Neural Networks (DNNs). The proposed networks are tailored to glioblastomas (both low and high grade) pictured in MR images. By their very nature, these tumors can appear anywhere in the brain and have almost any kind of shape, size, and contrast. These reasons motivate our exploration of a machine learning solution that exploits a flexible, high capacity DNN while being extremely efficient. Here, we give a description of different model choices that we've found to be necessary for obtaining competitive performance. We explore in particular different architectures based on Convolutional Neural Networks (CNN), i.e. DNNs specifically adapted to image data. We present a novel CNN architecture which differs from those traditionally used in computer vision. Our CNN exploits both local features as well as more global contextual features simultaneously. Also, different from most traditional uses of CNNs, our networks use a final layer that is a convolutional implementation of a fully connected layer which allows a 40 fold speed up. We also describe a 2-phase training procedure that allows us to tackle difficulties related to the imbalance of tumor labels. Finally, we explore a cascade architecture in which the output of a basic CNN is treated as an additional source of information for a subsequent CNN. Results reported on the 2013 BRATS test dataset reveal that our architecture improves over the currently published state-of-the-art while being over 30 times faster.

##### Abstract (translated by Google)
在本文中，我们提出了一种基于深度神经网络（DNNs）的全自动脑肿瘤分割方法。所提出的网络适合MR图像中所示的胶质母细胞瘤（包括低级和高级）。就其性质而言，这些肿瘤可以出现在大脑的任何地方，并具有几乎任何形状，大小和对比度。这些原因激发了我们对机器学习解决方案的探索，该机器学习解决方案利用灵活，高容量的DNN，同时效率极高。在这里，我们介绍了不同的模型选择，我们发现这是获得竞争力所必需的。我们特别研究基于卷积神经网络（CNN）的不同架构，即专门适用于图像数据的DNN。我们提出了一种新颖的CNN架构，与传统上用于计算机视觉的不同。我们的CNN同时利用本地功能以及更多的全球语境特征。另外，与CNN的大多数传统用途不同，我们的网络使用最后一层，这是一个完全连接层的卷积实现，允许加速40倍。我们还描述了一个两阶段的培训程序，使我们能够解决与肿瘤标签不平衡相关的困难。最后，我们探索了一个级联架构，在这个架构中，一个基本CNN的输出被视为后续CNN的附加信息源。在2013年BRATS测试数据集上报告的结果显示，我们的架构比目前发布的最新技术水平有所提高，而速度提高了30倍以上。

##### URL
[https://arxiv.org/abs/1505.03540](https://arxiv.org/abs/1505.03540)

##### PDF
[https://arxiv.org/pdf/1505.03540](https://arxiv.org/pdf/1505.03540)

