---
layout: post
title: "Transductive Zero-Shot Hashing via Coarse-to-Fine Similarity Mining"
date: 2017-11-08 07:46:47
categories: arXiv_CV
tags: arXiv_CV Image_Caption Knowledge Transfer_Learning
author: Hanjiang Lai, Yan Pan
mathjax: true
---

* content
{:toc}

##### Abstract
Zero-shot Hashing (ZSH) is to learn hashing models for novel/target classes without training data, which is an important and challenging problem. Most existing ZSH approaches exploit transfer learning via an intermediate shared semantic representations between the seen/source classes and novel/target classes. However, due to having disjoint, the hash functions learned from the source dataset are biased when applied directly to the target classes. In this paper, we study the transductive ZSH, i.e., we have unlabeled data for novel classes. We put forward a simple yet efficient joint learning approach via coarse-to-fine similarity mining which transfers knowledges from source data to target data. It mainly consists of two building blocks in the proposed deep architecture: 1) a shared two-streams network, which the first stream operates on the source data and the second stream operates on the unlabeled data, to learn the effective common image representations, and 2) a coarse-to-fine module, which begins with finding the most representative images from target classes and then further detect similarities among these images, to transfer the similarities of the source data to the target data in a greedy fashion. Extensive evaluation results on several benchmark datasets demonstrate that the proposed hashing method achieves significant improvement over the state-of-the-art methods.

##### Abstract (translated by Google)
零射影哈希（Zero-Hash Hashing，ZSH）是在没有训练数据的情况下为新奇/目标类别学习哈希模型，这是一个重要且具有挑战性的问题。大多数现有的ZSH方法通过在看到/源类和新/目标类之间的中间共享语义表示来利用转移学习。但是，由于不相交，从源数据集中学习到的哈希函数在直接应用到目标类时会有偏差。在本文中，我们研究了换能ZSH，也就是说，我们有新类的未标记数据。我们提出了一个简单而有效的联合学习方法，通过从源数据向目标数据传输知识的粗到细的相似性挖掘。它主要由两个构建块组成：1）一个共享的双流网络，第一个流对源数据进行操作，第二个流对未标记的数据进行操作，以学习有效的共同图像表示; 2）从粗到精的模块，首先从目标类别中找到最具代表性的图像，然后进一步检测这些图像之间的相似性，以贪婪的方式将源数据的相似性转移到目标数据。在几个基准数据集上的广泛的评估结果表明，所提出的哈希方法比现有技术的方法实现了显着的改进。

##### URL
[https://arxiv.org/abs/1711.02856](https://arxiv.org/abs/1711.02856)

##### PDF
[https://arxiv.org/pdf/1711.02856](https://arxiv.org/pdf/1711.02856)

