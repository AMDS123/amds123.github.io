---
layout: post
title: "Zero-Shot Sketch-Image Hashing"
date: 2018-03-06 16:23:44
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Knowledge Represenation_Learning Relation
author: Yuming Shen, Li Liu, Fumin Shen, Ling Shao
mathjax: true
---

* content
{:toc}

##### Abstract
Recent studies show that large-scale sketch-based image retrieval (SBIR) can be efficiently tackled by cross-modal binary representation learning methods, where Hamming distance matching significantly speeds up the process of similarity search. Providing training and test data subjected to a fixed set of pre-defined categories, the cutting-edge SBIR and cross-modal hashing works obtain acceptable retrieval performance. However, most of the existing methods fail when the categories of query sketches have never been seen during training. In this paper, the above problem is briefed as a novel but realistic zero-shot SBIR hashing task. We elaborate the challenges of this special task and accordingly propose a zero-shot sketch-image hashing (ZSIH) model. An end-to-end three-network architecture is built, two of which are treated as the binary encoders. The third network mitigates the sketch-image heterogeneity and enhances the semantic relations among data by utilizing the Kronecker fusion layer and graph convolution, respectively. As an important part of ZSIH, we formulate a generative hashing scheme in reconstructing semantic knowledge representations for zero-shot retrieval. To the best of our knowledge, ZSIH is the first zero-shot hashing work suitable for SBIR and cross-modal search. Comprehensive experiments are conducted on two extended datasets, i.e., Sketchy and TU-Berlin with a novel zero-shot train-test split. The proposed model remarkably outperforms related works.

##### Abstract (translated by Google)
最近的研究表明，大规模的基于草图的图像检索（SBIR）可以通过跨模态二进制表示学习方法有效解决，其中汉明距离匹配显着加快了相似性搜索过程。提供的训练和测试数据受到一组固定的预定义类别的限制，尖端的SBIR和跨模式散列工作可获得可接受的检索性能。然而，当在训练期间从未看到查询草图的类别时，大多数现有方法失败。在本文中，上述问题被简单描述为一种新颖而实际的零点SBIR哈希任务。我们详细阐述了这个特殊任务的挑战，并相应地提出了零镜头草图哈希（ZSIH）模型。建立了一个端到端的三网络架构，其中两个被视为二进制编码器。第三个网络分别利用Kronecker融合层和图卷积，缓解了草图异质性，增强了数据之间的语义关系。作为ZSIH的一个重要组成部分，我们制定了一个生成哈希方案来重构零镜头检索的语义知识表示。据我们所知，ZSIH是第一个适用于SBIR和跨模式搜索的零镜散列工作。对两个扩展数据集进行了全面的实验，即Sketchy和TU-Berlin采用了新颖的零点火车测试分割。提出的模型显着优于相关作品。

##### URL
[http://arxiv.org/abs/1803.02284](http://arxiv.org/abs/1803.02284)

##### PDF
[http://arxiv.org/pdf/1803.02284](http://arxiv.org/pdf/1803.02284)

