---
layout: post
title: "Channel-wise pruning of neural networks with tapering resource constraint"
date: 2018-12-04 10:41:09
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Optimization
author: Alexey Kruglov
mathjax: true
---

* content
{:toc}

##### Abstract
Neural network pruning is an important step in design process of efficient neural networks for edge devices with limited computational power. Pruning is a form of knowledge transfer from the weights of the original network to a smaller target subnetwork. We propose a new method for compute-constrained structured channel-wise pruning of convolutional neural networks. The method iteratively fine-tunes the network, while gradually tapering the computation resources available to the pruned network via a holonomic constraint in the method of Lagrangian multipliers framework. An explicit and adaptive automatic control over the rate of tapering is provided. The trainable parameters of our pruning method are separate from the weights of the neural network, which allows us to avoid the interference with the neural network solver (e.g. avoid the direct dependence of pruning speed on neural network learning rates). Our method combines the `rigoristic' approach by the direct application of constrained optimization, avoiding the pitfalls of ADMM-based methods, like their need to define the target amount of resources for each pruning run, and direct dependence of pruning speed and priority of pruning on the relative scale of weights between layers. For VGG-16 @ ILSVRC-2012, we achieve reduction of 15.47 -&gt; 3.87 GMAC with only 1% top-1 accuracy reduction (68.4% -&gt; 67.4%). For AlexNet @ ILSVRC-2012, we achieve 0.724 -&gt; 0.411 GMAC with 1% top-1 accuracy reduction (56.8% -&gt; 55.8%).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07060](http://arxiv.org/abs/1812.07060)

##### PDF
[http://arxiv.org/pdf/1812.07060](http://arxiv.org/pdf/1812.07060)

