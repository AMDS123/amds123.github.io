---
layout: post
title: "Learning Disentangled Representations for Timber and Pitch in Music Audio"
date: 2018-11-08 05:05:50
categories: arXiv_SD
tags: arXiv_SD Adversarial Knowledge CNN Represenation_Learning
author: Yun-Ning Hung, Yi-An Chen, Yi-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Timbre and pitch are the two main perceptual properties of musical sounds. Depending on the target applications, we sometimes prefer to focus on one of them, while reducing the effect of the other. Researchers have managed to hand-craft such timbre-invariant or pitch-invariant features using domain knowledge and signal processing techniques, but it remains difficult to disentangle them in the resulting feature representations. Drawing upon state-of-the-art techniques in representation learning, we propose in this paper two deep convolutional neural network models for learning disentangled representation of musical timbre and pitch. Both models use encoders/decoders and adversarial training to learn music representations, but the second model additionally uses skip connections to deal with the pitch information. As music is an art of time, the two models are supervised by frame-level instrument and pitch labels using a new dataset collected from MuseScore. We compare the result of the two disentangling models with a new evaluation protocol called "timbre crossover", which leads to interesting applications in audio-domain music editing. Via various objective evaluations, we show that the second model can better change the instrumentation of a multi-instrument music piece without much affecting the pitch structure. By disentangling timbre and pitch, we envision that the model can contribute to generating more realistic music audio as well.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.03271](http://arxiv.org/abs/1811.03271)

##### PDF
[http://arxiv.org/pdf/1811.03271](http://arxiv.org/pdf/1811.03271)

