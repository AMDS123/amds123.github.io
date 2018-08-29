---
layout: post
title: "Attributes as Operators: Factorizing Unseen Attribute-Object Compositions"
date: 2018-08-27 19:33:30
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
我们提出了一种新的视觉属性建模方法。先前的工作以与对象类似的角色投射属性，学习潜在表示，其中属性（例如，切片）被对象（例如，苹果）的方式很多地被分类器识别。然而，这种常见的方法无法将训练期间观察到的属性与组成它们的对象分开，使其在遇到新的属性 - 对象组合时无效。相反，我们建议将属性建模为运算符。我们的方法学习语义嵌入，明确地从其伴随对象中分解出属性，并且还受益于表达属性操作符效果的新型正则化器（例如，钝器应该消除尖锐的影响）。我们的方法不仅在概念上与属性作为修饰语的语言角色保持一致，而且还概括为识别对象和属性的看不见的组合。我们在两个具有挑战性的数据集上验证了我们的方法，并展示了对最先进技术的重大改进。此外，我们表明，我们的模型不仅可以在开放世界环境中强有力地识别看不见的成分，还可以推广到在训练期间看不到物体本身的成分。

##### URL
[http://arxiv.org/abs/1803.09851](http://arxiv.org/abs/1803.09851)

##### PDF
[http://arxiv.org/pdf/1803.09851](http://arxiv.org/pdf/1803.09851)

