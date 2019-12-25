---
title: "Monotonic Multihead Attention"
collection: publications
permalink: /publication/monotonic-multi-head
excerpt: "Xutai Ma, Juan Pino, James Cross, Liezl Puzon, **Jiatao Gu**"
date: 2020-04-26
venue: 'International Conference on Learning Representations (ICLR)'
---


**Abstract** <br>
Simultaneous machine translation models start generating a target sequence before they have encoded or read the source sequence. Recent approaches for this task either apply a fixed policy on a state-of-the art Transformer model, or a learnable monotonic attention on a weaker recurrent neural network-based structure. In this paper, we propose a new attention mechanism, Monotonic Multihead Attention (MMA), which extends the monotonic attention mechanism to multihead attention. We also introduce two novel and interpretable approaches for latency control that are specifically designed for multiple attentions heads. We apply MMA to the simultaneous machine translation task and demonstrate better latency-quality tradeoffs compared to MILk, the previous state-of-the-art approach. We also analyze how the latency controls affect the attention span and we motivate the introduction of our model by analyzing the effect of the number of decoder layers and heads on quality and latency.
[[paper]](https://arxiv.org/pdf/1909.12406.pdf) [code]

Please cite as:
```bibtex
@article{ma2019monotonic,
  title={Monotonic Multihead Attention},
  author={Ma, Xutai and Pino, Juan and Cross, James and Puzon, Liezl and Gu, Jiatao},
  journal={8th International Conference on Learning Representations, {ICLR} 2020,
           Addis Ababa, Ethiopia, April 26-30, 2020, Conference Track Proceedings},
  year={2020}
}
```