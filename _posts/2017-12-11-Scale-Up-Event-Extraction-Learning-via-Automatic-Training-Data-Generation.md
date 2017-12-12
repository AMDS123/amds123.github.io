---
layout: post
title: "Scale Up Event Extraction Learning via Automatic Training Data Generation"
date: 2017-12-11 07:41:28
categories: arXiv_CL
tags: arXiv_CL Knowledge Inference
author: Ying Zeng, Yansong Feng, Rong Ma, Zheng Wang, Rui Yan, Chongde Shi, Dongyan Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
The task of event extraction has long been investigated in a supervised learning paradigm, which is bound by the number and the quality of the training instances. Existing training data must be manually generated through a combination of expert domain knowledge and extensive human involvement. However, due to drastic efforts required in annotating text, the resultant datasets are usually small, which severally affects the quality of the learned model, making it hard to generalize. Our work develops an automatic approach for generating training data for event extraction. Our approach allows us to scale up event extraction training instances from thousands to hundreds of thousands, and it does this at a much lower cost than a manual approach. We achieve this by employing distant supervision to automatically create event annotations from unlabelled text using existing structured knowledge bases or tables.We then develop a neural network model with post inference to transfer the knowledge extracted from structured knowledge bases to automatically annotate typed events with corresponding arguments in text.We evaluate our approach by using the knowledge extracted from Freebase to label texts from Wikipedia articles. Experimental results show that our approach can generate a large number of high quality training instances. We show that this large volume of training data not only leads to a better event extractor, but also allows us to detect multiple typed events.

##### Abstract (translated by Google)
事件抽取的任务一直在受监督的学习范式中进行调查，这受到训练实例的数量和质量的约束。现有的训练数据必须通过结合专家领域知识和广泛的人员参与手动生成。然而，由于注解文本需要大量的努力，所得到的数据集通常很小，这对于学习模型的质量有很大的影响，很难一概而论。我们的工作开发了一种自动方法来生成事件提取的训练数据。我们的方法允许我们将事件提取培训实例从数千个扩展到数十万个，而且这个方法的成本要比人工方法低得多。我们通过使用远程监督来使用现有的结构化知识库或表格来自动创建来自未标记文本的事件注释来实现这一点。然后，我们开发了一个带有推后的神经网络模型，以将从结构化知识库中提取的知识转移到具有相应参数的自动注释类型事件我们通过使用从Freebase提取的知识来标记维基百科文章中的文本来评估我们的方法。实验结果表明，我们的方法可以产生大量的高质量的训练实例。我们显示，这个大量的训练数据不仅导致更好的事件提取器，而且还允许我们检测多个类型的事件。

##### URL
[http://arxiv.org/abs/1712.03665](http://arxiv.org/abs/1712.03665)

##### PDF
[http://arxiv.org/pdf/1712.03665](http://arxiv.org/pdf/1712.03665)

