---
layout: post
title: "Learning the Enigma with Recurrent Neural Networks"
date: 2017-09-07 19:05:23
categories: arXiv_CV
tags: arXiv_CV Image_Caption Speech_Recognition Caption RNN Recognition
author: Sam Greydanus
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks (RNNs) represent the state of the art in translation, image captioning, and speech recognition. They are also capable of learning algorithmic tasks such as long addition, copying, and sorting from a set of training examples. We demonstrate that RNNs can learn decryption algorithms -- the mappings from plaintext to ciphertext -- for three polyalphabetic ciphers (Vigen\`ere, Autokey, and Enigma). Most notably, we demonstrate that an RNN with a 3000-unit Long Short-Term Memory (LSTM) cell can learn the decryption function of the Enigma machine. We argue that our model learns efficient internal representations of these ciphers 1) by exploring activations of individual memory neurons and 2) by comparing memory usage across the three ciphers. To be clear, our work is not aimed at 'cracking' the Enigma cipher. However, we do show that our model can perform elementary cryptanalysis by running known-plaintext attacks on the Vigen\`ere and Autokey ciphers. Our results indicate that RNNs can learn algorithmic representations of black box polyalphabetic ciphers and that these representations are useful for cryptanalysis.

##### Abstract (translated by Google)
递归神经网络（RNN）代表翻译，图像字幕和语音识别的现有技术。他们还能够从一组训练样例中学习算法任务，例如长时间添加，复制和排序。我们证明了RNN可以学习三种多字母密码（Vigen \ ere，Autokey和Enigma）的解密算法 - 从明文到密文的映射。最值得注意的是，我们证明具有3000单位长短期记忆（LSTM）细胞的RNN可以学习Enigma机器的解密功能。我们认为我们的模型通过探索单个记忆神经元的激活来学习这些密码的有效内部表示1）通过比较三个密码的内存使用情况。需要说明的是，我们的工作并非旨在“破解”Enigma密码。但是，我们确实表明我们的模型可以通过对Vigen \ ere和Autokey密码运行已知明文攻击来执行基本密码分析。我们的结果表明，RNN可以学习黑盒子多字母密码的算法表示，并且这些表示对于密码分析是有用的。

##### URL
[https://arxiv.org/abs/1708.07576](https://arxiv.org/abs/1708.07576)

##### PDF
[https://arxiv.org/pdf/1708.07576](https://arxiv.org/pdf/1708.07576)

