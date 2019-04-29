---
layout: post
title: "Divide, Denoise, and Defend against Adversarial Attacks"
date: 2019-04-25 22:32:22
categories: arXiv_AI
tags: arXiv_AI Adversarial
author: Seyed-Mohsen Moosavi-Dezfooli, Ashish Shrivastava, Oncel Tuzel
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks, although shown to be a successful class of machine learning algorithms, are known to be extremely unstable to adversarial perturbations. Improving the robustness of neural networks against these attacks is important, especially for security-critical applications. To defend against such attacks, we propose dividing the input image into multiple patches, denoising each patch independently, and reconstructing the image, without losing significant image content. We call our method D3. This proposed defense mechanism is non-differentiable which makes it non-trivial for an adversary to apply gradient-based attacks. Moreover, we do not fine-tune the network with adversarial examples, making it more robust against unknown attacks. We present an analysis of the tradeoff between accuracy and robustness against adversarial attacks. We evaluate our method under black-box, grey-box, and white-box settings. On the ImageNet dataset, our method outperforms the state-of-the-art by 19.7% under grey-box setting, and performs comparably under black-box setting. For the white-box setting, the proposed method achieves 34.4% accuracy compared to the 0% reported in the recent works.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1802.06806](http://arxiv.org/abs/1802.06806)

##### PDF
[http://arxiv.org/pdf/1802.06806](http://arxiv.org/pdf/1802.06806)

