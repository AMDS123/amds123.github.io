---
layout: post
title: "Where to put the Image in an Image Caption Generator"
date: 2018-03-14 08:56:53
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption RNN Language_Model
author: Marc Tanti (1), Albert Gatt (1), Kenneth P. Camilleri (1) ((1) University of Malta)
mathjax: true
---

* content
{:toc}

##### Abstract
When a recurrent neural network language model is used for caption generation, the image information can be fed to the neural network either by directly incorporating it in the RNN -- conditioning the language model by `injecting' image features -- or in a layer following the RNN -- conditioning the language model by `merging' image features. While both options are attested in the literature, there is as yet no systematic comparison between the two. In this paper we empirically show that it is not especially detrimental to performance whether one architecture is used or another. The merge architecture does have practical advantages, as conditioning by merging allows the RNN's hidden state vector to shrink in size by up to four times. Our results suggest that the visual and linguistic modalities for caption generation need not be jointly encoded by the RNN as that yields large, memory-intensive models with few tangible advantages in performance; rather, the multimodal integration should be delayed to a subsequent stage.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1703.09137](https://arxiv.org/abs/1703.09137)

##### PDF
[https://arxiv.org/pdf/1703.09137](https://arxiv.org/pdf/1703.09137)

