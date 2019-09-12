---
title: "Learning to Translate in Real-time with Neural Machine Translation"
collection: publications
permalink: /publication/simultaneous-nmt
excerpt: '**Jiatao Gu**, Graham Neubig, Kyunghyun Cho and Victor O.K. Li'
date: 2017-04-10
venue: 'Conference of the European Chapter
        of the Association for Computational Linguistics (EACL)'
---

![png](/images/eacl2017.png)<br>
**Abstract** <br>
Translating in real-time, a.k.a. simultaneous translation, outputs translation words before the input sentence ends, which is a challenging problem for conventional machine translation methods. We propose a neural machine translation (NMT) frame-work for simultaneous translation in which an agent learns to make decisions on when to translate from the interaction with a pre-trained NMT environment. To trade off quality and delay, we extensively explore various targets for delay and design a method for beam-search applicable in the simultaneous MT setting. Experiments against state-of-the-art baselines on two language pairs demonstrate the efficacy of the proposed framework both quantitatively and qualitatively

[paper] [code]

Please cite as:
```bibtex
@article{gu2016learning,
  title={Learning to translate in real-time with neural machine translation},
  author={Gu, Jiatao and Neubig, Graham and Cho, Kyunghyun and Li, Victor OK},
  journal={arXiv preprint arXiv:1610.00388},
  year={2016}
}
```