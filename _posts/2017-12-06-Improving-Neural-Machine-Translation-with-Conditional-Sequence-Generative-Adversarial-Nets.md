---
layout: post
title: 'Improving Neural Machine Translation with Conditional Sequence Generative Adversarial Nets'
date: 2017-12-06 03:09:44
categories: arXiv_CL
tags: arXiv_CL Adversarial GAN NMT RNN
author: Zhen Yang, Wei Chen, Feng Wang, Bo Xu
---

* content
{:toc}

##### Abstract
This paper proposes an approach for applying GANs to NMT. We build a conditional sequence generative adversarial net which comprises of two adversarial sub models, a generator and a discriminator. The generator aims to generate sentences which are hard to be discriminated from human-translated sentences ( i.e., the golden target sentences); And the discriminator makes efforts to discriminate the machine-generated sentences from human-translated ones. The two sub models play a mini-max game and achieve the win-win situation when they reach a Nash Equilibrium. Additionally, the static sentence-level BLEU is utilized as the reinforced objective for the generator, which biases the generation towards high BLEU points. During training, both the dynamic discriminator and the static BLEU objective are employed to evaluate the generated sentences and feedback the evaluations to guide the learning of the generator. Experimental results show that the proposed model consistently outperforms the traditional RNNSearch and the newly emerged state-of-the-art Transformer on English-German and Chinese-English translation tasks.

##### Abstract (translated by Google)
本文提出了一种将GAN应用于NMT的方法。我们构建了一个条件序列生成对抗网络，它包含两个敌对子模型，一个生成器和一个鉴别器。该生成器旨在生成难以与人类翻译的句子（即，金色目标语句）区分的句子;鉴别者努力区分机器生成的句子和翻译的句子。这两个子模式发挥了迷你最大化的博弈，达到纳什均衡时实现了双赢的局面。另外，静态句级BLEU被用作发电机的增强目标，这将偏向于高BLEU点的发电。在训练过程中，采用动态鉴别器和静态BLEU目标对生成的句子进行评估，反馈评估指导生成器的学习。实验结果表明，该模型一贯优于传统的RNNSearch和新出现的英汉德语和汉英翻译任务的先进Transformer。

##### URL
[https://arxiv.org/abs/1703.04887](https://arxiv.org/abs/1703.04887)

