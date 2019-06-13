---
layout: post
title: "Continual and Multi-Task Architecture Search"
date: 2019-06-12 16:01:35
categories: arXiv_CV
tags: arXiv_CV Video_Caption Knowledge Caption Image_Classification Classification Language_Model
author: Ramakanth Pasunuru, Mohit Bansal
mathjax: true
---

* content
{:toc}

##### Abstract
Architecture search is the process of automatically learning the neural model or cell structure that best suits the given task. Recently, this approach has shown promising performance improvements (on language modeling and image classification) with reasonable training speed, using a weight sharing strategy called Efficient Neural Architecture Search (ENAS). In our work, we first introduce a novel continual architecture search (CAS) approach, so as to continually evolve the model parameters during the sequential training of several tasks, without losing performance on previously learned tasks (via block-sparsity and orthogonality constraints), thus enabling life-long learning. Next, we explore a multi-task architecture search (MAS) approach over ENAS for finding a unified, single cell structure that performs well across multiple tasks (via joint controller rewards), and hence allows more generalizable transfer of the cell structure knowledge to an unseen new task. We empirically show the effectiveness of our sequential continual learning and parallel multi-task learning based architecture search approaches on diverse sentence-pair classification tasks (GLUE) and multimodal-generation based video captioning tasks. Further, we present several ablations and analyses on the learned cell structures.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.05226](http://arxiv.org/abs/1906.05226)

##### PDF
[http://arxiv.org/pdf/1906.05226](http://arxiv.org/pdf/1906.05226)

