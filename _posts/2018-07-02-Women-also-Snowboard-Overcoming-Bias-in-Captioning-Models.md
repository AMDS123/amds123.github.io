---
layout: post
title: "Women also Snowboard: Overcoming Bias in Captioning Models"
date: 2018-07-02 08:15:11
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption Prediction
author: Lisa Anne Hendricks, Kaylee Burns, Kate Saenko, Trevor Darrell, Anna Rohrbach
mathjax: true
---

* content
{:toc}

##### Abstract
Most machine learning methods are known to capture and exploit biases of the training data. While some biases are beneficial for learning, others are harmful. Specifically, image captioning models tend to exaggerate biases present in training data. This can lead to incorrect captions in domains where unbiased captions are desired, or required, due to over reliance on the learned prior and image context. We investigate generation of gender specific caption words (e.g. man, woman) based on the person's appearance or the image context. We introduce a new Equalizer model that ensures equal gender probability when gender evidence is occluded in a scene and confident predictions when gender evidence is present. The resulting model is forced to look at a person rather than use contextual cues to make a gender specific prediction. The losses that comprise our model, the Appearance Confusion Loss and the Confident Loss, are general, and can be added to any description model in order to mitigate impacts of unwanted bias in a description dataset. Our proposed model has lower error than prior work when describing images with people and mentioning their gender and more closely matches the ground truth ratio of sentences including women to sentences including men.

##### Abstract (translated by Google)
已知大多数机器学习方法捕获和利用训练数据的偏差。虽然一些偏见有利于学习，但其他偏见是有害的。具体而言，图像字幕模型倾向于夸大训练数据中存在的偏差。由于过度依赖学习的先前和图像上下文，这可能导致需要或需要无偏字幕的域中的字幕不正确。我们根据人的外表或图像背景调查性别特定字幕词（例如男人，女人）的生成。我们引入了一种新的均衡器模型，该模型可确保在场景中出现性别证据时保持相同的性别概率，并在出现性别证据时进行自信的预测。由此产生的模型被迫查看一个人，而不是使用上下文提示来进行性别特定的预测。构成我们模型的损失，外观混淆损失和置信损失，是一般性的，可以添加到任何描述模型中，以减轻描述数据集中不需要的偏差的影响。我们提出的模型在与人们描述图像并提及他们的性别时比先前的工作具有更低的误差，并且更接近地匹配包括女性在内的句子（包括男性）在内的句子的真实比率。

##### URL
[https://arxiv.org/abs/1807.00517](https://arxiv.org/abs/1807.00517)

##### PDF
[https://arxiv.org/pdf/1807.00517](https://arxiv.org/pdf/1807.00517)

