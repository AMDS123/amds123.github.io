---
layout: post
title: "Transfer Learning for Related Reinforcement Learning Tasks via Image-to-Image Translation"
date: 2018-12-12 19:43:31
categories: arXiv_AI
tags: arXiv_AI Adversarial Knowledge GAN Reinforcement_Learning Transfer_Learning
author: Shani Gamrian, Yoav Goldberg
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Reinforcement Learning has managed to achieve state-of-the-art results in learning control policies directly from raw pixels. However, despite its remarkable success, it fails to generalize, a fundamental component required in a stable Artificial Intelligence system. Using the Atari game Breakout, we demonstrate the difficulty of a trained agent in adjusting to simple modifications in the raw image, ones that a human could adapt to trivially. In transfer learning, the goal is to use the knowledge gained from the source task to make the training of the target task faster and better. We show that using various forms of fine-tuning, a common method for transfer learning, is not effective for adapting to such small visual changes. In fact, it is often easier to re-train the agent from scratch than to fine-tune a trained agent. We suggest that in some cases transfer learning can be improved by adding a dedicated component whose goal is to learn to visually map between the known domain and the new one. Concretely, we use Unaligned Generative Adversarial Networks (GANs) to create a mapping function to translate images in the target task to corresponding images in the source task. These mapping functions allow us to transform between various variations of the Breakout game, as well as different levels of a Nintendo game, Road Fighter. We show that learning this mapping is substantially more efficient than re-training. A visualization of a trained agent playing Breakout and Road Fighter, with and without the GAN transfer, can be seen in https://youtu.be/4mnkzYyXMn4 and https://youtu.be/khtS-VjpOEA .

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1806.07377](http://arxiv.org/abs/1806.07377)

##### PDF
[http://arxiv.org/pdf/1806.07377](http://arxiv.org/pdf/1806.07377)

