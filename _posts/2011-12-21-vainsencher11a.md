---
title: The Sample Complexity of Dictionary Learning
abstract: A large set of signals can sometimes be described sparsely using a dictionary,
  that is, every element can be represented as a linear combination of few elements
  from the dictionary.  Algorithms for various signal processing applications, including
  classification, denoising and signal separation, learn a dictionary from a given
  set of signals to be represented. Can we expect that the error in representing by
  such a dictionary a previously unseen signal from the same source will be of similar
  magnitude as those for the given examples?We assume signals are generated from a
  fixed distribution, and study these questions from a statistical learning theory
  perspective. We develop generalization bounds on the quality of the learned dictionary
  for two types of constraints on the coefficient selection, as measured by the expected
  L_2 error in representation when the dictionary is used.For the case of l_1 regularized
  coefficient selection we provide a generalization bound of the order of O\left(\sqrtnp\ln(m
  λ)/m\right), where n is the dimension, p is the number of elements in the dictionary,
  λis a bound on the l_1 norm of the coefficient vector and m is the number of samples,
  which complements existing results.For the case of representing a new signal as
  a combination of at most k dictionary elements, we provide a bound ofthe order O(\sqrtnp\ln(m
  k)/m) under an assumption on the closeness to orthogonality of the dictionary (low
  Babel function).We further show that this assumption holds for \em most dictionaries
  in high dimensions in a strong probabilistic sense.Our results also include bounds
  that converge as 1/m, not previously known for this problem.We provide similar results
  in a general setting using kernels with weak smoothness requirements.
pdf: http://proceedings.mlr.press/v19/vainsencher11a/vainsencher11a.pdf
layout: inproceedings
series: Proceedings of Machine Learning Research
id: vainsencher11a
month: 0
tex_title: The Sample Complexity of Dictionary Learning
firstpage: 773
lastpage: 788
page: 773-788
order: 773
cycles: false
author:
- given: Daniel
  family: Vainsencher
- given: Shie
  family: Mannor
- given: Alfred M.
  family: Bruckstein
date: 2011-12-21
address: Budapest, Hungary
publisher: PMLR
container-title: Proceedings of the 24th Annual Conference on Learning Theory
volume: '19'
genre: inproceedings
issued:
  date-parts:
  - 2011
  - 12
  - 21
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
