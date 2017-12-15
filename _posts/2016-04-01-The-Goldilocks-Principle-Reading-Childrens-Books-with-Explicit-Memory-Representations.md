---
layout: post
title: "The Goldilocks Principle: Reading Children's Books with Explicit Memory Representations"
date: 2016-04-01 05:31:33
categories: arXiv_CL
tags: arXiv_CL QA Attention Language_Model
author: Felix Hill, Antoine Bordes, Sumit Chopra, Jason Weston
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a new test of how well language models capture meaning in children's books. Unlike standard language modelling benchmarks, it distinguishes the task of predicting syntactic function words from that of predicting lower-frequency words, which carry greater semantic content. We compare a range of state-of-the-art models, each with a different way of encoding what has been previously read. We show that models which store explicit representations of long-term contexts outperform state-of-the-art neural language models at predicting semantic content words, although this advantage is not observed for syntactic function words. Interestingly, we find that the amount of text encoded in a single memory representation is highly influential to the performance: there is a sweet-spot, not too big and not too small, between single words and full sentences that allows the most meaningful information in a text to be effectively retained and recalled. Further, the attention over such window-based memories can be trained effectively through self-supervision. We then assess the generality of this principle by applying it to the CNN QA benchmark, which involves identifying named entities in paraphrased summaries of news articles, and achieve state-of-the-art performance.

##### Abstract (translated by Google)
我们引入了一个新的测试，即语言模型如何在儿童读物中捕捉到意义。与标准的语言建模基准不同，它将预测句法功能词的任务与预测低频词的任务区分开来，所述低频词具有更大的语义内容。我们比较了一系列最先进的模型，每种模型都有不同的编码方式。我们表明，存储长期上下文的显式表示的模型在预测语义内容词时优于现有技术的神经语言模型，尽管这种优势在句法功能词中没有观察到。有趣的是，我们发现在单个内存表示中编码的文本数量对性能影响很大：在单个单词和完整句子之间存在一个甜点，不是太大，也不是太小，允许最有意义的信息一个文本将被有效保留和回忆。此外，通过自我监督可以有效地培养对这种基于窗口的记忆的关注。然后，我们将这个原则的通用性应用到CNN QA基准中，该基准涉及在新闻文章的转述摘要中识别命名实体，并达到最新的性能。

##### URL
[https://arxiv.org/abs/1511.02301](https://arxiv.org/abs/1511.02301)

##### PDF
[https://arxiv.org/pdf/1511.02301](https://arxiv.org/pdf/1511.02301)

