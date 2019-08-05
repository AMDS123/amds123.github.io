---
layout: post
title: "A high performance computing method for accelerating temporal action proposal generation"
date: 2019-08-02 05:12:50
categories: arXiv_CV
tags: arXiv_CV Face Action_Recognition CNN Deep_Learning Recognition
author: Shiye Lei, Tian Wang, Youyou Jiang, Zihang Deng, Hichem Snoussi, Chang Choi
mathjax: true
---

* content
{:toc}

##### Abstract
Temporal action proposal generation, coming from temporal action recognition, is an important and challenging problem in computer vision. Because of the big capacity of video files, the speed of temporal action recognition is difficult for both researchers and companies. To training a convolutional neural network (CNN) for temporal action recognition, a lot of videos are required to put into the CNN. A speed-up for the task should be proposed for the training process to achieve the faster response of temporal action recognition system. To address it, we implement ring parallel architecture by Massage Passing Interface (MPI). Different from traditional parameter server architecture, total data transmission is reduced by adding a connection between multiple computing load in our new architecture. Compared to parameter server architecture, our parallel architecture has higher efficiency on temporal action proposal generation task with multiple GPUs, which is significant to dealing with large-scale video database. And based on the absence of evaluating time consumption in a distributed deep learning system, we proposed a concept of training time metrics which can assess the performance in the distributed training process.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06496](http://arxiv.org/abs/1906.06496)

##### PDF
[http://arxiv.org/pdf/1906.06496](http://arxiv.org/pdf/1906.06496)

