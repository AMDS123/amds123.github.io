---
layout: post
title: "Improving the Performance of Online Neural Transducer Models"
date: 2017-12-05 18:34:56
categories: arXiv_CL
tags: arXiv_CL
author: Tara N. Sainath, Chung-Cheng Chiu, Rohit Prabhavalkar, Anjuli Kannan, Yonghui Wu, Patrick Nguyen, Zhifeng Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Having a sequence-to-sequence model which can operate in an online fashion is important for streaming applications such as Voice Search. Neural transducer is a streaming sequence-to-sequence model, but has shown a significant degradation in performance compared to non-streaming models such as Listen, Attend and Spell (LAS). In this paper, we present various improvements to NT. Specifically, we look at increasing the window over which NT computes attention, mainly by looking backwards in time so the model still remains online. In addition, we explore initializing a NT model from a LAS-trained model so that it is guided with a better alignment. Finally, we explore including stronger language models such as using wordpiece models, and applying an external LM during the beam search. On a Voice Search task, we find with these improvements we can get NT to match the performance of LAS.

##### Abstract (translated by Google)
具有可以以在线方式操作的序列到序列模型对于诸如语音搜索的流式应用是重要的。神经传感器是一种流式序列到序列模型，但与非流式模型（如Listen，Attend and Spell（LAS））相比，表现出明显的性能下降。在本文中，我们提出了对NT的各种改进。具体而言，我们考虑增加NT计算关注的窗口，主要是通过及时回顾模型，使模型保持在线状态。另外，我们从LAS训练的模型中探索初始化一个NT模型，以便更好地对齐。最后，我们探索包括更强大的语言模型，如使用wordpiece模型，并在波束搜索期间应用外部LM。在语音搜索任务中，我们发现通过这些改进，我们可以得到NT来匹配LAS的性能。

##### URL
[http://arxiv.org/abs/1712.01807](http://arxiv.org/abs/1712.01807)

##### PDF
[http://arxiv.org/pdf/1712.01807](http://arxiv.org/pdf/1712.01807)

