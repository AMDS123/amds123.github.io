---
layout: post
title: "Attributes as Operators"
date: 2018-03-27 02:30:56
categories: arXiv_CV
tags: arXiv_CV Embedding
author: Tushar Nagarajan, Kristen Grauman
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new approach to modeling visual attributes. Prior work casts attributes in a similar role as objects, learning a latent representation where properties (e.g., sliced) are recognized by classifiers much in the way objects (e.g., apple) are. However, this common approach fails to separate the attributes observed during training from the objects with which they are composed, making it ineffectual when encountering new attribute-object compositions. Instead, we propose to model attributes as operators. Our approach learns a semantic embedding that explicitly factors out attributes from their accompanying objects, and also benefits from novel regularizers expressing attribute operators' effects (e.g., blunt should undo the effects of sharp). Not only does our approach align conceptually with the linguistic role of attributes as modifiers, but it also generalizes to recognize unseen compositions of objects and attributes. We validate our approach on two challenging datasets and demonstrate significant improvements over the state-of-the-art. In addition, we show that not only can our model recognize unseen compositions robustly in an open-world setting, it can also generalize to compositions where objects themselves were unseen during training.

##### Abstract (translated by Google)
我们提出了一种新的方法来建模视觉属性。先前的工作将属性转换为与对象类似的角色，学习潜在表示，其中属性（例如，切片）被分类器以对象（例如，苹果）的方式识别得很多。然而，这种常用方法未能将训练期间观察到的属性与构成它们的对象分开，使得在遇到新的属性 - 对象组合时效果不佳。相反，我们建议将属性建模为运算符。我们的方法学习语义嵌入，明确地从其伴随对象中提取属性，并且还受益于表达属性操作符效果的新型正规化器（例如，钝器应该消除尖锐效应）。我们的方法不仅在概念上与作为修饰符的属性的语言角色相一致，而且还泛化为识别看不见的对象和属性组合。我们在两个具有挑战性的数据集上验证了我们的方法，并证明了对最先进的技术的重大改进。此外，我们表明，我们的模型不仅可以在开放的世界环境中鲁棒地识别看不见的成分，还可以推广到其中物体本身在训练期间看不见的组合物。

##### URL
[https://arxiv.org/abs/1803.09851](https://arxiv.org/abs/1803.09851)

##### PDF
[https://arxiv.org/pdf/1803.09851](https://arxiv.org/pdf/1803.09851)

