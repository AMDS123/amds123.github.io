---
layout: post
title: "Progressive Deep Neural Networks Acceleration via Soft Filter Pruning"
date: 2018-08-22 00:32:41
categories: arXiv_CV
tags: arXiv_CV Optimization Inference
author: Yang He, Xuanyi Dong, Guoliang Kang, Yanwei Fu, Yi Yang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposed a Progressive Soft Filter Pruning method (PSFP) to prune the filters of deep Neural Networks which can thus be accelerated in the inference. Specifically, the proposed PSFP method prunes the network progressively and enables the pruned filters to be updated when training the model after pruning. PSFP has three advantages over previous works: 1) Larger model capacity. Updating previously pruned filters provides our approach with larger optimization space than fixing the filters to zero. Therefore, the network trained by our method has a larger model capacity to learn from the training data. 2) Less dependence on the pre-trained model. Large capacity enables our method to train from scratch and prune the model simultaneously. In contrast, previous filter pruning methods should be conducted on the basis of the pre-trained model to guarantee their performance. Empirically, PSFP from scratch outperforms the previous filter pruning methods. 3) Pruning the neural network progressively makes the selection of low-norm filters much more stable, which has a potential to get a better performance. Moreover, our approach has been demonstrated effective for many advanced CNN architectures. Notably, on ILSCRC-2012, our method reduces more than 42% FLOPs on ResNet-101 with even 0.2% top-5 accuracy improvement, which has advanced the state-of-the-art. On ResNet-50, our progressive pruning method have 1.08% top-1 accuracy improvement over the pruning method without progressive pruning.

##### Abstract (translated by Google)
本文提出了一种渐进式软滤波器修剪方法（PSFP）来修剪深度神经网络的滤波器，从而加快推理速度。具体地，所提出的PSFP方法逐步修剪网络并且在修剪之后训练模型时能够更新修剪的滤波器。 PSFP比以前的工作有三个优点：1）更大的模型容量。更新先前已修剪的过滤器为我们的方法提供了比将过滤器固定为零更大的优化空间。因此，通过我们的方法训练的网络具有更大的模型能力来从训练数据中学习。 2）减少对预训练模型的依赖。大容量使我们的方法能够从头开始训练并同时修剪模型。相反，先前的过滤器修剪方法应该在预先训练的模型的基础上进行，以保证其性能。根据经验，从头开始的PSFP优于以前的过滤器修剪方法。 3）逐步修剪神经网络使得低范数滤波器的选择更加稳定，有可能获得更好的性能。此外，我们的方法已被证明对许多先进的CNN架构有效。值得注意的是，在ILSCRC-2012上，我们的方法减少了ResNet-101上超过42％的FLOP，甚至提高了0.2％的前5精度，这提高了最新技术水平。在ResNet-50上，我们的渐进修剪方法比没有渐进修剪的修剪方法具有1.08％的前1精度提高。

##### URL
[http://arxiv.org/abs/1808.07471](http://arxiv.org/abs/1808.07471)

##### PDF
[http://arxiv.org/pdf/1808.07471](http://arxiv.org/pdf/1808.07471)

