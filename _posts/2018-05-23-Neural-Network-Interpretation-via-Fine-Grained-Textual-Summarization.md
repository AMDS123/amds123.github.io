---
layout: post
title: "Neural Network Interpretation via Fine Grained Textual Summarization"
date: 2018-05-23 05:54:15
categories: arXiv_CV
tags: arXiv_CV Image_Caption Image_Retrieval Summarization Caption Inference Classification Prediction
author: Pei Guo, Connor Anderson, Kolten Pearson, Ryan Farrell
mathjax: true
---

* content
{:toc}

##### Abstract
Current visualization based network interpretation methodssuffer from lacking semantic-level information. In this paper, we introduce the novel task of interpreting classification models using fine grained textual summarization. Along with the label prediction, the network will generate a sentence explaining its decision. Constructing a fully annotated dataset of filter|text pairs is unrealistic because of image to filter response function complexity. We instead propose a weakly-supervised learning algorithm leveraging off-the-shelf image caption annotations. Central to our algorithm is the filter-level attribute probability density function (PDF), learned as a conditional probability through Bayesian inference with the input image and its feature map as latent variables. We show our algorithm faithfully reflects the features learned by the model using rigorous applications like attribute based image retrieval and unsupervised text grounding. We further show that the textual summarization process can help in understanding network failure patterns and can provide clues for further improvements.

##### Abstract (translated by Google)
目前的基于可视化的网络解释方法，由于缺乏语义层次的信息，在本文中，我们介绍了使用细粒度文本摘要来解释分类模型的新任务。随着标签预测，网络将生成一个解释其决定的句子。由于图像过滤响应函数的复杂性，因此构造完整注释的过滤器|文本对的数据集是不现实的。相反，我们提出了一种利用现成图像标题注释的弱监督学习算法。我们算法的核心是滤波器级属性概率密度函数（PDF），通过贝叶斯推理将输入图像及其特征图作为潜在变量作为条件概率学习。我们展示了我们的算法忠实地反映了模型使用基于属性的图像检索和无监督文本接地等严格应用学习的特征。我们进一步表明，文本摘要过程可以帮助理解网络故障模式，并可以提供进一步改进的线索。

##### URL
[http://arxiv.org/abs/1805.08969](http://arxiv.org/abs/1805.08969)

##### PDF
[http://arxiv.org/pdf/1805.08969](http://arxiv.org/pdf/1805.08969)

