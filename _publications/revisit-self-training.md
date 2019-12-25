---
title: "Revisiting Self-Training for Neural Sequence Generation"
collection: publications
permalink: /publication/revisit-self-training
excerpt: "Junxian He^, **Jiatao Gu**^, Jiajun Shen and Marc'Aurelio Ranzato"
date: 2020-04-26
venue: 'International Conference on Learning Representations (ICLR)'
---

![png](/images/self_training.jpg)<br>
**Abstract** <br>
Self-training is one of the earliest and simplest semi-supervised methods. The key
idea is to augment the original labeled dataset with unlabeled data paired with the
model’s prediction (i.e. the pseudo-parallel data). While self-training has been extensively studied on classification problems, in complex sequence generation tasks
(e.g. machine translation) it is still unclear how self-training works due to the compositionality of the target space. In this work, we first empirically show that selftraining is able to decently improve the supervised baseline on neural sequence
generation tasks. Through careful examination of the performance gains, we find
that the perturbation on the hidden states (i.e. dropout) is critical for self-training
to benefit from the pseudo-parallel data, which acts as a regularizer and forces the
model to yield close predictions for similar unlabeled inputs. Such effect helps
the model correct some incorrect predictions on unlabeled data. To further encourage this mechanism, we propose to inject noise to the input space, resulting
in a “noisy” version of self-training. Empirical study on standard machine translation and text summarization benchmarks shows that noisy self-training is able to
effectively utilize unlabeled data and improve the performance of the supervised
baseline by a large margin.

[[paper]](https://arxiv.org/pdf/1909.13788.pdf) [code]

Please cite as:
```bibtex
@article{he2019revisiting,
  title={Revisiting Self-Training for Neural Sequence Generation},
  author={He, Junxian and Gu, Jiatao and Shen, Jiajun and Ranzato, Marc'Aurelio},
  journal={8th International Conference on Learning Representations, {ICLR} 2020,
           Addis Ababa, Ethiopia, April 26-30, 2020, Conference Track Proceedings},
  year={2020}
}
```