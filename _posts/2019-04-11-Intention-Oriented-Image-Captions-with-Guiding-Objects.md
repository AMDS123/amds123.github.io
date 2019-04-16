---
layout: post
title: "Intention Oriented Image Captions with Guiding Objects"
date: 2019-04-11 08:36:21
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption RNN
author: Yue Zheng, Yali Li, Shengjin Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Although existing image caption models can produce promising results using recurrent neural networks (RNNs), it is difficult to guarantee that an object we care about is contained in generated descriptions, for example in the case that the object is inconspicuous in the image. Problems become even harder when these objects did not appear in training stage. In this paper, we propose a novel approach for generating image captions with guiding objects (CGO). The CGO constrains the model to involve a human-concerned object when the object is in the image. CGO ensures that the object is in the generated description while maintaining fluency. Instead of generating the sequence from left to right, we start the description with a selected object and generate other parts of the sequence based on this object. To achieve this, we design a novel framework combining two LSTMs in opposite directions. We demonstrate the characteristics of our method on MSCOCO where we generate descriptions for each detected object in the images. With CGO, we can extend the ability of description to the objects being neglected in image caption labels and provide a set of more comprehensive and diverse descriptions for an image. CGO shows advantages when applied to the task of describing novel objects. We show experimental results on both MSCOCO and ImageNet datasets. Evaluations show that our method outperforms the state-of-the-art models in the task with average F1 75.8, leading to better descriptions in terms of both content accuracy and fluency.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.07662](https://arxiv.org/abs/1811.07662)

##### PDF
[https://arxiv.org/pdf/1811.07662](https://arxiv.org/pdf/1811.07662)

