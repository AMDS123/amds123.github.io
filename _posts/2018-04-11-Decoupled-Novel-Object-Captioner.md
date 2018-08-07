---
layout: post
title: "Decoupled Novel Object Captioner"
date: 2018-04-11 04:21:22
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption Detection
author: Yu Wu, Linchao Zhu, Lu Jiang, Yi Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Image captioning is a challenging task where the machine automatically describes an image by sentences or phrases. It often requires a large number of paired image-sentence annotations for training. However, a pre-trained captioning model can hardly be applied to a new domain in which some novel object categories exist, i.e., the objects and their description words are unseen during model training. To correctly caption the novel object, it requires professional human workers to annotate the images by sentences with the novel words. It is labor expensive and thus limits its usage in real-world applications. In this paper, we introduce the zero-shot novel object captioning task where the machine generates descriptions without extra sentences about the novel object. To tackle the challenging problem, we propose a Decoupled Novel Object Captioner (DNOC) framework that can fully decouple the language sequence model from the object descriptions. DNOC has two components. 1) A Sequence Model with the Placeholder (SM-P) generates a sentence containing placeholders. The placeholder represents an unseen novel object. Thus, the sequence model can be decoupled from the novel object descriptions. 2) A key-value object memory built upon the freely available detection model, contains the visual information and the corresponding word for each object. The SM-P will generate a query to retrieve the words from the object memory. The placeholder will then be filled with the correct word, resulting in a caption with novel object descriptions. The experimental results on the held-out MSCOCO dataset demonstrate the ability of DNOC in describing novel concepts in the zero-shot novel object captioning task.

##### Abstract (translated by Google)
图像字幕是一项具有挑战性的任务，其中机器通过句子或短语自动描述图像。它通常需要大量配对的图像 - 句子注释用于训练。然而，预训练的字幕模型很难应用于存在一些新的对象类别的新域，即，在模型训练期间看不到对象及其描述词。为了正确地标注新颖的物体，需要专业的人类工作者用新颖的词语用句子来注释图像。它劳动力昂贵，因此限制了它在实际应用中的使用。在本文中，我们介绍了零镜头新颖的对象字幕任务，其中机器生成描述而没有关于新对象的额外句子。为了解决这个具有挑战性的问题，我们提出了一种解耦新型对象捕获器（DNOC）框架，它可以完全将语言序列模型与对象描述分离。 DNOC有两个组成部分。 1）具有占位符的序列模型（SM-P）生成包含占位符的句子。占位符代表了一个看不见的新颖对象。因此，序列模型可以与新颖的对象描述分离。 2）基于可自由使用的检测模型构建的键值对象存储器，包含每个对象的视觉信息和相应的单词。 SM-P将生成查询以从对象存储器中检索单词。然后占位符将填充正确的单词，从而产生具有新颖对象描述的标题。对于保留的MSCOCO数据集的实验结果证明了DNOC在零镜头新颖的对象字幕描述任务中描述新概念的能力。

##### URL
[https://arxiv.org/abs/1804.03803](https://arxiv.org/abs/1804.03803)

##### PDF
[https://arxiv.org/pdf/1804.03803](https://arxiv.org/pdf/1804.03803)

