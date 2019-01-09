---
layout: post
title: "FastGRNN: A Fast, Accurate, Stable and Tiny Kilobyte Sized Gated Recurrent Neural Network"
date: 2019-01-08 15:19:13
categories: arXiv_AI
tags: arXiv_AI Sparse RNN Prediction
author: Aditya Kusupati, Manish Singh, Kush Bhatia, Ashish Kumar, Prateek Jain, Manik Varma
mathjax: true
---

* content
{:toc}

##### Abstract
This paper develops the FastRNN and FastGRNN algorithms to address the twin RNN limitations of inaccurate training and inefficient prediction. Previous approaches have improved accuracy at the expense of prediction costs making them infeasible for resource-constrained and real-time applications. Unitary RNNs have increased accuracy somewhat by restricting the range of the state transition matrix's singular values but have also increased the model size as they require a larger number of hidden units to make up for the loss in expressive power. Gated RNNs have obtained state-of-the-art accuracies by adding extra parameters thereby resulting in even larger models. FastRNN addresses these limitations by adding a residual connection that does not constrain the range of the singular values explicitly and has only two extra scalar parameters. FastGRNN then extends the residual connection to a gate by reusing the RNN matrices to match state-of-the-art gated RNN accuracies but with a 2-4x smaller model. Enforcing FastGRNN's matrices to be low-rank, sparse and quantized resulted in accurate models that could be up to 35x smaller than leading gated and unitary RNNs. This allowed FastGRNN to accurately recognize the "Hey Cortana" wakeword with a 1 KB model and to be deployed on severely resource-constrained IoT microcontrollers too tiny to store other RNN models. FastGRNN's code is available at https://github.com/Microsoft/EdgeML/.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.02358](http://arxiv.org/abs/1901.02358)

##### PDF
[http://arxiv.org/pdf/1901.02358](http://arxiv.org/pdf/1901.02358)

