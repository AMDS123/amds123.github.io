---
layout: post
title: "Every Smile is Unique: Landmark-Guided Diverse Smile Generation"
date: 2018-02-06 10:15:39
categories: arXiv_CV
tags: arXiv_CV Face Embedding Deep_Learning
author: Wang Wei, Xavier Alameda-Pineda, Dan Xu, Elisa Ricci, Nicu Sebe
mathjax: true
---

* content
{:toc}

##### Abstract
Each smile is unique: one person surely smiles in different ways (e.g., closing/opening the eyes or mouth). Given one input image of a neutral face, can we generate multiple smile videos with distinctive characteristics? To tackle this one-to-many video generation problem, we propose a novel deep learning architecture named Conditional Multi-Mode Network (CMM-Net). To better encode the dynamics of facial expressions, CMM-Net explicitly exploits facial landmarks for generating smile sequences. Specifically, a variational auto-encoder is used to learn a facial landmark embedding. This single embedding is then exploited by a conditional recurrent network which generates a landmark embedding sequence conditioned on a specific expression (e.g., spontaneous smile). Next, the generated landmark embeddings are fed into a multi-mode recurrent landmark generator, producing a set of landmark sequences still associated to the given smile class but clearly distinct from each other. Finally, these landmark sequences are translated into face videos. Our experimental results demonstrate the effectiveness of our CMM-Net in generating realistic videos of multiple smile expressions.

##### Abstract (translated by Google)
每一个微笑都是独一无二的：一个人肯定以不同的方式微笑（例如关闭/打开眼睛或嘴巴）。给定一张中性脸部的输入图像，我们可以生成具有鲜明特色的多个笑脸视频吗？为了解决这个一对多的视频生成问题，我们提出了一种名为条件多模式网络（CMM-Net）的新型深度学习体系结构。为了更好地对面部表情的动态进行编码，CMM-Net明确地利用面部标志来产生微笑序列。具体来说，使用变分自动编码器来学习面部标志嵌入。然后利用有条件的递归网络利用这种单一的嵌入，该网络产生一个以特定表达式（例如，自发的笑容）为条件的地标嵌入序列。接下来，生成的地标嵌入被馈送到多模式递归地标生成器中，产生仍然与给定微笑类别相关但是彼此明显不同的一组地标序列。最后，这些地标序列被翻译成脸部视频。我们的实验结果证明了我们的CMM-Net在生成多个微笑表情的真实视频方面的有效性。

##### URL
[http://arxiv.org/abs/1802.01873](http://arxiv.org/abs/1802.01873)

##### PDF
[http://arxiv.org/pdf/1802.01873](http://arxiv.org/pdf/1802.01873)

