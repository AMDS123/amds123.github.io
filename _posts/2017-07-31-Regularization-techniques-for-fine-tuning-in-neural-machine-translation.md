---
layout: post
title: "Regularization techniques for fine-tuning in neural machine translation"
date: 2017-07-31 15:31:12
categories: arXiv_CL
tags: arXiv_CL Regularization NMT
author: Antonio Valerio Miceli Barone, Barry Haddow, Ulrich Germann, Rico Sennrich
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate techniques for supervised domain adaptation for neural machine translation where an existing model trained on a large out-of-domain dataset is adapted to a small in-domain dataset. In this scenario, overfitting is a major challenge. We investigate a number of techniques to reduce overfitting and improve transfer learning, including regularization techniques such as dropout and L2-regularization towards an out-of-domain prior. In addition, we introduce tuneout, a novel regularization technique inspired by dropout. We apply these techniques, alone and in combination, to neural machine translation, obtaining improvements on IWSLT datasets for English->German and English->Russian. We also investigate the amounts of in-domain training data needed for domain adaptation in NMT, and find a logarithmic relationship between the amount of training data and gain in BLEU score.

##### Abstract (translated by Google)
我们调查神经机器翻译监督领域适应的技术，在一个大的域外数据集上训练的现有模型适应于一个小的域内数据集。在这种情况下，过度配合是一个重大挑战。我们调查了一些技术，以减少过度拟合，并提高转移学习，包括正规化技术，如辍学和二次正规化领域之外的事先。另外，我们引入了一个新的正规化技术tuneout，这个技术受到了辍学的启发。我们将这些技术单独或组合应用于神经机器翻译，在英语 - >德语和英语 - >俄语中获得IWSLT数据集的改进。我们还调查NMT领域适应所需的域内训练数据量，并找到训练数据量与BLEU得分增益之间的对数关系。

##### URL
[https://arxiv.org/abs/1707.09920](https://arxiv.org/abs/1707.09920)

