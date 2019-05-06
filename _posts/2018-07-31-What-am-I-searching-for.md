---
layout: post
title: "What am I searching for?"
date: 2018-07-31 17:15:11
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Mengmi Zhang, Jiashi Feng, Joo Hwee Lim, Qi Zhao, Gabriel Kreiman
mathjax: true
---

* content
{:toc}

##### Abstract
Can we infer intentions and goals from a person's actions? As an example of this family of problems, we consider here whether it is possible to decipher what a person is searching for by decoding their eye movement behavior. We conducted two human psychophysics experiments on object arrays and natural images where we monitored subjects' eye movements while they were looking for a target object. Using as input the pattern of "error" fixations on non-target objects before the target was found, we developed a model (InferNet) whose goal was to infer what the target was. "Error" fixations share similar features with the sought target. The Infernet model uses a pre-trained 2D convolutional architecture to extract features from the error fixations and computes a 2D similarity map between the error fixation and all locations across the search image by modulating the search image via convolution across layers. InferNet consolidates the modulated response maps across layers via max pooling to keep track of the sub-patterns highly similar to features at error fixations and integrates these maps across all error fixations. InferNet successfully identifies the subject's goal and outperforms all the competitive null models, even without any object-specific training on the inference task.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1807.11926](https://arxiv.org/abs/1807.11926)

##### PDF
[https://arxiv.org/pdf/1807.11926](https://arxiv.org/pdf/1807.11926)

