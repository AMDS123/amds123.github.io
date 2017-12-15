---
layout: post
title: "Expect the unexpected: Harnessing Sentence Completion for Sarcasm Detection"
date: 2017-07-19 15:24:20
categories: arXiv_CL
tags: arXiv_CL RNN Detection
author: Aditya Joshi, Samarth Agrawal, Pushpak Bhattacharyya, Mark Carman
mathjax: true
---

* content
{:toc}

##### Abstract
The trigram `I love being' is expected to be followed by positive words such as `happy'. In a sarcastic sentence, however, the word `ignored' may be observed. The expected and the observed words are, thus, incongruous. We model sarcasm detection as the task of detecting incongruity between an observed and an expected word. In order to obtain the expected word, we use Context2Vec, a sentence completion library based on Bidirectional LSTM. However, since the exact word where such an incongruity occurs may not be known in advance, we present two approaches: an All-words approach (which consults sentence completion for every content word) and an Incongruous words-only approach (which consults sentence completion for the 50% most incongruous content words). The approaches outperform reported values for tweets but not for discussion forum posts. This is likely to be because of redundant consultation of sentence completion for discussion forum posts. Therefore, we consider an oracle case where the exact incongruous word is manually labeled in a corpus reported in past work. In this case, the performance is higher than the all-words approach. This sets up the promise for using sentence completion for sarcasm detection.

##### Abstract (translated by Google)
“我爱的三卦”预计会跟随“快乐”这样的积极词汇。然而，在一个讽刺的句子中，可以观察到“忽略”这个词。因此，预期的和观察到的词语是不协调的。我们将讽刺检测建模为检测观察词和预期词之间不协调的任务。为了获得期望的单词，我们使用基于双向LSTM的句子完成库Context2Vec。然而，由于这种不协调的确切词语可能并不是事先知道的，因此我们提出两种方法：一种是全部词语的方法（对每一个内容词都进行咨询句子完成）和一种不协调的单词方法对于50％最不协调的内容词）。这些方法比tweets的报告值要好，但不能用于讨论论坛的帖子。这可能是因为讨论论坛帖子的句子完成冗余咨询。因此，我们考虑一个oracle案例，其中在过去的工作中报告的语料库中人工标记了确切的不一致的单词。在这种情况下，表现比全面的方法更高。这就建立了对讽刺检测使用句子完成的承诺。

##### URL
[https://arxiv.org/abs/1707.06151](https://arxiv.org/abs/1707.06151)

##### PDF
[https://arxiv.org/pdf/1707.06151](https://arxiv.org/pdf/1707.06151)

