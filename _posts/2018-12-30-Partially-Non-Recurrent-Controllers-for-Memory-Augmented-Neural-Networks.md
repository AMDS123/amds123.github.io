---
layout: post
title: "Partially Non-Recurrent Controllers for Memory-Augmented Neural Networks"
date: 2018-12-30 07:59:04
categories: arXiv_CV
tags: arXiv_CV RNN
author: Naoya Taguchi, Yoshimasa Tsuruoka
mathjax: true
---

* content
{:toc}

##### Abstract
Memory-Augmented Neural Networks (MANNs) are a class of neural networks equipped with an external memory, and are reported to be effective for tasks requiring a large long-term memory and its selective use. The core module of a MANN is called a controller, which is usually implemented as a recurrent neural network (RNN) (e.g., LSTM) to enable the use of contextual information in controlling the other modules. However, such an RNN-based controller often allows a MANN to directly solve the given task by using the (small) internal memory of the controller, and prevents the MANN from making the best use of the external memory, thereby resulting in a suboptimally trained model. To address this problem, we present a novel type of RNN-based controller that is partially non-recurrent and avoids the direct use of its internal memory for solving the task, while keeping the ability of using contextual information in controlling the other modules. Our empirical experiments using Neural Turing Machines and Differentiable Neural Computers on the Toy and bAbI tasks demonstrate that the proposed controllers give substantially better results than standard RNN-based controllers.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1812.11485](https://arxiv.org/abs/1812.11485)

##### PDF
[https://arxiv.org/pdf/1812.11485](https://arxiv.org/pdf/1812.11485)

