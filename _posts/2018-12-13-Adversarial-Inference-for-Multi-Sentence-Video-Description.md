---
layout: post
title: "Adversarial Inference for Multi-Sentence Video Description"
date: 2018-12-13 19:07:17
categories: arXiv_CV
tags: arXiv_CV Image_Caption Adversarial Video_Caption GAN Caption Inference
author: Jae Sung Park, Marcus Rohrbach, Trevor Darrell, Anna Rohrbach
mathjax: true
---

* content
{:toc}

##### Abstract
While significant progress has been made in the image captioning task, video description is still comparatively in its infancy, due to the complex nature of video data. Generating multi-sentence descriptions for long videos is even more challenging. Among the main issues are the fluency and coherence of the generated descriptions, and their relevance to the video. Recently, reinforcement and adversarial learning based methods have been explored to improve the image captioning models; however, both types of methods suffer from a number of issues, e.g. poor readability and high redundancy for RL and stability issues for GANs. In this work, we instead propose to apply adversarial techniques during inference, designing a discriminator which encourages better multi-sentence video description. In addition, we find that a multi-discriminator "hybrid" design, where each discriminator targets one aspect of a description, leads to the best results. Specifically, we decouple the discriminator to evaluate on three criteria: 1) visual relevance to the video, 2) language diversity and fluency, and 3) coherence across sentences. Our approach results in more accurate, diverse and coherent multi-sentence video descriptions, as shown by automatic as well as human evaluation on the popular ActivityNet Captions dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.05634](http://arxiv.org/abs/1812.05634)

##### PDF
[http://arxiv.org/pdf/1812.05634](http://arxiv.org/pdf/1812.05634)

