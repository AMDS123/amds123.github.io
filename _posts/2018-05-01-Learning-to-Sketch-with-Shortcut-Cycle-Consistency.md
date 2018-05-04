---
layout: post
title: "Learning to Sketch with Shortcut Cycle Consistency"
date: 2018-05-01 09:13:14
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Quantitative
author: Jifei Song, Kaiyue Pang, Yi-Zhe Song, Tao Xiang, Timothy Hospedales
mathjax: true
---

* content
{:toc}

##### Abstract
To see is to sketch -- free-hand sketching naturally builds ties between human and machine vision. In this paper, we present a novel approach for translating an object photo to a sketch, mimicking the human sketching process. This is an extremely challenging task because the photo and sketch domains differ significantly. Furthermore, human sketches exhibit various levels of sophistication and abstraction even when depicting the same object instance in a reference photo. This means that even if photo-sketch pairs are available, they only provide weak supervision signal to learn a translation model. Compared with existing supervised approaches that solve the problem of D(E(photo)) -> sketch, where E($\cdot$) and D($\cdot$) denote encoder and decoder respectively, we take advantage of the inverse problem (e.g., D(E(sketch)) -> photo), and combine with the unsupervised learning tasks of within-domain reconstruction, all within a multi-task learning framework. Compared with existing unsupervised approaches based on cycle consistency (i.e., D(E(D(E(photo)))) -> photo), we introduce a shortcut consistency enforced at the encoder bottleneck (e.g., D(E(photo)) -> photo) to exploit the additional self-supervision. Both qualitative and quantitative results show that the proposed model is superior to a number of state-of-the-art alternatives. We also show that the synthetic sketches can be used to train a better fine-grained sketch-based image retrieval (FG-SBIR) model, effectively alleviating the problem of sketch data scarcity.

##### Abstract (translated by Google)
看到的是素描 - 自由手写草图自然地建立人与机器视觉之间的联系。在本文中，我们提出了一种将对象照片翻译为草图的新颖方法，模仿人类草图绘制过程。这是一项非常具有挑战性的任务，因为照片和素描域的差异很大。此外，即使在参考照片中描绘相同的对象实例时，人体草图也展现出不同程度的复杂性和抽象性。这意味着即使有照片素描对，他们也只能提供弱的监督信号来学习翻译模型。与现有的解决D（E（照片）） - >草图的监督方法相比，E（$ \ cdot $）和D（$ \ cdot $）分别表示编码器和解码器，我们利用逆问题（例如，D（E（草图）） - >照片），并且与无监督的域内重建学习任务相结合，所有这些都在多任务学习框架内。与基于循环一致性的现有无监督方法（即D（E（D（E（photo）））） - > photo）相比，我们引入了在编码器瓶颈处强制执行的快捷方式一致性（例如D（E（photo）） - >照片）利用额外的自我监督。定性和定量结果都表明，所提出的模型优于一些最先进的替代方案。我们还表明，合成草图可用于训练更好的细粒度草图图像检索（FG-SBIR）模型，有效缓解草图数据稀缺的问题。

##### URL
[https://arxiv.org/abs/1805.00247](https://arxiv.org/abs/1805.00247)

##### PDF
[https://arxiv.org/pdf/1805.00247](https://arxiv.org/pdf/1805.00247)

