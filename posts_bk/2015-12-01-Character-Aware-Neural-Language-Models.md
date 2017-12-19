---
layout: post
title: "Character-Aware Neural Language Models"
date: 2015-12-01 22:59:24
categories: arXiv_CL
tags: arXiv_CL CNN RNN Language_Model Prediction
author: Yoon Kim, Yacine Jernite, David Sontag, Alexander M. Rush
mathjax: true
---

* content
{:toc}

##### Abstract
We describe a simple neural language model that relies only on character-level inputs. Predictions are still made at the word-level. Our model employs a convolutional neural network (CNN) and a highway network over characters, whose output is given to a long short-term memory (LSTM) recurrent neural network language model (RNN-LM). On the English Penn Treebank the model is on par with the existing state-of-the-art despite having 60% fewer parameters. On languages with rich morphology (Arabic, Czech, French, German, Spanish, Russian), the model outperforms word-level/morpheme-level LSTM baselines, again with fewer parameters. The results suggest that on many languages, character inputs are sufficient for language modeling. Analysis of word representations obtained from the character composition part of the model reveals that the model is able to encode, from characters only, both semantic and orthographic information.

##### Abstract (translated by Google)
我们描述一个简单的神经语言模型，只依赖于字符级输入。预测仍然在单词级别上进行。我们的模型采用了卷积神经网络（CNN）和高速公路网络，将其输出给一个长期的短期记忆（LSTM）递归神经网络语言模型（RNN-LM）。在英国宾夕法尼亚州立大学（Penn Treebank），尽管参数少了60％，但该模型与现有技术水平相当。在形态丰富的语言（阿拉伯语，捷克语，法语，德语，西班牙语，俄语）上，该模型优于单词级/语素级LSTM基线，参数较少。结果表明，在许多语言中，字符输入足以用于语言建模。对从模型的人物组成部分获得的词表示的分析揭示，该模型能够仅从人物编码语义和正字法信息。

##### URL
[https://arxiv.org/abs/1508.06615](https://arxiv.org/abs/1508.06615)

##### PDF
[https://arxiv.org/pdf/1508.06615](https://arxiv.org/pdf/1508.06615)

