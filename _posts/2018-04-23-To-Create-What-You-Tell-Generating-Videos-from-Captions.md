---
layout: post
title: "To Create What You Tell: Generating Videos from Captions"
date: 2018-04-23 07:07:20
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Caption Embedding Deep_Learning Quantitative
author: Yingwei Pan, Zhaofan Qiu, Ting Yao, Houqiang Li, Tao Mei
mathjax: true
---

* content
{:toc}

##### Abstract
We are creating multimedia contents everyday and everywhere. While automatic content generation has played a fundamental challenge to multimedia community for decades, recent advances of deep learning have made this problem feasible. For example, the Generative Adversarial Networks (GANs) is a rewarding approach to synthesize images. Nevertheless, it is not trivial when capitalizing on GANs to generate videos. The difficulty originates from the intrinsic structure where a video is a sequence of visually coherent and semantically dependent frames. This motivates us to explore semantic and temporal coherence in designing GANs to generate videos. In this paper, we present a novel Temporal GANs conditioning on Captions, namely TGANs-C, in which the input to the generator network is a concatenation of a latent noise vector and caption embedding, and then is transformed into a frame sequence with 3D spatio-temporal convolutions. Unlike the naive discriminator which only judges pairs as fake or real, our discriminator additionally notes whether the video matches the correct caption. In particular, the discriminator network consists of three discriminators: video discriminator classifying realistic videos from generated ones and optimizes video-caption matching, frame discriminator discriminating between real and fake frames and aligning frames with the conditioning caption, and motion discriminator emphasizing the philosophy that the adjacent frames in the generated videos should be smoothly connected as in real ones. We qualitatively demonstrate the capability of our TGANs-C to generate plausible videos conditioning on the given captions on two synthetic datasets (SBMG and TBMG) and one real-world dataset (MSVD). Moreover, quantitative experiments on MSVD are performed to validate our proposal via Generative Adversarial Metric and human study.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1804.08264](https://arxiv.org/abs/1804.08264)

##### PDF
[https://arxiv.org/pdf/1804.08264](https://arxiv.org/pdf/1804.08264)

