---
layout: post
title: "Learning to Organize Knowledge and Answer Questions with N-Gram Machines"
date: 2018-07-01 07:09:45
categories: arXiv_AI
tags: arXiv_AI Knowledge QA GAN
author: Fan Yang, Jiazhong Nie, William W. Cohen, Ni Lao
mathjax: true
---

* content
{:toc}

##### Abstract
Though deep neural networks have great success in natural language processing, they are limited at more knowledge intensive AI tasks, such as open-domain Question Answering (QA). Existing end-to-end deep QA models need to process the entire text after observing the question, and therefore their complexity in responding a question is linear in the text size. This is prohibitive for practical tasks such as QA from Wikipedia, a novel, or the Web. We propose to solve this scalability issue by using symbolic meaning representations, which can be indexed and retrieved efficiently with complexity that is independent of the text size. We apply our approach, called the N-Gram Machine (NGM), to three representative tasks. First as proof-of-concept, we demonstrate that NGM successfully solves the bAbI tasks of synthetic text. Second, we show that NGM scales to large corpus by experimenting on "life-long bAbI", a special version of bAbI that contains millions of sentences. Lastly on the WikiMovies dataset, we use NGM to induce latent structure (i.e. schema) and answer questions from natural language Wikipedia text, with only QA pairs as weak supervision.

##### Abstract (translated by Google)
尽管深度神经网络在自然语言处理方面取得了巨大成功，但它们受限于更多知识密集型AI任务，例如开放域问答（QA）。现有的端到端深度QA模型需要在观察问题后处理整个文本，因此它们在回答问题时的复杂性在文本大小上是线性的。这对于诸如维基百科的QA，小说或网络等实际任务来说是令人望而却步的。我们建议通过使用符号意义表示来解决这种可伸缩性问题，这些表示可以通过独立于文本大小的复杂性进行有效索引和检索。我们将称为N-Gram Machine（NGM）的方法应用于三个代表性任务。首先作为概念验证，我们证明NGM成功地解决了合成文本的bAbI任务。其次，我们通过对“终身bAbI”进行实验来证明NGM可以扩展到大型语料库，这是一个包含数百万个句子的特殊版本的bAbI。最后，在WikiMovies数据集上，我们使用NGM来诱导潜在结构（即模式）并回答来自自然语言维基百科文本的问题，只有QA对作为弱监督。

##### URL
[http://arxiv.org/abs/1711.06744](http://arxiv.org/abs/1711.06744)

##### PDF
[http://arxiv.org/pdf/1711.06744](http://arxiv.org/pdf/1711.06744)

