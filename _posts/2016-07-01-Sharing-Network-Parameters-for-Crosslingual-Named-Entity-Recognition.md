---
layout: post
title: "Sharing Network Parameters for Crosslingual Named Entity Recognition"
date: 2016-07-01 10:35:59
categories: arXiv_CL
tags: arXiv_CL Recognition
author: Rudra Murthy V, Mitesh Khapra, Pushpak Bhattacharyya
mathjax: true
---

* content
{:toc}

##### Abstract
Most state of the art approaches for Named Entity Recognition rely on hand crafted features and annotated corpora. Recently Neural network based models have been proposed which do not require handcrafted features but still require annotated corpora. However, such annotated corpora may not be available for many languages. In this paper, we propose a neural network based model which allows sharing the decoder as well as word and character level parameters between two languages thereby allowing a resource fortunate language to aid a resource deprived language. Specifically, we focus on the case when limited annotated corpora is available in one language ($L_1$) and abundant annotated corpora is available in another language ($L_2$). Sharing the network architecture and parameters between $L_1$ and $L_2$ leads to improved performance in $L_1$. Further, our approach does not require any hand crafted features but instead directly learns meaningful feature representations from the training data itself. We experiment with 4 language pairs and show that indeed in a resource constrained setup (lesser annotated corpora), a model jointly trained with data from another language performs better than a model trained only on the limited corpora in one language.

##### Abstract (translated by Google)
命名实体识别的大多数最先进的方法依赖于手工制作的特征和注释的语料库。目前已经提出了基于神经网络的模型，其不需要手工特征，但仍需要注释的语料库。但是，这样的注释语料库可能不适用于多种语言。在本文中，我们提出了一个基于神经网络的模型，它允许在两种语言之间共享解码器以及字和字符级参数，从而允许资源幸运语言帮助资源剥夺语言。具体来说，我们重点关注一种语言（$ L_1 $）有限注释语料库可用的情况，以另一种语言（$ L_2 $）提供大量注释语料库。在$ L_1 $和$ L_2 $之间共享网络体系结构和参数可以提高$ L_1 $的性能。此外，我们的方法不需要任何手工制作的特征，而是直接从训练数据本身获得有意义的特征表示。我们用4个语言对进行实验，结果表明，在一个资源受限的语料库（较少注释的语料库）中，与另一种语言的数据联合训练的模型比只使用一种语言的有限语料库训练的模型更好。

##### URL
[https://arxiv.org/abs/1607.00198](https://arxiv.org/abs/1607.00198)

##### PDF
[https://arxiv.org/pdf/1607.00198](https://arxiv.org/pdf/1607.00198)

