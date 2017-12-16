---
layout: post
title: "Multi-source Transfer Learning with Convolutional Neural Networks for Lung Pattern Analysis"
date: 2016-12-08 10:43:03
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Transfer_Learning Classification
author: Stergios Christodoulidis, Marios Anthimopoulos, Lukas Ebner, Andreas Christe, Stavroula Mougiakakou
mathjax: true
---

* content
{:toc}

##### Abstract
Early diagnosis of interstitial lung diseases is crucial for their treatment, but even experienced physicians find it difficult, as their clinical manifestations are similar. In order to assist with the diagnosis, computer-aided diagnosis (CAD) systems have been developed. These commonly rely on a fixed scale classifier that scans CT images, recognizes textural lung patterns and generates a map of pathologies. In a previous study, we proposed a method for classifying lung tissue patterns using a deep convolutional neural network (CNN), with an architecture designed for the specific problem. In this study, we present an improved method for training the proposed network by transferring knowledge from the similar domain of general texture classification. Six publicly available texture databases are used to pretrain networks with the proposed architecture, which are then fine-tuned on the lung tissue data. The resulting CNNs are combined in an ensemble and their fused knowledge is compressed back to a network with the original architecture. The proposed approach resulted in an absolute increase of about 2% in the performance of the proposed CNN. The results demonstrate the potential of transfer learning in the field of medical image analysis, indicate the textural nature of the problem and show that the method used for training a network can be as important as designing its architecture.

##### Abstract (translated by Google)
间质性肺疾病的早期诊断对他们的治疗至关重要，但即使是有经验的医生也很难发现，因为他们的临床表现是相似的。为了帮助诊断，开发了计算机辅助诊断（CAD）系统。这些通常依靠固定比例分类器来扫描CT图像，识别肺部纹理并生成病理图谱。在以前的研究中，我们提出了一种使用深度卷积神经网络（CNN）对肺组织模式进行分类的方法，其具有针对特定问题设计的体系结构。在这项研究中，我们提出了一种改进的方法来训练提出的网络，通过传递知识从类似的领域的一般纹理分类。使用六个公开可用的纹理数据库来对所提出的架构进行网络预训练，然后对肺组织数据进行微调。所得到的CNN被合并为一个集合，并且它们的融合知识被压缩回到原始结构的网络。所提出的方法导致提出的CNN的表现绝对增加约2％。结果证明了转移学习在医学图像分析领域的潜力，指出了问题的结构性质，并表明用于训练网络的方法与设计其体系结构一样重要。

##### URL
[https://arxiv.org/abs/1612.02589](https://arxiv.org/abs/1612.02589)

##### PDF
[https://arxiv.org/pdf/1612.02589](https://arxiv.org/pdf/1612.02589)

