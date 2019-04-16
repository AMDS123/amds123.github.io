---
layout: post
title: "End-to-End Speech-Driven Facial Animation with Temporal GANs"
date: 2018-07-19 12:40:47
categories: arXiv_CV
tags: arXiv_CV Knowledge GAN
author: Konstantinos Vougioukas, Stavros Petridis, Maja Pantic
mathjax: true
---

* content
{:toc}

##### Abstract
Speech-driven facial animation is the process which uses speech signals to automatically synthesize a talking character. The majority of work in this domain creates a mapping from audio features to visual features. This often requires post-processing using computer graphics techniques to produce realistic albeit subject dependent results. We present a system for generating videos of a talking head, using a still image of a person and an audio clip containing speech, that doesn't rely on any handcrafted intermediate features. To the best of our knowledge, this is the first method capable of generating subject independent realistic videos directly from raw audio. Our method can generate videos which have (a) lip movements that are in sync with the audio and (b) natural facial expressions such as blinks and eyebrow movements. We achieve this by using a temporal GAN with 2 discriminators, which are capable of capturing different aspects of the video. The effect of each component in our system is quantified through an ablation study. The generated videos are evaluated based on their sharpness, reconstruction quality, and lip-reading accuracy. Finally, a user study is conducted, confirming that temporal GANs lead to more natural sequences than a static GAN-based approach.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1805.09313](https://arxiv.org/abs/1805.09313)

##### PDF
[https://arxiv.org/pdf/1805.09313](https://arxiv.org/pdf/1805.09313)

