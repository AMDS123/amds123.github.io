---
layout: post
title: "Joint Intermodal and Intramodal Label Transfers for Extremely Rare or Unseen Classes"
date: 2017-03-22 04:40:51
categories: arXiv_CV
tags: arXiv_CV Text_Classification Image_Classification Classification Relation
author: Guo-Jun Qi, Wei Liu, Charu Aggarwal, Thomas Huang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a label transfer model from texts to images for image classification tasks. The problem of image classification is often much more challenging than text classification. On one hand, labeled text data is more widely available than the labeled images for classification tasks. On the other hand, text data tends to have natural semantic interpretability, and they are often more directly related to class labels. On the contrary, the image features are not directly related to concepts inherent in class labels. One of our goals in this paper is to develop a model for revealing the functional relationships between text and image features as to directly transfer intermodal and intramodal labels to annotate the images. This is implemented by learning a transfer function as a bridge to propagate the labels between two multimodal spaces. However, the intermodal label transfers could be undermined by blindly transferring the labels of noisy texts to annotate images. To mitigate this problem, we present an intramodal label transfer process, which complements the intermodal label transfer by transferring the image labels instead when relevant text is absent from the source corpus. In addition, we generalize the inter-modal label transfer to zero-shot learning scenario where there are only text examples available to label unseen classes of images without any positive image examples. We evaluate our algorithm on an image classification task and show the effectiveness with respect to the other compared algorithms.

##### Abstract (translated by Google)
在本文中，我们提出了一个从文本到图像的图像分类任务的标签传输模型。图像分类的问题通常比文本分类更具挑战性。一方面，标记的文本数据比标记的图像更广泛地用于分类任务。另一方面，文本数据倾向于具有自然的语义解释性，而且往往与类标签更直接相关。相反，图像特征与类标签中固有的概念并不直接相关。本文的目的之一是建立一个揭示文本和图像特征之间的函数关系的模型，以直接转移联运和模式间的标签来标注图像。这是通过学习传递函数作为在两个多模式空间之间传播标签的桥梁来实现的。但是，通过盲目地传送嘈杂文本的标签来标注图像，可能会破坏联运标签的传输。为了缓解这个问题，我们提出了一个模式间的标签传输过程，它补充了联运标签传输，当源语料库中没有相关的文本时，通过传输图像标签来代替。另外，我们将模式间的标签转移概括为零射击的学习场景，其中只有文本示例可用于标记看不见的图像类别，而没有任何正面的图像示例。我们评估我们的算法的图像分类任务，并显示其他比较算法的有效性。

##### URL
[https://arxiv.org/abs/1703.07519](https://arxiv.org/abs/1703.07519)

##### PDF
[https://arxiv.org/pdf/1703.07519](https://arxiv.org/pdf/1703.07519)

