---
layout: post
title: "Efficient Contextualized Representation: Language Model Pruning for Sequence Labeling"
date: 2018-09-10 17:24:49
categories: arXiv_CL
tags: arXiv_CL Regularization Inference Language_Model
author: Liyuan Liu, Xiang Ren, Jingbo Shang, Jian Peng, Jiawei Han
mathjax: true
---

* content
{:toc}

##### Abstract
Many efforts have been made to facilitate natural language processing tasks with pre-trained language models (LMs), and brought significant improvements to various applications. To fully leverage the nearly unlimited corpora and capture linguistic information of multifarious levels, large-size LMs are required; but for a specific task, only parts of these information are useful. Such large-sized LMs, even in the inference stage, may cause heavy computation workloads, making them too time-consuming for large-scale applications. Here we propose to compress bulky LMs while preserving useful information with regard to a specific task. As different layers of the model keep different information, we develop a layer selection method for model pruning using sparsity-inducing regularization. By introducing the dense connectivity, we can detach any layer without affecting others, and stretch shallow and wide LMs to be deep and narrow. In model training, LMs are learned with layer-wise dropouts for better robustness. Experiments on two benchmark datasets demonstrate the effectiveness of our method.

##### Abstract (translated by Google)
已经做出许多努力来利用预训练的语言模型（LM）来促进自然语言处理任务，并且对各种应用带来了显着的改进。为了充分利用几乎无限的语料库并捕获各种级别的语言信息，需要大尺寸的LM;但对于特定任务，只有部分信息是有用的。即使在推理阶段，这样的大尺寸LM也可能导致繁重的计算工作量，这使得它们对于大规模应用而言太耗时。在这里，我们建议压缩笨重的LM，同时保留关于特定任务的有用信息。由于模型的不同层保持不同的信息，我们开发了一种使用稀疏诱导正则化进行模型修剪的层选择方法。通过引入密集连接，我们可以在不影响其他层的情况下分离任何层，并且可以将浅而宽的LM拉伸为深而窄。在模型训练中，通过分层丢失来学习LM，以获得更好的稳健性。两个基准数据集的实验证明了我们方法的有效性。

##### URL
[http://arxiv.org/abs/1804.07827](http://arxiv.org/abs/1804.07827)

##### PDF
[http://arxiv.org/pdf/1804.07827](http://arxiv.org/pdf/1804.07827)

