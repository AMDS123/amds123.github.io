---
layout: post
title: "Diverse Image-to-Image Translation via Disentangled Representations"
date: 2018-08-02 17:54:27
categories: arXiv_CV
tags: arXiv_CV Quantitative
author: Hsin-Ying Lee, Hung-Yu Tseng, Jia-Bin Huang, Maneesh Kumar Singh, Ming-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Image-to-image translation aims to learn the mapping between two visual domains. There are two main challenges for many applications: 1) the lack of aligned training pairs and 2) multiple possible outputs from a single input image. In this work, we present an approach based on disentangled representation for producing diverse outputs without paired training images. To achieve diversity, we propose to embed images onto two spaces: a domain-invariant content space capturing shared information across domains and a domain-specific attribute space. Our model takes the encoded content features extracted from a given input and the attribute vectors sampled from the attribute space to produce diverse outputs at test time. To handle unpaired training data, we introduce a novel cross-cycle consistency loss based on disentangled representations. Qualitative results show that our model can generate diverse and realistic images on a wide range of tasks without paired training data. For quantitative comparisons, we measure realism with user study and diversity with a perceptual distance metric. We apply the proposed model to domain adaptation and show competitive performance when compared to the state-of-the-art on the MNIST-M and the LineMod datasets.

##### Abstract (translated by Google)
图像到图像转换旨在学习两个视觉域之间的映射。许多应用存在两个主要挑战：1）缺少对齐的训练对和2）来自单个输入图像的多个可能输出。在这项工作中，我们提出了一种基于解缠表示的方法，用于在没有成对训练图像的情况下产生多样化的输出。为了实现多样性，我们建议将图像嵌入到两个空间中：域不变的内容空间捕获跨域的共享信息和特定于域的属性空间。我们的模型采用从给定输入中提取的编码内容特征和从属性空间采样的属性向量，以在测试时产生不同的输出。为了处理不成对的训练数据，我们引入了基于解开的表示的新的跨周期一致性损失。定性结果表明，我们的模型可以在无需配对训练数据的情况下，在各种任务上生成多样且逼真的图像。对于定量比较，我们使用感知距离度量来衡量用户研究和多样性的真实性。与MNIST-M和LineMod数据集上的最新技术相比，我们将所提出的模型应用于域适应并显示出竞争性能。

##### URL
[http://arxiv.org/abs/1808.00948](http://arxiv.org/abs/1808.00948)

##### PDF
[http://arxiv.org/pdf/1808.00948](http://arxiv.org/pdf/1808.00948)

