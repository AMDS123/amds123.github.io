---
layout: post
title: "Training for 'Unstable' CNN Accelerator:A Case Study on FPGA"
date: 2018-12-02 11:45:07
categories: arXiv_CV
tags: arXiv_CV CNN
author: KouZi Xing
mathjax: true
---

* content
{:toc}

##### Abstract
With the great advancements of convolution neural networks(CNN), CNN accelerators are increasingly developed and deployed in the major computing systems.To make use of the CNN accelerators, CNN models are trained via the off-line training systems such as Caffe, Pytorch and Tensorflow on multi-core CPUs and GPUs first and then compiled to the target accelerators. Although the two-step process seems to be natural and has been widely applied, it assumes that the accelerators' behavior can be fully modeled on CPUs and GPUs. This does not hold true and the behavior of the CNN accelerators is un-deterministic when the circuit works at 'unstable' mode when it is overclocked or is affected by the environment like fault-prone aerospace. The exact behaviors of the accelerators are determined by both the chip fabrication and the working environment or status. In this case, applying the conventional off-line training result to the accelerators directly may lead to considerable accuracy loss. 
 To address this problem, we propose to train for the 'unstable' CNN accelerator and have the 'un-determined behavior' learned together with the data in the same framework. Basically, it starts from the off-line trained model and then integrates the uncertain circuit behaviors into the CNN models through additional accelerator-specific training. The fine-tuned training makes the CNN models less sensitive to the circuit uncertainty. We apply the design method to both an overclocked CNN accelerator and a faulty accelerator. According to our experiments on a subset of ImageNet, the accelerator-specific training can improve the top 5 accuracy up to 3.4% and 2.4% on average when the CNN accelerator is at extreme overclocking. When the accelerator is exposed to a faulty environment, the top 5 accuracy improves up to 6.8% and 4.28% on average under the most severe fault injection.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.01689](http://arxiv.org/abs/1812.01689)

##### PDF
[http://arxiv.org/pdf/1812.01689](http://arxiv.org/pdf/1812.01689)

