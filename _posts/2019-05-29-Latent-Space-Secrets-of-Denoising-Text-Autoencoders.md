---
layout: post
title: "Latent Space Secrets of Denoising Text-Autoencoders"
date: 2019-05-29 23:22:56
categories: arXiv_CL
tags: arXiv_CL Sentiment Adversarial GAN Text_Generation Language_Model
author: Tianxiao Shen, Jonas Mueller, Regina Barzilay, Tommi Jaakkola
mathjax: true
---

* content
{:toc}

##### Abstract
While neural language models have recently demonstrated impressive performance in unconditional text generation, controllable generation and manipulation of text remain challenging. Latent variable generative models provide a natural approach for control, but their application to text has proven more difficult than to images. Models such as variational autoencoders may suffer from posterior collapse or learning an irregular latent geometry. We propose to instead employ adversarial autoencoders (AAEs) and add local perturbations by randomly replacing/removing words from input sentences during training. Within the prior enforced by the adversary, structured perturbations in the data space begin to carve and organize the latent space. Theoretically, we prove that perturbations encourage similar sentences to map to similar latent representations. Experimentally, we investigate the trade-off between text-generation and autoencoder-reconstruction capabilities. Our straightforward approach significantly improves over regular AAEs as well as other autoencoders, and enables altering the tense/sentiment of sentences through simple addition of a fixed vector offset to their latent representation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12777](http://arxiv.org/abs/1905.12777)

##### PDF
[http://arxiv.org/pdf/1905.12777](http://arxiv.org/pdf/1905.12777)

