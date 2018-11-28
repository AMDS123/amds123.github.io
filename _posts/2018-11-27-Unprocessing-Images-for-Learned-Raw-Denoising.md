---
layout: post
title: "Unprocessing Images for Learned Raw Denoising"
date: 2018-11-27 17:38:14
categories: arXiv_CV
tags: arXiv_CV CNN
author: Tim Brooks, Ben Mildenhall, Tianfan Xue, Jiawen Chen, Dillon Sharlet, Jonathan T. Barron
mathjax: true
---

* content
{:toc}

##### Abstract
Machine learning techniques work best when the data used for training resembles the data used for evaluation. This holds true for learned single-image denoising algorithms, which are applied to real raw camera sensor readings but, due to practical constraints, are often trained on synthetic image data. Though it is understood that generalizing from synthetic to real data requires careful consideration of the noise properties of image sensors, the other aspects of a camera's image processing pipeline (gain, color correction, tone mapping, etc) are often overlooked, despite their significant effect on how raw measurements are transformed into finished images. To address this, we present a technique to "unprocess" images by inverting each step of an image processing pipeline, thereby allowing us to synthesize realistic raw sensor measurements from commonly available internet photos. We additionally model the relevant components of an image processing pipeline when evaluating our loss function, which allows training to be aware of all relevant photometric processing that will occur after denoising. By processing and unprocessing model outputs and training data in this way, we are able to train a simple convolutional neural network that has 14%-38% lower error rates and is 9x-18x faster than the previous state of the art on the Darmstadt Noise Dataset, and generalizes to sensors outside of that dataset as well.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11127](http://arxiv.org/abs/1811.11127)

##### PDF
[http://arxiv.org/pdf/1811.11127](http://arxiv.org/pdf/1811.11127)

