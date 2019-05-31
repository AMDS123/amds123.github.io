---
layout: post
title: "Adversarial Sub-sequence for Text Generation"
date: 2019-05-30 02:51:15
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN Text_Generation
author: Xingyuan Chen, Yanzhe Li, Peng Jin, Jiuhua Zhang, Xinyu Dai, Jiajun Chen, Gang Song
mathjax: true
---

* content
{:toc}

##### Abstract
Generative adversarial nets (GAN) has been successfully introduced for generating text to alleviate the exposure bias. However, discriminators in these models only evaluate the entire sequence, which causes feedback sparsity and mode collapse. To tackle these problems, we propose a novel mechanism. It first segments the entire sequence into several sub-sequences. Then these sub-sequences, together with the entire sequence, are evaluated individually by the discriminator. At last these feedback signals are all used to guide the learning of GAN. This mechanism learns the generation of both the entire sequence and the sub-sequences simultaneously. Learning to generate sub-sequences is easy and is helpful in generating an entire sequence. It is easy to improve the existing GAN-based models with this mechanism. We rebuild three previous well-designed models with our mechanism, and the experimental results on benchmark data show these models are improved significantly, the best one outperforms the state-of-the-art model.\footnote[1]{All code and data are available at https://github.com/liyzcj/seggan.git

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12835](http://arxiv.org/abs/1905.12835)

##### PDF
[http://arxiv.org/pdf/1905.12835](http://arxiv.org/pdf/1905.12835)

