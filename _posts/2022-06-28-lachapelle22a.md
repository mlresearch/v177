---
abstract: This work introduces a novel principle we call disentanglement via mechanism
  sparsity regularization, which can be applied when the latent factors of interest
  depend sparsely on past latent factors and/or observed auxiliary variables. We propose
  a representation learning method that induces disentanglement by simultaneously
  learning the latent factors and the sparse causal graphical model that relates them.
  We develop a rigorous identifiability theory, building on recent nonlinear independent
  component analysis (ICA) results, that formalizes this principle and shows how the
  latent variables can be recovered up to permutation if one regularizes the latent
  mechanisms to be sparse and if some graph connectivity criterion is satisfied by
  the data generating process. As a special case of our framework, we show how one
  can leverage unknown-target interventions on the latent factors to disentangle them,
  thereby drawing further connections between ICA and causality. We propose a VAE-based
  method in which the latent mechanisms are learned and regularized via binary masks,
  and validate our theory by showing it learns disentangled representations in simulations.
booktitle: First Conference on Causal Learning and Reasoning
title: 'Disentanglement via Mechanism Sparsity Regularization: A New Principle for
  Nonlinear ICA'
year: '2022'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: lachapelle22a
month: 0
tex_title: 'Disentanglement via Mechanism Sparsity Regularization: A New Principle
  for Nonlinear {ICA}'
firstpage: 428
lastpage: 484
page: 428-484
order: 428
cycles: false
bibtex_author: Lachapelle, Sebastien and Rodriguez, Pau and Sharma, Yash and Everett,
  Katie E and PRIOL, R{\'e}mi LE and Lacoste, Alexandre and Lacoste-Julien, Simon
author:
- given: Sebastien
  family: Lachapelle
- given: Pau
  family: Rodriguez
- given: Yash
  family: Sharma
- given: Katie E
  family: Everett
- given: Rémi LE
  family: PRIOL
- given: Alexandre
  family: Lacoste
- given: Simon
  family: Lacoste-Julien
date: 2022-06-28
address:
container-title: Proceedings of the First Conference on Causal Learning and Reasoning
volume: '177'
genre: inproceedings
issued:
  date-parts:
  - 2022
  - 6
  - 28
pdf: https://proceedings.mlr.press/v177/lachapelle22a/lachapelle22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
