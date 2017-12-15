---
layout: post
title: "Visual Relationship Detection with Language Priors"
date: 2016-07-31 05:54:13
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Embedding Detection Relation
author: Cewu Lu, Ranjay Krishna, Michael Bernstein, Li Fei-Fei
mathjax: true
---

* content
{:toc}

##### Abstract
Visual relationships capture a wide variety of interactions between pairs of objects in images (e.g. "man riding bicycle" and "man pushing bicycle"). Consequently, the set of possible relationships is extremely large and it is difficult to obtain sufficient training examples for all possible relationships. Because of this limitation, previous work on visual relationship detection has concentrated on predicting only a handful of relationships. Though most relationships are infrequent, their objects (e.g. "man" and "bicycle") and predicates (e.g. "riding" and "pushing") independently occur more frequently. We propose a model that uses this insight to train visual models for objects and predicates individually and later combines them together to predict multiple relationships per image. We improve on prior work by leveraging language priors from semantic word embeddings to finetune the likelihood of a predicted relationship. Our model can scale to predict thousands of types of relationships from a few examples. Additionally, we localize the objects in the predicted relationships as bounding boxes in the image. We further demonstrate that understanding relationships can improve content based image retrieval.

##### Abstract (translated by Google)
视觉关系捕捉图像中的对象之间的各种各样的交互（例如“男子骑自行车”和“男子推自行车”）。因此，这组可能的关系是非常大的，很难为所有可能的关系获得足够的训练样本。由于这个限制，以前关于视觉关系检测的工作集中在预测一小部分关系上。尽管大多数关系并不频繁，但它们的对象（例如“人”和“自行车”）和谓词（例如“骑乘”和“推”）独立地更频繁地发生。我们提出了一个使用这种洞察力的模型来单独训练对象和谓词的可视化模型，然后将它们结合在一起以预测每个图像的多重关系。我们通过利用来自语义词嵌入的语言先验来优化之前的工作，以微调预测关系的可能性。我们的模型可以通过几个例子来扩展以预测成千上万种类型的关系。此外，我们将预测关系中的对象本地化为图像中的边界框。我们进一步证明理解关系可以改善基于内容的图像检索。

##### URL
[https://arxiv.org/abs/1608.00187](https://arxiv.org/abs/1608.00187)

##### PDF
[https://arxiv.org/pdf/1608.00187](https://arxiv.org/pdf/1608.00187)

