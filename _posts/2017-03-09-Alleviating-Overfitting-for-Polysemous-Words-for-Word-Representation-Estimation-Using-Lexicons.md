---
layout: post
title: "Alleviating Overfitting for Polysemous Words for Word Representation Estimation Using Lexicons"
date: 2017-03-09 12:36:26
categories: arXiv_CL
tags: arXiv_CL
author: Yuanzhi Ke, Masafumi Hagiwara
mathjax: true
---

* content
{:toc}

##### Abstract
Though there are some works on improving distributed word representations using lexicons, the improper overfitting of the words that have multiple meanings is a remaining issue deteriorating the learning when lexicons are used, which needs to be solved. An alternative method is to allocate a vector per sense instead of a vector per word. However, the word representations estimated in the former way are not as easy to use as the latter one. Our previous work uses a probabilistic method to alleviate the overfitting, but it is not robust with a small corpus. In this paper, we propose a new neural network to estimate distributed word representations using a lexicon and a corpus. We add a lexicon layer in the continuous bag-of-words model and a threshold node after the output of the lexicon layer. The threshold rejects the unreliable outputs of the lexicon layer that are less likely to be the same with their inputs. In this way, it alleviates the overfitting of the polysemous words. The proposed neural network can be trained using negative sampling, which maximizing the log probabilities of target words given the context words, by distinguishing the target words from random noises. We compare the proposed neural network with the continuous bag-of-words model, the other works improving it, and the previous works estimating distributed word representations using both a lexicon and a corpus. The experimental results show that the proposed neural network is more efficient and balanced for both semantic tasks and syntactic tasks than the previous works, and robust to the size of the corpus.

##### Abstract (translated by Google)
虽然在词汇表达上改善分布式词汇表达方面存在一些问题，但是词汇表达方式的不恰当的过度拟合是词汇使用过程中残留学习的一个亟待解决的问题，需要加以解决。另一种方法是为每个感觉分配一个矢量，而不是每个单词的矢量。但是，以前一种方式估计的词语表达方式并不像后一种那样容易使用。我们以前的工作使用概率方法来缓解过度拟合，但是对于一个小的语料库来说，它是不稳健的。在本文中，我们提出了一个新的神经网络来估计分布式词表示使用词典和语料库。在词典层的输出之后，我们在连续词袋模型和阈值节点中添加词典层。阈值拒绝不太可能与输入相同的词典层的不可靠输出。这样就减轻了多义词的过度拟合。所提出的神经网络可以使用负样本进行训练，通过区分目标词和随机噪声来最大化目标词的对数概率。我们将提出的神经网络与连续词袋模型进行比较，另一个工作对其进行了改进，以前的工作使用词典和语料库来估计分布式词汇表示。实验结果表明，所提出的神经网络在语义任务和句法任务方面均比以前的作品更加高效和平衡，并且对语料的大小起到了鲁棒的作用。

##### URL
[https://arxiv.org/abs/1612.00584](https://arxiv.org/abs/1612.00584)

##### PDF
[https://arxiv.org/pdf/1612.00584](https://arxiv.org/pdf/1612.00584)

