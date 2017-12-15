---
layout: post
title: "Classifying Relations by Ranking with Convolutional Neural Networks"
date: 2015-05-24 13:58:05
categories: arXiv_CL
tags: arXiv_CL Embedding CNN Classification Relation
author: Cicero Nogueira dos Santos, Bing Xiang, Bowen Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Relation classification is an important semantic processing task for which state-ofthe-art systems still rely on costly handcrafted features. In this work we tackle the relation classification task using a convolutional neural network that performs classification by ranking (CR-CNN). We propose a new pairwise ranking loss function that makes it easy to reduce the impact of artificial classes. We perform experiments using the the SemEval-2010 Task 8 dataset, which is designed for the task of classifying the relationship between two nominals marked in a sentence. Using CRCNN, we outperform the state-of-the-art for this dataset and achieve a F1 of 84.1 without using any costly handcrafted features. Additionally, our experimental results show that: (1) our approach is more effective than CNN followed by a softmax classifier; (2) omitting the representation of the artificial class Other improves both precision and recall; and (3) using only word embeddings as input features is enough to achieve state-of-the-art results if we consider only the text between the two target nominals.

##### Abstract (translated by Google)
关系分类是一个重要的语义处理任务，最先进的系统仍然依赖昂贵的手工功能。在这项工作中，我们使用卷积神经网络（CR-CNN）进行关系分类任务。我们提出了一个新的两两排序损失函数，可以很容易地减少人工类的影响。我们使用SemEval-2010任务8数据集进行实验，这个数据集是为分类两个在句子中标注的名词之间的关系而设计的。使用CRCNN，我们超越了这个数据集的最新水平，实现了84.1的F1，而无需使用任何昂贵的手工功能。另外，我们的实验结果表明：（1）我们的方法比CNN和softmax分类器更有效; （2）省略人工类别的表示其他提高精度和召回率; （3）如果仅考虑两个目标名词之间的文本，只使用词嵌入作为输入特征就足以达到最新的结果。

##### URL
[https://arxiv.org/abs/1504.06580](https://arxiv.org/abs/1504.06580)

##### PDF
[https://arxiv.org/pdf/1504.06580](https://arxiv.org/pdf/1504.06580)

