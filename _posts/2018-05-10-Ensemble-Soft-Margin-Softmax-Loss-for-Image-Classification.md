---
layout: post
title: "Ensemble Soft-Margin Softmax Loss for Image Classification"
date: 2018-05-10 10:47:13
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification Recognition
author: Xiaobo Wang, Shifeng Zhang, Zhen Lei, Si Liu, Xiaojie Guo, Stan Z. Li
mathjax: true
---

* content
{:toc}

##### Abstract
Softmax loss is arguably one of the most popular losses to train CNN models for image classification. However, recent works have exposed its limitation on feature discriminability. This paper casts a new viewpoint on the weakness of softmax loss. On the one hand, the CNN features learned using the softmax loss are often inadequately discriminative. We hence introduce a soft-margin softmax function to explicitly encourage the discrimination between different classes. On the other hand, the learned classifier of softmax loss is weak. We propose to assemble multiple these weak classifiers to a strong one, inspired by the recognition that the diversity among weak classifiers is critical to a good ensemble. To achieve the diversity, we adopt the Hilbert-Schmidt Independence Criterion (HSIC). Considering these two aspects in one framework, we design a novel loss, named as Ensemble soft-Margin Softmax (EM-Softmax). Extensive experiments on benchmark datasets are conducted to show the superiority of our design over the baseline softmax loss and several state-of-the-art alternatives.

##### Abstract (translated by Google)
Softmax损失可以说是培训CNN模型进行图像分类的最受欢迎的损失之一。然而，最近的作品已经暴露了其对特征可辨性的限制。本文对softmax损失的弱点提出了新的观点。一方面，使用softmax损失学习的CNN特征往往不具有区分性。因此，我们引入了软边缘softmax函数来明确地鼓励不同类别之间的区分。另一方面，softmax损失的学习分类器很弱。我们建议将多个这些弱分类器组合成一个强分类器，这受到了认识，认为弱分类器的多样性对于一个好的合奏系统至关重要。为了实现多样性，我们采用希尔伯特 - 施密特独立准则（HSIC）。在一个框架中考虑这两个方面，我们设计了一个新的损失，命名为Ensemble soft-Margin Softmax（EM-Softmax）。我们对基准数据集进行了大量实验，以显示我们的设计优于基线softmax损耗的优势以及几种最先进的替代方案。

##### URL
[http://arxiv.org/abs/1805.03922](http://arxiv.org/abs/1805.03922)

##### PDF
[http://arxiv.org/pdf/1805.03922](http://arxiv.org/pdf/1805.03922)

