---
layout: post
title: "All-Weather Deep Outdoor Lighting Estimation"
date: 2019-06-12 03:19:08
categories: arXiv_CV
tags: arXiv_CV
author: Jinsong Zhang, Kalyan Sunkavalli, Yannick Hold-Geoffroy, Sunil Hadap, Jonathan Eisenmann, Jean-Fran&#xe7;ois Lalonde
mathjax: true
---

* content
{:toc}

##### Abstract
We present a neural network that predicts HDR outdoor illumination from a single LDR image. At the heart of our work is a method to accurately learn HDR lighting from LDR panoramas under any weather condition. We achieve this by training another CNN (on a combination of synthetic and real images) to take as input an LDR panorama, and regress the parameters of the Lalonde-Matthews outdoor illumination model. This model is trained such that it a) reconstructs the appearance of the sky, and b) renders the appearance of objects lit by this illumination. We use this network to label a large-scale dataset of LDR panoramas with lighting parameters and use them to train our single image outdoor lighting estimation network. We demonstrate, via extensive experiments, that both our panorama and single image networks outperform the state of the art, and unlike prior work, are able to handle weather conditions ranging from fully sunny to overcast skies.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04909](http://arxiv.org/abs/1906.04909)

##### PDF
[http://arxiv.org/pdf/1906.04909](http://arxiv.org/pdf/1906.04909)

