---
layout: post
title: "Building a Word Segmenter for Sanskrit Overnight"
date: 2018-02-17 04:05:36
categories: arXiv_CL
tags: arXiv_CL Knowledge Segmentation
author: Vikas Reddy, Amrith Krishna, Vishnu Dutt Sharma, Prateek Gupta, Vineeth M R, Pawan Goyal
mathjax: true
---

* content
{:toc}

##### Abstract
There is an abundance of digitised texts available in Sanskrit. However, the word segmentation task in such texts are challenging due to the issue of 'Sandhi'. In Sandhi, words in a sentence often fuse together to form a single chunk of text, where the word delimiter vanishes and sounds at the word boundaries undergo transformations, which is also reflected in the written text. Here, we propose an approach that uses a deep sequence to sequence (seq2seq) model that takes only the sandhied string as the input and predicts the unsandhied string. The state of the art models are linguistically involved and have external dependencies for the lexical and morphological analysis of the input. Our model can be trained "overnight" and be used for production. In spite of the knowledge lean approach, our system preforms better than the current state of the art by gaining a percentage increase of 16.79 % than the current state of the art.

##### Abstract (translated by Google)
梵语中有丰富的数字化文本。然而，由于'Sandhi'的问题，这些文本中的分词任务是具有挑战性的。在Sandhi中，一个句子中的单词经常融合在一起形成一个单独的文本块，单词分隔符消失，单词边界处的声音经历转换，这也反映在书面文本中。在这里，我们提出了一种使用深度序列来排序（seq2seq）模型的方法，该模型仅将sandhied字符串作为输入并预测未被取消的字符串。现有技术模型在语言上涉及并且对输入的词汇和形态分析具有外部依赖性。我们的模型可以进行“过夜”培训并用于生产。尽管采用了知识精益的方法，但我们的系统比现有技术水平的表现要好于当前技术水平，比目前的技术水平提高了16.79％。

##### URL
[http://arxiv.org/abs/1802.06185](http://arxiv.org/abs/1802.06185)

##### PDF
[http://arxiv.org/pdf/1802.06185](http://arxiv.org/pdf/1802.06185)

