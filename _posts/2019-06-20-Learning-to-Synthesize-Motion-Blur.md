---
layout: post
title: "Learning to Synthesize Motion Blur"
date: 2019-06-20 07:28:50
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Tim Brooks, Jonathan T. Barron
mathjax: true
---

* content
{:toc}

##### Abstract
We present a technique for synthesizing a motion blurred image from a pair of unblurred images captured in succession. To build this system we motivate and design a differentiable "line prediction" layer to be used as part of a neural network architecture, with which we can learn a system to regress from image pairs to motion blurred images that span the capture time of the input image pair. Training this model requires an abundance of data, and so we design and execute a strategy for using frame interpolation techniques to generate a large-scale synthetic dataset of motion blurred images and their respective inputs. We additionally capture a high quality test set of real motion blurred images, synthesized from slow motion videos, with which we evaluate our model against several baseline techniques that can be used to synthesize motion blur. Our model produces higher accuracy output than our baselines, and is significantly faster than baselines with competitive accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11745](http://arxiv.org/abs/1811.11745)

##### PDF
[http://arxiv.org/pdf/1811.11745](http://arxiv.org/pdf/1811.11745)

