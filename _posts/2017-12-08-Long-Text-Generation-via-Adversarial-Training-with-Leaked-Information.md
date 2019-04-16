---
layout: post
title: "Long Text Generation via Adversarial Training with Leaked Information"
date: 2017-12-08 18:53:52
categories: arXiv_CV
tags: arXiv_CV Image_Caption Adversarial GAN Text_Generation Reinforcement_Learning Caption
author: Jiaxian Guo, Sidi Lu, Han Cai, Weinan Zhang, Yong Yu, Jun Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Automatically generating coherent and semantically meaningful text has many applications in machine translation, dialogue systems, image captioning, etc. Recently, by combining with policy gradient, Generative Adversarial Nets (GAN) that use a discriminative model to guide the training of the generative model as a reinforcement learning policy has shown promising results in text generation. However, the scalar guiding signal is only available after the entire text has been generated and lacks intermediate information about text structure during the generative process. As such, it limits its success when the length of the generated text samples is long (more than 20 words). In this paper, we propose a new framework, called LeakGAN, to address the problem for long text generation. We allow the discriminative net to leak its own high-level extracted features to the generative net to further help the guidance. The generator incorporates such informative signals into all generation steps through an additional Manager module, which takes the extracted features of current generated words and outputs a latent vector to guide the Worker module for next-word generation. Our extensive experiments on synthetic data and various real-world tasks with Turing test demonstrate that LeakGAN is highly effective in long text generation and also improves the performance in short text generation scenarios. More importantly, without any supervision, LeakGAN would be able to implicitly learn sentence structures only through the interaction between Manager and Worker.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1709.08624](https://arxiv.org/abs/1709.08624)

##### PDF
[https://arxiv.org/pdf/1709.08624](https://arxiv.org/pdf/1709.08624)

