---
layout: post
title: "Multi-GPU Distributed Parallel Bayesian Differential Topic Modelling"
date: 2015-10-22 09:40:54
categories: arXiv_CL
tags: arXiv_CL Salient Knowledge
author: Aaron Q Li
mathjax: true
---

* content
{:toc}

##### Abstract
There is an explosion of data, documents, and other content, and people require tools to analyze and interpret these, tools to turn the content into information and knowledge. Topic modeling have been developed to solve these problems. Topic models such as LDA [Blei et. al. 2003] allow salient patterns in data to be extracted automatically. When analyzing texts, these patterns are called topics. Among numerous extensions of LDA, few of them can reliably analyze multiple groups of documents and extract topic similarities. Recently, the introduction of differential topic modeling (SPDP) [Chen et. al. 2012] performs uniformly better than many topic models in a discriminative setting. There is also a need to improve the sampling speed for topic models. While some effort has been made for distributed algorithms, there is no work currently done using graphical processing units (GPU). Note the GPU framework has already become the most cost-efficient platform for many problems. In this thesis, I propose and implement a scalable multi-GPU distributed parallel framework which approximates SPDP. Through experiments, I have shown my algorithms have a gain in speed of about 50 times while being almost as accurate, with only one single cheap laptop GPU. Furthermore, I have shown the speed improvement is sublinearly scalable when multiple GPUs are used, while fairly maintaining the accuracy. Therefore on a medium-sized GPU cluster, the speed improvement could potentially reach a factor of a thousand. Note SPDP is just a representative of other extensions of LDA. Although my algorithm is implemented to work with SPDP, it is designed to be a general enough to work with other topic models. The speed-up on smaller collections (i.e., 1000s of documents), means that these more complex LDA extensions could now be done in real-time, thus opening up a new way of using these LDA models in industry.

##### Abstract (translated by Google)
数据，文档和其他内容大量涌现，人们需要工具来分析和解释这些工具，以将内容转化为信息和知识。主题建模已经被开发出来解决这些问题。主题模型，如LDA [Blei et。人。 2003]允许数据中的显着模式被自动提取。分析文本时，这些模式称为主题。在众多的LDA扩展中，很少能够可靠地分析多组文档并提取主题相似之处。最近，引入差异主题建模（SPDP）[Chen et。人。 2012]在歧视性的环境中比许多话题模型更好地执行。还需要提高话题模型的采样速度。虽然已经为分布式算法做了一些努力，但是目前没有使用图形处理单元（GPU）完成的工作。请注意，GPU框架已经成为许多问题的最具成本效益的平台。在本文中，我提出并实现了一个可扩展的多GPU分布式并行框架，它近似于SPDP。通过实验，我发现我的算法速度提高了大约50倍，几乎同样精确，只有一台便宜的笔记本电脑GPU。此外，我已经表明，在使用多个GPU的情况下，速度改进是次线性可扩展的，同时相当保持准确性。因此，在一个中等规模的GPU集群上，速度的提升有可能达到千分之一。注意SPDP只是LDA其他扩展的代表。尽管我的算法实现了与SPDP一起工作，但它的设计足以与其他主题模型一起工作。在较小的集合（即1000个文档）上的加速意味着这些更复杂的LDA扩展现在可以实时完成，从而为工业上使用这些LDA模型开辟了一条新途径。

##### URL
[https://arxiv.org/abs/1510.06549](https://arxiv.org/abs/1510.06549)

##### PDF
[https://arxiv.org/pdf/1510.06549](https://arxiv.org/pdf/1510.06549)

