---
layout: post
title: "Relational Long Short-Term Memory for Video Action Recognition"
date: 2018-11-16 23:03:23
categories: arXiv_CV
tags: arXiv_CV Action_Recognition RNN Relation Recognition
author: Zexi Chen, Bharathkumar Ramachandra, Tianfu Wu, Ranga Raju Vatsavai
mathjax: true
---

* content
{:toc}

##### Abstract
Spatial and temporal relationships, both short-range and long-range, between objects in videos are key cues for recognizing actions. It is a challenging problem to model them jointly. In this paper, we first present a new variant of Long Short-Term Memory, namely Relational LSTM to address the challenge for relation reasoning across space and time between objects. In our Relational LSTM module, we utilize a non-local operation similar in spirit to the recently proposed non-local network to substitute the fully connected operation in the vanilla LSTM. By doing this, our Relational LSTM is capable of capturing long and short-range spatio-temporal relations between objects in videos in a principled way. Then, we propose a two-branch neural architecture consisting of the Relational LSTM module as the non-local branch and a spatio-temporal pooling based local branch. The local branch is introduced for capturing local spatial appearance and/or short-term motion features. The two-branch modules are concatenated to learn video-level features from snippet-level ones end-to-end. Experimental results on UCF-101 and HMDB-51 datasets show that our model achieves state-of-the-art results among LSTM-based methods, while obtaining comparable performance with other state-of-the-art methods (which use not directly comparable schema). Our code will be released.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07059](http://arxiv.org/abs/1811.07059)

##### PDF
[http://arxiv.org/pdf/1811.07059](http://arxiv.org/pdf/1811.07059)

