---
layout: post
title: "Visually grounded cross-lingual keyword spotting in speech"
date: 2018-06-13 13:37:34
categories: arXiv_CL
tags: arXiv_CL
author: Herman Kamper, Michael Roth
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work considered how images paired with speech can be used as supervision for building speech systems when transcriptions are not available. We ask whether visual grounding can be used for cross-lingual keyword spotting: given a text keyword in one language, the task is to retrieve spoken utterances containing that keyword in another language. This could enable searching through speech in a low-resource language using text queries in a high-resource language. As a proof-of-concept, we use English speech with German queries: we use a German visual tagger to add keyword labels to each training image, and then train a neural network to map English speech to German keywords. Without seeing parallel speech-transcriptions or translations, the model achieves a precision at ten of 58%. We show that most erroneous retrievals contain equivalent or semantically relevant keywords; excluding these would improve P@10 to 91%.

##### Abstract (translated by Google)
最近的工作考虑了如何在语音转录不可用的情况下将图像与语音配对如何用作构建语音系统的监督。我们询问是否可以使用视觉基础进行跨语言关键词检测：给定一种语言的文本关键字，其任务是检索包含该关键字的另一种语言的口头语言。这可以使用高资源语言的文本查询以低资源语言搜索语音。作为一个概念验证，我们在德语查询中使用英语语音：我们使用德语视觉标注器为每个训练图像添加关键字标签，然后训练一个神经网络将英语语音映射到德语关键字。没有看到平行的语音转录或翻译，模型的精确度达到了58％。我们表明，大多数错误的检索包含等效或语义相关的关键字;不包括这些将使P @ 10提高到91％。

##### URL
[https://arxiv.org/abs/1806.05030](https://arxiv.org/abs/1806.05030)

##### PDF
[https://arxiv.org/pdf/1806.05030](https://arxiv.org/pdf/1806.05030)

