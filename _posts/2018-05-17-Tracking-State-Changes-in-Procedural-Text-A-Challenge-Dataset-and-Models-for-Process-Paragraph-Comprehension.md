---
layout: post
title: "Tracking State Changes in Procedural Text: A Challenge Dataset and Models for Process Paragraph Comprehension"
date: 2018-05-17 21:42:04
categories: arXiv_CL
tags: arXiv_CL OCR Tracking RNN Prediction
author: Bhavana Dalvi Mishra, Lifu Huang, Niket Tandon, Wen-tau Yih, Peter Clark
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new dataset and models for comprehending paragraphs about processes (e.g., photosynthesis), an important genre of text describing a dynamic world. The new dataset, ProPara, is the first to contain natural (rather than machine-generated) text about a changing world along with a full annotation of entity states (location and existence) during those changes (81k datapoints). The end-task, tracking the location and existence of entities through the text, is challenging because the causal effects of actions are often implicit and need to be inferred. We find that previous models that have worked well on synthetic data achieve only mediocre performance on ProPara, and introduce two new neural models that exploit alternative mechanisms for state prediction, in particular using LSTM input encoding and span prediction. The new models improve accuracy by up to 19%. The dataset and models are available to the community at <a href="http://data.allenai.org/propara.">this http URL</a>

##### Abstract (translated by Google)
我们提出了一个新的数据集和模型，用于理解关于过程的段落（例如光合作用），这是描述动态世界的重要文本类型。新数据集ProPara是第一个包含关于变化世界的自然（而不是机器生成的）文本以及在这些变化（81k数据点）期间对实体状态（位置和存在）的完整注释的文本。通过文本跟踪实体的位置和存在的最终任务是具有挑战性的，因为行为的因果效应往往是隐含的，需要被推断出来。我们发现之前在合成数据上运行良好的模型在ProPara上只能获得平庸的性能，并且引入了两种新的神经模型，这些模型利用用于状态预测的替代机制，特别是使用LSTM输入编码和跨度预测。新型号的精度提高了19％。数据集和模型可在<a href="http://data.allenai.org/propara.">此http URL </a>处获得

##### URL
[http://arxiv.org/abs/1805.06975](http://arxiv.org/abs/1805.06975)

##### PDF
[http://arxiv.org/pdf/1805.06975](http://arxiv.org/pdf/1805.06975)

