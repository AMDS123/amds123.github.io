---
layout: post
title: "Knowledge-Embedded Representation Learning for Fine-Grained Image Recognition"
date: 2018-07-02 07:49:06
categories: arXiv_CV
tags: arXiv_CV Knowledge_Graph Knowledge GAN Image_Classification Represenation_Learning Classification Recognition
author: Tianshui Chen, Liang Lin, Riquan Chen, Yang Wu, Xiaonan Luo
mathjax: true
---

* content
{:toc}

##### Abstract
Humans can naturally understand an image in depth with the aid of rich knowledge accumulated from daily lives or professions. For example, to achieve fine-grained image recognition (e.g., categorizing hundreds of subordinate categories of birds) usually requires a comprehensive visual concept organization including category labels and part-level attributes. In this work, we investigate how to unify rich professional knowledge with deep neural network architectures and propose a Knowledge-Embedded Representation Learning (KERL) framework for handling the problem of fine-grained image recognition. Specifically, we organize the rich visual concepts in the form of knowledge graph and employ a Gated Graph Neural Network to propagate node message through the graph for generating the knowledge representation. By introducing a novel gated mechanism, our KERL framework incorporates this knowledge representation into the discriminative image feature learning, i.e., implicitly associating the specific attributes with the feature maps. Compared with existing methods of fine-grained image classification, our KERL framework has several appealing properties: i) The embedded high-level knowledge enhances the feature representation, thus facilitating distinguishing the subtle differences among subordinate categories. ii) Our framework can learn feature maps with a meaningful configuration that the highlighted regions finely accord with the nodes (specific attributes) of the knowledge graph. Extensive experiments on the widely used Caltech-UCSD bird dataset demonstrate the superiority of our KERL framework over existing state-of-the-art methods.

##### Abstract (translated by Google)
借助日常生活或职业积累的丰富知识，人类可以自然地理解深度图像。例如，为了实现细粒度图像识别（例如，对数百个从属类别的鸟类进行分类），通常需要包括类别标签和部分级属性的综合视觉概念组织。在这项工作中，我们研究如何用深度神经网络架构统一丰富的专业知识，并提出一个知识嵌入式表示学习（KERL）框架来处理细粒度图像识别问题。具体来说，我们以知识图的形式组织丰富的视觉概念，并使用门控图神经网络通过图传播节点消息以生成知识表示。通过引入新颖的门控机制，我们的KERL框架将该知识表示结合到辨别图像特征学习中，即隐含地将特定属性与特征图相关联。与现有的细粒度图像分类方法相比，我们的KERL框架具有以下几个吸引人的特性：i）嵌入式高级知识增强了特征表示，从而有助于区分从属类别之间的细微差别。 ii）我们的框架可以学习具有有意义配置的特征映射，突出显示的区域与知识图的节点（特定属性）完全一致。对广泛使用的Caltech-UCSD鸟类数据集进行了大量实验，证明了我们的KERL框架优于现有最先进的方法。

##### URL
[http://arxiv.org/abs/1807.00505](http://arxiv.org/abs/1807.00505)

##### PDF
[http://arxiv.org/pdf/1807.00505](http://arxiv.org/pdf/1807.00505)

