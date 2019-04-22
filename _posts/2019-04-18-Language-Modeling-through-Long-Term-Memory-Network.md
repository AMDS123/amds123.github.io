---
layout: post
title: "Language Modeling through Long Term Memory Network"
date: 2019-04-18 09:19:25
categories: arXiv_CL
tags: arXiv_CL RNN Language_Model Relation Memory_Networks
author: Anupiya Nugaliyadde, Kok Wai Wong, Ferdous Sohel, Hong Xie
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent Neural Networks (RNN), Long Short-Term Memory Networks (LSTM), and Memory Networks which contain memory are popularly used to learn patterns in sequential data. Sequential data has long sequences that hold relationships. RNN can handle long sequences but suffers from the vanishing and exploding gradient problems. While LSTM and other memory networks address this problem, they are not capable of handling long sequences (50 or more data points long sequence patterns). Language modelling requiring learning from longer sequences are affected by the need for more information in memory. This paper introduces Long Term Memory network (LTM), which can tackle the exploding and vanishing gradient problems and handles long sequences without forgetting. LTM is designed to scale data in the memory and gives a higher weight to the input in the sequence. LTM avoid overfitting by scaling the cell state after achieving the optimal results. The LTM is tested on Penn treebank dataset, and Text8 dataset and LTM achieves test perplexities of 83 and 82 respectively. 650 LTM cells achieved a test perplexity of 67 for Penn treebank, and 600 cells achieved a test perplexity of 77 for Text8. LTM achieves state of the art results by only using ten hidden LTM cells for both datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08936](http://arxiv.org/abs/1904.08936)

##### PDF
[http://arxiv.org/pdf/1904.08936](http://arxiv.org/pdf/1904.08936)

