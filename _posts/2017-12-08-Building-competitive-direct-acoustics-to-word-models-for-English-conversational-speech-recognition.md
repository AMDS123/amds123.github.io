---
layout: post
title: "Building competitive direct acoustics-to-word models for English conversational speech recognition"
date: 2017-12-08 15:43:21
categories: arXiv_CL
tags: arXiv_CL Regularization Attention Speech_Recognition Language_Model Recognition
author: Kartik Audhkhasi, Brian Kingsbury, Bhuvana Ramabhadran, George Saon, Michael Picheny
mathjax: true
---

* content
{:toc}

##### Abstract
Direct acoustics-to-word (A2W) models in the end-to-end paradigm have received increasing attention compared to conventional sub-word based automatic speech recognition models using phones, characters, or context-dependent hidden Markov model states. This is because A2W models recognize words from speech without any decoder, pronunciation lexicon, or externally-trained language model, making training and decoding with such models simple. Prior work has shown that A2W models require orders of magnitude more training data in order to perform comparably to conventional models. Our work also showed this accuracy gap when using the English Switchboard-Fisher data set. This paper describes a recipe to train an A2W model that closes this gap and is at-par with state-of-the-art sub-word based models. We achieve a word error rate of 8.8%/13.9% on the Hub5-2000 Switchboard/CallHome test sets without any decoder or language model. We find that model initialization, training data order, and regularization have the most impact on the A2W model performance. Next, we present a joint word-character A2W model that learns to first spell the word and then recognize it. This model provides a rich output to the user instead of simple word hypotheses, making it especially useful in the case of words unseen or rarely-seen during training.

##### Abstract (translated by Google)
与使用电话，字符或上下文相关的隐马尔可夫模型状态的基于传统子字的自动语音识别模型相比，端到端范例中的直接声学对字（A2W）模型已经受到越来越多的关注。这是因为A2W模型在没有任何解码器，语音词典或外部训练的语言模型的情况下识别来自语音的单词，使得使用这种模型的训练和解码简单。之前的工作表明，A2W模型需要更多数量的训练数据才能与常规模型相媲美。当使用英文Switchboard-Fisher数据集时，我们的工作也显示了这种精度差距。本文描述了一个训练A2W模型的方法，该模型弥合了这个差距，并且与最先进的基于子字的模型相当。在没有任何解码器或语言模型的Hub5-2000交换机/ CallHome测试集中，我们实现了8.8％/ 13.9％的字错误率。我们发现，模型初始化，训练数据顺序和正则化对A2W模型的性能影响最大。接下来，我们提出一个联合的单词字符A2W模型，学习先拼写单词然后识别它。这个模型为用户提供了一个丰富的输出，而不是简单的单词假设，使得它在训练期间看不见或很少看到的单词尤其有用。

##### URL
[https://arxiv.org/abs/1712.03133](https://arxiv.org/abs/1712.03133)

##### PDF
[https://arxiv.org/pdf/1712.03133](https://arxiv.org/pdf/1712.03133)

