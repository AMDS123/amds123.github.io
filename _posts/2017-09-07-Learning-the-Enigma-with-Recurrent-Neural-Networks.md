---
layout: post
title: "Learning the Enigma with Recurrent Neural Networks"
date: 2017-09-07 19:05:23
categories: arXiv_CV
tags: arXiv_CV Image_Caption Speech_Recognition Caption RNN Recognition
author: Sam Greydanus
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks (RNNs) represent the state of the art in translation, image captioning, and speech recognition. They are also capable of learning algorithmic tasks such as long addition, copying, and sorting from a set of training examples. We demonstrate that RNNs can learn decryption algorithms -- the mappings from plaintext to ciphertext -- for three polyalphabetic ciphers (Vigenère, Autokey, and Enigma). Most notably, we demonstrate that an RNN with a 3000-unit Long Short-Term Memory (LSTM) cell can learn the decryption function of the Enigma machine. We argue that our model learns efficient internal representations of these ciphers 1) by exploring activations of individual memory neurons and 2) by comparing memory usage across the three ciphers. To be clear, our work is not aimed at 'cracking' the Enigma cipher. However, we do show that our model can perform elementary cryptanalysis by running known-plaintext attacks on the Vigenère and Autokey ciphers. Our results indicate that RNNs can learn algorithmic representations of black box polyalphabetic ciphers and that these representations are useful for cryptanalysis.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1708.07576](https://arxiv.org/abs/1708.07576)

##### PDF
[https://arxiv.org/pdf/1708.07576](https://arxiv.org/pdf/1708.07576)

