---
layout: post
title: "Dual Control Memory Augmented Neural Networks for Treatment Recommendations"
date: 2018-02-11 03:50:41
categories: arXiv_CV
tags: arXiv_CV Prediction Recommendation
author: Hung Le, Truyen Tran, Svetha Venkatesh
mathjax: true
---

* content
{:toc}

##### Abstract
Machine-assisted treatment recommendations hold a promise to reduce physician time and decision errors. We formulate the task as a sequence-to-sequence prediction model that takes the entire time-ordered medical history as input, and predicts a sequence of future clinical procedures and medications. It is built on the premise that an effective treatment plan may have long-term dependencies from previous medical history. We approach the problem by using a memory-augmented neural network, in particular, by leveraging the recent differentiable neural computer that consists of a neural controller and an external memory module. But differing from the original model, we use dual controllers, one for encoding the history followed by another for decoding the treatment sequences. In the encoding phase, the memory is updated as new input is read; at the end of this phase, the memory holds not only the medical history but also the information about the current illness. During the decoding phase, the memory is write-protected. The decoding controller generates a treatment sequence, one treatment option at a time. The resulting dual controller write-protected memory-augmented neural network is demonstrated on the MIMIC-III dataset on two tasks: procedure prediction and medication prescription. The results show improved performance over both traditional bag-of-words and sequence-to-sequence methods.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1802.03689](https://arxiv.org/abs/1802.03689)

##### PDF
[https://arxiv.org/pdf/1802.03689](https://arxiv.org/pdf/1802.03689)

