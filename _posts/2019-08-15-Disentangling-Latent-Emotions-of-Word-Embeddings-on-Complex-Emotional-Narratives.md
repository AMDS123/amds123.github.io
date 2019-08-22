---
layout: post
title: "Disentangling Latent Emotions of Word Embeddings on Complex Emotional Narratives"
date: 2019-08-15 11:05:45
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Zhengxuan Wu, Yueyi Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
Word embedding models such as GloVe are widely used in natural language processing (NLP) research to convert words into vectors. Here, we provide a preliminary guide to probe latent emotions in text through GloVe word vectors. First, we trained a neural network model to predict continuous emotion valence ratings by taking linguistic inputs from Stanford Emotional Narratives Dataset (SEND). After interpreting the weights in the model, we found that only a few dimensions of the word vectors contributed to expressing emotions in text, and words were clustered on the basis of their emotional polarities. Furthermore, we performed a linear transformation that projected high dimensional embedded vectors into an emotion space. Based on NRC Emotion Lexicon (EmoLex), we visualized the entanglement of emotions in the lexicon by using both projected and raw GloVe word vectors. We showed that, in the proposed emotion space, we were able to better disentangle emotions than using raw GloVe vectors alone. In addition, we found that the sum vectors of different pairs of emotion words successfully captured expressed human feelings in the EmoLex. For example, the sum of two embedded word vectors expressing Joy and Trust which express Love shared high similarity (similarity score .62) with the embedded vector expressing Optimism. On the contrary, this sum vector was dissimilar (similarity score -.19) with the the embedded vector expressing Remorse. In this paper, we argue that through the proposed emotion space, arithmetic of emotions is preserved in the word vectors. The affective representation uncovered in emotion vector space could shed some light on how to help machines to disentangle emotion expressed in word embeddings.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07817](http://arxiv.org/abs/1908.07817)

##### PDF
[http://arxiv.org/pdf/1908.07817](http://arxiv.org/pdf/1908.07817)

