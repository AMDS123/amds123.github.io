---
layout: post
title: "Reasoning about Fine-grained Attribute Phrases using Reference Games"
date: 2017-08-29 16:57:39
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Embedding
author: Jong-Chyi Su, Chenyun Wu, Huaizu Jiang, Subhransu Maji
mathjax: true
---

* content
{:toc}

##### Abstract
We present a framework for learning to describe fine-grained visual differences between instances using attribute phrases. Attribute phrases capture distinguishing aspects of an object (e.g., "propeller on the nose" or "door near the wing" for airplanes) in a compositional manner. Instances within a category can be described by a set of these phrases and collectively they span the space of semantic attributes for a category. We collect a large dataset of such phrases by asking annotators to describe several visual differences between a pair of instances within a category. We then learn to describe and ground these phrases to images in the context of a *reference game* between a speaker and a listener. The goal of a speaker is to describe attributes of an image that allows the listener to correctly identify it within a pair. Data collected in a pairwise manner improves the ability of the speaker to generate, and the ability of the listener to interpret visual descriptions. Moreover, due to the compositionality of attribute phrases, the trained listeners can interpret descriptions not seen during training for image retrieval, and the speakers can generate attribute-based explanations for differences between previously unseen categories. We also show that embedding an image into the semantic space of attribute phrases derived from listeners offers 20% improvement in accuracy over existing attribute-based representations on the FGVC-aircraft dataset.

##### Abstract (translated by Google)
我们提出了一个学习框架来描述使用属性短语的实例之间的细粒度视觉差异。属性短语以组合方式捕捉对象的区别方面（例如，飞机上的“螺旋桨在机头上”或“在机翼附近的机翼”）。一个类别中的实例可以用一组这些短语来描述，并且它们共同跨越一个类别的语义属性的空间。我们通过要求注释者描述一个类别内的一对实例之间的几个视觉差异来收集这样的短语的大数据集。然后，我们学会在发言者和听众之间的*参考游戏*的背景下，将这些短语描述和映射到图像。演讲者的目标是描述一个图像的属性，允许听众在一对中正确识别它。以成对方式收集的数据提高了说话者生成的能力，以及聆听者解释视觉描述的能力。此外，由于属性短语的组成性，训练的听众可以解释训练期间在图像检索过程中看不到的描述，并且讲话者可以针对之前看不见的类别之间的差异产生基于属性的解释。我们还表明，将图像嵌入到从听众派生的属性短语的语义空间中，与FGVC-飞机数据集上现有的基于属性的表示相比，精度提高了20％。

##### URL
[https://arxiv.org/abs/1708.08874](https://arxiv.org/abs/1708.08874)

##### PDF
[https://arxiv.org/pdf/1708.08874](https://arxiv.org/pdf/1708.08874)

