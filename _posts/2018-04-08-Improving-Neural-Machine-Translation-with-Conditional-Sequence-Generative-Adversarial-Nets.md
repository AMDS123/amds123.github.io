---
layout: post
title: "Improving Neural Machine Translation with Conditional Sequence Generative Adversarial Nets"
date: 2018-04-08 08:23:43
categories: arXiv_CL
tags: arXiv_CL Adversarial GAN NMT RNN
author: Zhen Yang, Wei Chen, Feng Wang, Bo Xu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes an approach for applying GANs to NMT. We build a conditional sequence generative adversarial net which comprises of two adversarial sub models, a generator and a discriminator. The generator aims to generate sentences which are hard to be discriminated from human-translated sentences (i.e., the golden target sentences), And the discriminator makes efforts to discriminate the machine-generated sentences from human-translated ones. The two sub models play a mini-max game and achieve the win-win situation when they reach a Nash Equilibrium. Additionally, the static sentence-level BLEU is utilized as the reinforced objective for the generator, which biases the generation towards high BLEU points. During training, both the dynamic discriminator and the static BLEU objective are employed to evaluate the generated sentences and feedback the evaluations to guide the learning of the generator. Experimental results show that the proposed model consistently outperforms the traditional RNNSearch and the newly emerged state-of-the-art Transformer on English-German and Chinese-English translation tasks.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1703.04887](https://arxiv.org/abs/1703.04887)

##### PDF
[https://arxiv.org/pdf/1703.04887](https://arxiv.org/pdf/1703.04887)

