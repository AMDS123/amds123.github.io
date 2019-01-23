---
layout: post
title: "Training Neural Networks with Local Error Signals"
date: 2019-01-20 10:59:53
categories: arXiv_CV
tags: arXiv_CV Optimization Classification Deep_Learning
author: Arild N&#xf8;kland, Lars Hiller Eidnes
mathjax: true
---

* content
{:toc}

##### Abstract
Supervised training of neural networks for classification is typically performed with a global loss function. The loss function provides a gradient for the output layer, and this gradient is back-propagated to hidden layers to dictate an update direction for the weights. An alternative approach is to train the network with layer-wise loss functions. In this paper we demonstrate, for the first time, that layer-wise training can approach the state-of-the-art on a variety of image datasets. We use single-layer sub-networks and two different supervised loss functions to generate local error signals for the hidden layers, and we show that the combination of these losses help with optimization in the context of local learning. Using local errors could be a step towards more biologically plausible deep learning because the global error does not have to be transported back to hidden layers. A completely backprop free variant outperforms previously reported results among methods aiming for higher biological plausibility. Code is available https://github.com/anokland/local-loss

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.06656](http://arxiv.org/abs/1901.06656)

##### PDF
[http://arxiv.org/pdf/1901.06656](http://arxiv.org/pdf/1901.06656)

