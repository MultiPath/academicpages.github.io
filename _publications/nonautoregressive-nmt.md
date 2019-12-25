---
title: "Non-autoregressive Neural Machine Translation"
collection: publications
permalink: /publication/nonautoregressive-nmt
excerpt: '**Jiatao Gu**, James Bradbury, Caiming Xiong, Victor O.K. Li and Richard Socher'
date: 2018-04-30
venue: 'International Conference on Learning Representations (ICLR)'
---

![png](/images/nat.png)<br>
**Abstract** <br>
Existing approaches to neural machine translation condition each output word on previously generated outputs. We introduce a model that avoids this autoregressive property and produces its outputs in parallel, allowing an order of magnitude lower latency during inference. Through knowledge distillation, the use of input token fertilities as a latent variable, and policy gradient fine-tuning, we achieve this at a cost of as little as 2.0 BLEU points relative to the autoregressive Transformer network used as a teacher. We demonstrate substantial cumulative improvements associated with each of the three aspects of our training strategy, and validate our approach on IWSLT 2016 English–German and two WMT language pairs. By sampling fertilities in parallel at inference time, our non-autoregressive model achieves near-state-of-the-art performance of 29.8 BLEU on WMT 2016 English–Romanian.

[paper] [code]


Please cite as:
```bibtex
@inproceedings{gu2017non,
  title={Non-autoregressive neural machine translation},
  author={Gu, Jiatao and Bradbury, James and Xiong, Caiming and Li, Victor O.K. and Socher, Richard},
  booktitle = {6th International Conference on Learning Representations, {ICLR} 2018,
               Vancouver, Canada, April 30-May 3, 2018, Conference Track Proceedings},
  year      = {2018}
}
```