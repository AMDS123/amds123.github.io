---
layout: post
title: "Women also Snowboard: Overcoming Bias in Captioning Models"
date: 2018-03-26 19:07:08
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption Prediction
author: Kaylee Burns, Lisa Anne Hendricks, Trevor Darrell, Anna Rohrbach
mathjax: true
---

* content
{:toc}

##### Abstract
Most machine learning methods are known to capture and exploit biases of the training data. While some biases are beneficial for learning, others are harmful. Specifically, image captioning models tend to exaggerate biases present in training data (e.g., if a word is present in 60% of training sentences, it might be predicted in 70% of sentences at test time). This can lead to incorrect captions in domains where unbiased captions are desired, or required, due to over-reliance on the learned prior and image context. In this work we investigate generation of gender-specific caption words (e.g. man, woman) based on the person's appearance or the image context. We introduce a new Equalizer model that ensures equal gender probability when gender evidence is occluded in a scene and confident predictions when gender evidence is present. The resulting model is forced to look at a person rather than use contextual cues to make a gender-specific predictions. The losses that comprise our model, the Appearance Confusion Loss and the Confident Loss, are general, and can be added to any description model in order to mitigate impacts of unwanted bias in a description dataset. Our proposed model has lower error than prior work when describing images with people and mentioning their gender and more closely matches the ground truth ratio of sentences including women to sentences including men. We also show that unlike other approaches, our model is indeed more often looking at people when predicting their gender.

##### Abstract (translated by Google)
已知大多数机器学习方法捕捉和利用训练数据的偏差。虽然有些偏见有利于学习，但其他偏见却是有害的。具体而言，图像字幕模型倾向于夸大训练数据中存在的偏差（例如，如果在60％的训练语句中存在单词，则可能在测试时间的70％的句子中预测该单词）。由于过度依赖学习的先前和图像上下文，这可能会导致需要无偏标题的域中出现不正确的字幕，或者需要这些字幕。在这项工作中，我们根据个人的外貌或形象背景，研究生成特定于性别的字幕词（例如男人，女人）。我们引入了一种新的均衡器模型，当性别证据被遮挡在场景中时，可确保性别概率相等，并在存在性别证据时进行有把握的预测。由此产生的模型被迫看到一个人，而不是使用上下文线索来进行性别特定的预测。构成我们模型的损失，外观混乱损失和自信损失是一般性的，可以添加到任何描述模型中，以减轻描述数据集中不需要的偏倚的影响。我们提出的模型比以往的工作有更低的误差，当用人们描述图像并且提及他们的性别并且更接近地匹配包括女性在内的句子在内的句子的地面真实比率时。我们还表明，与其他方法不同，我们的模型确实更经常在预测他们的性别时看待人。

##### URL
[https://arxiv.org/abs/1803.09797](https://arxiv.org/abs/1803.09797)

##### PDF
[https://arxiv.org/pdf/1803.09797](https://arxiv.org/pdf/1803.09797)

