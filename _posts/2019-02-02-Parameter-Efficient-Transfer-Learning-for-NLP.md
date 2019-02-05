---
layout: post
title: "Parameter-Efficient Transfer Learning for NLP"
date: 2019-02-02 16:29:47
categories: arXiv_CL
tags: arXiv_CL Text_Classification Transfer_Learning Classification
author: Neil Houlsby, Andrei Giurgiu, Stanislaw Jastrzebski, Bruna Morrone, Quentin de Laroussilhe, Andrea Gesmundo, Mona Attariyan, Sylvain Gelly
mathjax: true
---

* content
{:toc}

##### Abstract
Fine-tuning large pre-trained models is an effective transfer mechanism in NLP. However, in the presence of many downstream tasks, fine-tuning is parameter inefficient: an entire new model is required for every task. As an alternative, we propose transfer with adapter modules. Adapter modules yield a compact and extensible model; they add only a few trainable parameters per task, and new tasks can be added without revisiting previous ones. The parameters of the original network remain fixed, yielding a high degree of parameter sharing. To demonstrate adapter's effectiveness, we transfer the recently proposed BERT Transformer model to 26 diverse text classification tasks, including the GLUE benchmark. Adapters attain near state-of-the-art performance, whilst adding only a few parameters per task. On GLUE, we attain within 0.4% of the performance of full fine-tuning, adding only 3.6% parameters per task. By contrast, fine-tuning trains 100% of the parameters per task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.00751](http://arxiv.org/abs/1902.00751)

##### PDF
[http://arxiv.org/pdf/1902.00751](http://arxiv.org/pdf/1902.00751)

