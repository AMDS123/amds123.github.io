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
图像字幕是一项具有挑战性的任务，机器通过句子或短语自动描述图像。它通常需要大量的配对图像句子注释进行训练。然而，预先训练的字幕模型很难应用于其中存在一些新颖的对象类别的新领域，即，在模型训练期间对象及其描述词是不可见的。为了正确地标注新小说对象，它需要专业的人类工作者用小说用句子来注释图像。这是劳动力昂贵的，因此限制了其在实际应用中的使用。在本文中，我们介绍零点新颖物体字幕任务，其中机器生成描述而不用额外的句子来描述新物体。为了解决具有挑战性的问题，我们提出了一个Decoupled Novel Object Captioner（DNOC）框架，它可以将语言序列模型与对象描述完全分离。 DNOC有两个组件。 1）带占位符（SM-P）的序列模型生成包含占位符的句子。占位符代表一个看不见的新颖对象。因此，序列模型可以从新的对象描述中分离出来。 2）建立在免费检测模型上的键值对象存储器包含每个对象的可视信息和相应的单词。 SM-P将生成一个查询来从对象内存中检索单词。然后占位符将被填充正确的单词，从而产生具有新颖对象描述的标题。在所推出的MSCOCO数据集上的实验结果证明了DNOC在零点新颖物体字幕任务中描述新颖概念的能力。

##### URL
[https://arxiv.org/abs/1804.03803](https://arxiv.org/abs/1804.03803)

##### PDF
[https://arxiv.org/pdf/1804.03803](https://arxiv.org/pdf/1804.03803)

