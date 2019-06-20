---
layout: post
title: "Pre-Training with Whole Word Masking for Chinese BERT"
date: 2019-06-19 13:54:25
categories: arXiv_CL
tags: arXiv_CL Sentiment Sentiment_Classification Inference Classification Language_Model Recognition
author: Yiming Cui, Wanxiang Che, Ting Liu, Bing Qin, Ziqing Yang, Shijin Wang, Guoping Hu
mathjax: true
---

* content
{:toc}

##### Abstract
Bidirectional Encoder Representations from Transformers (BERT) has shown marvelous improvements across various NLP tasks. Recently, an upgraded version of BERT has been released with Whole Word Masking (WWM), which mitigate the drawbacks of masking partial WordPiece tokens in pre-training BERT. In this technical report, we adapt whole word masking in Chinese text, that masking the whole word instead of masking Chinese characters, which could bring another challenge in Masked Language Model (MLM) pre-training task. The model was trained on the latest Chinese Wikipedia dump. We aim to provide easy extensibility and better performance for Chinese BERT without changing any neural architecture or even hyper-parameters. The model is verified on various NLP tasks, across sentence-level to document-level, including sentiment classification (ChnSentiCorp, Sina Weibo), named entity recognition (People Daily, MSRA-NER), natural language inference (XNLI), sentence pair matching (LCQMC, BQ Corpus), and machine reading comprehension (CMRC 2018, DRCD, CAIL RC). Experimental results on these datasets show that the whole word masking could bring another significant gain. Moreover, we also examine the effectiveness of Chinese pre-trained models: BERT, ERNIE, BERT-wwm. We release the pre-trained model (both TensorFlow and PyTorch) on GitHub: https://github.com/ymcui/Chinese-BERT-wwm

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08101](http://arxiv.org/abs/1906.08101)

##### PDF
[http://arxiv.org/pdf/1906.08101](http://arxiv.org/pdf/1906.08101)

