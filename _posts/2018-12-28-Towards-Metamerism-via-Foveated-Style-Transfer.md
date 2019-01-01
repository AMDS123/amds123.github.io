---
layout: post
title: "Towards Metamerism via Foveated Style Transfer"
date: 2018-12-28 22:37:48
categories: arXiv_CV
tags: arXiv_CV Style_Transfer Optimization
author: Arturo Deza, Aditya Jonnalagadda, Miguel Eckstein
mathjax: true
---

* content
{:toc}

##### Abstract
The problem of $\textit{visual metamerism}$ is defined as finding a family of perceptually indistinguishable, yet physically different images. In this paper, we propose our NeuroFovea metamer model, a foveated generative model that is based on a mixture of peripheral representations and style transfer forward-pass algorithms. Our gradient-descent free model is parametrized by a foveated VGG19 encoder-decoder which allows us to encode images in high dimensional space and interpolate between the content and texture information with adaptive instance normalization anywhere in the visual field. Our contributions include: 1) A framework for computing metamers that resembles a noisy communication system via a foveated feed-forward encoder-decoder network -- We observe that metamerism arises as a byproduct of noisy perturbations that partially lie in the perceptual null space; 2) A perceptual optimization scheme as a solution to the hyperparametric nature of our metamer model that requires tuning of the image-texture tradeoff coefficients everywhere in the visual field which are a consequence of internal noise; 3) An ABX psychophysical evaluation of our metamers where we also find that the rate of growth of the receptive fields in our model match V1 for reference metamers and V2 between synthesized samples. Our model also renders metamers at roughly a second, presenting a $\times1000$ speed-up compared to the previous work, which allows for tractable data-driven metamer experiments.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1705.10041](http://arxiv.org/abs/1705.10041)

##### PDF
[http://arxiv.org/pdf/1705.10041](http://arxiv.org/pdf/1705.10041)

