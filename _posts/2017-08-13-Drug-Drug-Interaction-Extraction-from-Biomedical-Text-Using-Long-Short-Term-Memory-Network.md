---
layout: post
title: "Drug-Drug Interaction Extraction from Biomedical Text Using Long Short Term Memory Network"
date: 2017-08-13 12:56:03
categories: arXiv_CV
tags: arXiv_CV Embedding RNN Classification
author: Sunil Kumar Sahu, Ashish Anand
mathjax: true
---

* content
{:toc}

##### Abstract
Simultaneous administration of multiple drugs can have synergistic or antagonistic effects as one drug can affect activities of other drugs. Synergistic effects lead to improved therapeutic outcomes, whereas, antagonistic effects can be life-threatening, may lead to increased healthcare cost, or may even cause death. Thus identification of unknown drug-drug interaction (DDI) is an important concern for efficient and effective healthcare. Although multiple resources for DDI exist, they are often unable to keep pace with rich amount of information available in fast growing biomedical texts. Most existing methods model DDI extraction from text as a classification problem and mainly rely on handcrafted features. Some of these features further depend on domain specific tools. Recently neural network models using latent features have been shown to give similar or better performance than the other existing models dependent on handcrafted features. In this paper, we present three models namely, {\it B-LSTM}, {\it AB-LSTM} and {\it Joint AB-LSTM} based on long short-term memory (LSTM) network. All three models utilize word and position embedding as latent features and thus do not rely on explicit feature engineering. Further use of bidirectional long short-term memory (Bi-LSTM) networks allow implicit feature extraction from the whole sentence. The two models, {\it AB-LSTM} and {\it Joint AB-LSTM} also use attentive pooling in the output of Bi-LSTM layer to assign weights to features. Our experimental results on the SemEval-2013 DDI extraction dataset show that the {\it Joint AB-LSTM} model outperforms all the existing methods, including those relying on handcrafted features. The other two proposed LSTM models also perform competitively with state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1701.08303](https://arxiv.org/abs/1701.08303)

##### PDF
[https://arxiv.org/pdf/1701.08303](https://arxiv.org/pdf/1701.08303)

