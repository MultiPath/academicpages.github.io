---
title: "Trainable Greedy Decoding for Neural Machine Translation"
collection: publications
permalink: /publication/trainable-greedy-decoding
excerpt: '**Jiatao Gu**, Kyunghyun Cho and Victor O.K. Li'
date: 2017-11-01
venue: 'Conference on Empirical Methods in Natural Language Processing (EMNLP)'
---

![png](/images/emnlp2017.png)<br>
**Abstract** <br>
Recent research in neural machine trans- lation has largely focused on two aspects; neural network architectures and end-to-end learning algorithms. The problem of decoding, however, has received relatively little attention from the research community. In this paper, we solely focus on the problem of decoding given a trained neural machine translation model. Instead of trying to build a new decoding algorithm for any specific decoding objective, we propose the idea of trainable decoding algorithm in which we train a decoding algo- rithm to find a translation that maximizes an arbitrary decoding objective. More specifically, we design an actor that observes and manipulates the hidden state of the neural machine translation decoder and propose to train it using a variant of deterministic policy gradient. We exten-sively evaluate the proposed algorithm us- ing four language pairs and two decoding objectives, and show that we can indeed train a trainable greedy decoder that generates a better translation (in terms of a target decoding objective) with minimal computational overhead.

[paper] [code]

Please cite as:
```bibtex

```