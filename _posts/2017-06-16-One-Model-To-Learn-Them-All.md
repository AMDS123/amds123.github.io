---
layout: post
title: "One Model To Learn Them All"
date: 2017-06-16 03:10:03
categories: arXiv_CV
tags: arXiv_CV Image_Caption Speech_Recognition Caption CNN Image_Classification Classification Deep_Learning Recognition
author: Lukasz Kaiser, Aidan N. Gomez, Noam Shazeer, Ashish Vaswani, Niki Parmar, Llion Jones, Jakob Uszkoreit
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning yields great results across many fields, from speech recognition, image classification, to translation. But for each problem, getting a deep model to work well involves research into the architecture and a long period of tuning. We present a single model that yields good results on a number of problems spanning multiple domains. In particular, this single model is trained concurrently on ImageNet, multiple translation tasks, image captioning (COCO dataset), a speech recognition corpus, and an English parsing task. Our model architecture incorporates building blocks from multiple domains. It contains convolutional layers, an attention mechanism, and sparsely-gated layers. Each of these computational blocks is crucial for a subset of the tasks we train on. Interestingly, even if a block is not crucial for a task, we observe that adding it never hurts performance and in most cases improves it on all tasks. We also show that tasks with less data benefit largely from joint training with other tasks, while performance on large tasks degrades only slightly if at all.

##### Abstract (translated by Google)
深度学习在语音识别，图像分类，翻译等许多领域都有很好的效果。但是，对于每一个问题，深入研究模型都需要对体系结构和长时间的调整进行研究。我们提出了一个模型，可以在多个领域的许多问题上得到很好的结果。特别是在ImageNet上同时训练这个单一的模型，多个翻译任务，图像字幕（COCO数据集），语音识别语料库和英语解析任务。我们的模型体系结构包含来自多个域的构建块。它包含卷积层，关注机制和稀疏的门控层。这些计算块中的每一个对于我们训练的任务的一个子集都是至关重要的。有趣的是，即使一个块对于一个任务来说并不重要，但是我们注意到，添加它从不会伤害到性能，并且在大多数情况下在所有任务上都会改善它。我们还表明，数据较少的任务在很大程度上受益于与其他任务的联合训练，而大型任务的性能只会略微降低。

##### URL
[https://arxiv.org/abs/1706.05137](https://arxiv.org/abs/1706.05137)

##### PDF
[https://arxiv.org/pdf/1706.05137](https://arxiv.org/pdf/1706.05137)

