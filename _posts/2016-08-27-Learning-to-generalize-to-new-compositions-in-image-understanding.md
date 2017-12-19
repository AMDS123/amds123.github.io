---
layout: post
title: "Learning to generalize to new compositions in image understanding"
date: 2016-08-27 00:34:00
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption RNN Prediction
author: Yuval Atzmon, Jonathan Berant, Vahid Kezami, Amir Globerson, Gal Chechik
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks have recently been used for learning to describe images using natural language. However, it has been observed that these models generalize poorly to scenes that were not observed during training, possibly depending too strongly on the statistics of the text in the training data. Here we propose to describe images using short structured representations, aiming to capture the crux of a description. These structured representations allow us to tease-out and evaluate separately two types of generalization: standard generalization to new images with similar scenes, and generalization to new combinations of known entities. We compare two learning approaches on the MS-COCO dataset: a state-of-the-art recurrent network based on an LSTM (Show, Attend and Tell), and a simple structured prediction model on top of a deep network. We find that the structured model generalizes to new compositions substantially better than the LSTM, ~7 times the accuracy of predicting structured representations. By providing a concrete method to quantify generalization for unseen combinations, we argue that structured representations and compositional splits are a useful benchmark for image captioning, and advocate compositional models that capture linguistic and visual structure.

##### Abstract (translated by Google)
递归神经网络最近被用于学习以使用自然语言描述图像。然而，已经观察到，这些模型对于在训练期间没有观察到的场景的概括性较差，可能过于强烈地依赖于训练数据中的文本的统计。在这里，我们建议使用简短的结构化表示来描述图像，旨在捕捉描述的关键。这些结构化表示允许我们分别梳理和评估两种类型的泛化：标准泛化到具有相似场景的新图像，以及推广到已知实体的新组合。我们比较了MS-COCO数据集上的两种学习方法：一种基于LSTM（Show，Attend和Tell）的最新循环网络，以及一个在深度网络之上的简单结构化预测模型。我们发现结构化模型比LSTM更容易推广到新组合，这是预测结构化表示准确性的7倍。通过提供具体的方法来量化看不见的组合的泛化，我们认为结构化表示和组合分割是图像字幕的有用基准，并提倡捕捉语言和视觉结构的组合模型。

##### URL
[https://arxiv.org/abs/1608.07639](https://arxiv.org/abs/1608.07639)

##### PDF
[https://arxiv.org/pdf/1608.07639](https://arxiv.org/pdf/1608.07639)

