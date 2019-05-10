---
layout: post
title: "Interactive Image Generation Using Scene Graphs"
date: 2019-05-09 16:39:31
categories: arXiv_AI
tags: arXiv_AI Adversarial Image_Generation CNN
author: Gaurav Mittal, Shubham Agrawal, Anuva Agarwal, Sushant Mehta, Tanya Marwah
mathjax: true
---

* content
{:toc}

##### Abstract
Recent years have witnessed some exciting developments in the domain of generating images from scene-based text descriptions. These approaches have primarily focused on generating images from a static text description and are limited to generating images in a single pass. They are unable to generate an image interactively based on an incrementally additive text description (something that is more intuitive and similar to the way we describe an image). We propose a method to generate an image incrementally based on a sequence of graphs of scene descriptions (scene-graphs). We propose a recurrent network architecture that preserves the image content generated in previous steps and modifies the cumulative image as per the newly provided scene information. Our model utilizes Graph Convolutional Networks (GCN) to cater to variable-sized scene graphs along with Generative Adversarial image translation networks to generate realistic multi-object images without needing any intermediate supervision during training. We experiment with Coco-Stuff dataset which has multi-object images along with annotations describing the visual scene and show that our model significantly outperforms other approaches on the same dataset in generating visually consistent images for incrementally growing scene graphs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.03743](http://arxiv.org/abs/1905.03743)

##### PDF
[http://arxiv.org/pdf/1905.03743](http://arxiv.org/pdf/1905.03743)

