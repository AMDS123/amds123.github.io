---
layout: post
title: "Making the V in VQA Matter: Elevating the Role of Image Understanding in Visual Question Answering"
date: 2017-05-15 17:58:49
categories: arXiv_CV
tags: arXiv_CV Image_Caption QA VQA
author: Yash Goyal, Tejas Khot, Douglas Summers-Stay, Dhruv Batra, Devi Parikh
mathjax: true
---

* content
{:toc}

##### Abstract
Problems at the intersection of vision and language are of significant importance both as challenging research questions and for the rich set of applications they enable. However, inherent structure in our world and bias in our language tend to be a simpler signal for learning than visual modalities, resulting in models that ignore visual information, leading to an inflated sense of their capability. We propose to counter these language priors for the task of Visual Question Answering (VQA) and make vision (the V in VQA) matter! Specifically, we balance the popular VQA dataset by collecting complementary images such that every question in our balanced dataset is associated with not just a single image, but rather a pair of similar images that result in two different answers to the question. Our dataset is by construction more balanced than the original VQA dataset and has approximately twice the number of image-question pairs. Our complete balanced dataset is publicly available at www.visualqa.org as part of the 2nd iteration of the Visual Question Answering Dataset and Challenge (VQA v2.0). We further benchmark a number of state-of-art VQA models on our balanced dataset. All models perform significantly worse on our balanced dataset, suggesting that these models have indeed learned to exploit language priors. This finding provides the first concrete empirical evidence for what seems to be a qualitative sense among practitioners. Finally, our data collection protocol for identifying complementary images enables us to develop a novel interpretable model, which in addition to providing an answer to the given (image, question) pair, also provides a counter-example based explanation. Specifically, it identifies an image that is similar to the original image, but it believes has a different answer to the same question. This can help in building trust for machines among their users.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1612.00837](https://arxiv.org/abs/1612.00837)

##### PDF
[https://arxiv.org/pdf/1612.00837](https://arxiv.org/pdf/1612.00837)

