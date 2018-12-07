---
layout: post
title: "ForensicTransfer: Weakly-supervised Domain Adaptation for Forgery Detection"
date: 2018-12-06 13:11:09
categories: arXiv_CV
tags: arXiv_CV Object_Detection Embedding CNN Detection
author: Davide Cozzolino, Justus Thies, Andreas R&#xf6;ssler, Christian Riess, Matthias Nie&#xdf;ner, Luisa Verdoliva
mathjax: true
---

* content
{:toc}

##### Abstract
Distinguishing fakes from real images is becoming increasingly difficult as new sophisticated image manipulation approaches come out by the day. Convolutional neural networks (CNN) show excellent performance in detecting image manipulations when they are trained on a specific forgery method. However, on examples from unseen manipulation approaches, their performance drops significantly. To address this limitation in transferability, we introduce ForensicTransfer. ForensicTransfer tackles two challenges in multimedia forensics. First, we devise a learning-based forensic detector which adapts well to new domains, i.e., novel manipulation methods. Second we handle scenarios where only a handful of fake examples are available during training. To this end, we learn a forensic embedding that can be used to distinguish between real and fake imagery. We are using a new autoencoder-based architecture which enforces activations in different parts of a latent vector for the real and fake classes. Together with the constraint of correct reconstruction this ensures that the latent space keeps all the relevant information about the nature of the image. Therefore, the learned embedding acts as a form of anomaly detector; namely, an image manipulated from an unseen method will be detected as fake provided it maps sufficiently far away from the cluster of real images. Comparing with prior works, ForensicTransfer shows significant improvements in transferability, which we demonstrate in a series of experiments on cutting-edge benchmarks. For instance, on unseen examples, we achieve up to 80-85% in terms of accuracy compared to 50-59%, and with only a handful of seen examples, our performance already reaches around 95%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.02510](http://arxiv.org/abs/1812.02510)

##### PDF
[http://arxiv.org/pdf/1812.02510](http://arxiv.org/pdf/1812.02510)

