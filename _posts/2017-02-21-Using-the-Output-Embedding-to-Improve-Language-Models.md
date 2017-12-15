---
layout: post
title: "Using the Output Embedding to Improve Language Models"
date: 2017-02-21 17:50:20
categories: arXiv_CL
tags: arXiv_CL Embedding Language_Model
author: Ofir Press, Lior Wolf
mathjax: true
---

* content
{:toc}

##### Abstract
We study the topmost weight matrix of neural network language models. We show that this matrix constitutes a valid word embedding. When training language models, we recommend tying the input embedding and this output embedding. We analyze the resulting update rules and show that the tied embedding evolves in a more similar way to the output embedding than to the input embedding in the untied model. We also offer a new method of regularizing the output embedding. Our methods lead to a significant reduction in perplexity, as we are able to show on a variety of neural network language models. Finally, we show that weight tying can reduce the size of neural translation models to less than half of their original size without harming their performance.

##### Abstract (translated by Google)
我们研究神经网络语言模型的最高权重矩阵。我们证明这个矩阵构成了一个有效的字嵌入。在训练语言模型时，我们推荐搭配输入嵌入和输出嵌入。我们分析所得到的更新规则，并显示绑定嵌入与输出嵌入演变的方式相比，在嵌入模型中的输入嵌入更加类似。我们还提供了一种规范输出嵌入的新方法。我们的方法可以显着减少困惑，因为我们能够在各种神经网络语言模型上展示。最后，我们表明，体重搭配可以将神经翻译模型的大小减小到原始大小的一半，而不损害其性能。

##### URL
[https://arxiv.org/abs/1608.05859](https://arxiv.org/abs/1608.05859)

##### PDF
[https://arxiv.org/pdf/1608.05859](https://arxiv.org/pdf/1608.05859)

