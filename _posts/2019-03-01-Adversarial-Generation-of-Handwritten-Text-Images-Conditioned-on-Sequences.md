---
layout: post
title: "Adversarial Generation of Handwritten Text Images Conditioned on Sequences"
date: 2019-03-01 13:11:44
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Embedding RNN Recognition
author: Eloi Alonso, Bastien Moysset, Ronaldo Messina
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art offline handwriting text recognition systems tend to use neural networks and therefore require a large amount of annotated data to be trained. In order to partially satisfy this requirement, we propose a system based on Generative Adversarial Networks (GAN) to produce synthetic images of handwritten words. We use bidirectional LSTM recurrent layers to get an embedding of the word to be rendered, and we feed it to the generator network. We also modify the standard GAN by adding an auxiliary network for text recognition. The system is then trained with a balanced combination of an adversarial loss and a CTC loss. Together, these extensions to GAN enable to control the textual content of the generated word images. We obtain realistic images on both French and Arabic datasets, and we show that integrating these synthetic images into the existing training data of a text recognition system can slightly enhance its performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.00277](http://arxiv.org/abs/1903.00277)

##### PDF
[http://arxiv.org/pdf/1903.00277](http://arxiv.org/pdf/1903.00277)

