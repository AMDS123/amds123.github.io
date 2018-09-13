---
layout: post
title: "Chinese Poetry Generation with a Working Memory Model"
date: 2018-09-12 08:31:20
categories: arXiv_AI
tags: arXiv_AI Salient
author: Xiaoyuan Yi, Maosong Sun, Ruoyu Li, Zonghan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
As an exquisite and concise literary form, poetry is a gem of human culture. Automatic poetry generation is an essential step towards computer creativity. In recent years, several neural models have been designed for this task. However, among lines of a whole poem, the coherence in meaning and topics still remains a big challenge. In this paper, inspired by the theoretical concept in cognitive psychology, we propose a novel Working Memory model for poetry generation. Different from previous methods, our model explicitly maintains topics and informative limited history in a neural memory. During the generation process, our model reads the most relevant parts from memory slots to generate the current line. After each line is generated, it writes the most salient parts of the previous line into memory slots. By dynamic manipulation of the memory, our model keeps a coherent information flow and learns to express each topic flexibly and naturally. We experiment on three different genres of Chinese poetry: quatrain, iambic and chinoiserie lyric. Both automatic and human evaluation results show that our model outperforms current state-of-the-art methods.

##### Abstract (translated by Google)
诗歌作为一种精致而简洁的文学形式，是人类文化的瑰宝。自动诗歌生成是迈向计算机创造力的重要一步。近年来，已经为此任务设计了几种神经模型。然而，在整首诗中，意义和主题的连贯性仍然是一个巨大的挑战。本文在认知心理学理论概念的启发下，提出了一种新的工作记忆模型，用于诗歌创作。与以前的方法不同，我们的模型在神经记​​忆中明确地维护主题和信息有限的历史。在生成过程中，我们的模型从内存槽中读取最相关的部分以生成当前行。生成每一行后，它会将前一行的最显着部分写入内存插槽。通过动态操作内存，我们的模型保持连贯的信息流，并学会灵活自然地表达每个主题。我们尝试了三种不同类型的中国诗歌：quatrain，iambic和chinoiserie lyric。自动和人工评估结果都表明我们的模型优于当前最先进的方法。

##### URL
[http://arxiv.org/abs/1809.04306](http://arxiv.org/abs/1809.04306)

##### PDF
[http://arxiv.org/pdf/1809.04306](http://arxiv.org/pdf/1809.04306)

