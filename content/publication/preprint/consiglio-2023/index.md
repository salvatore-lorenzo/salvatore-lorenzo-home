---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Variational Gibbs State Preparation on NISQ Devices
subtitle: ''
summary: ''
authors:
- Mirko Consiglio
- Jacopo Settino
- Andrea Giordano
- Carlo Mastroianni
- Francesco Plastina
- Salvatore Lorenzo
- Sabrina Maniscalco
- John Goold
- Tony J. G. Apollaro
tags:
- Condensed Matter - Statistical Mechanics
- Quantum Physics
categories: []
date: '2023-03-01'
lastmod: 2023-03-21T22:03:10+01:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2023-03-21T21:03:10.405863Z'
publication_types:
- '3'
abstract: The preparation of an equilibrium thermal state of a quantum many-body system
  on noisy intermediate-scale (NISQ) devices is an important task in order to extend
  the range of applications of quantum computation. Faithful Gibbs state preparation
  would pave the way to investigate protocols such as thermalization and out-of-equilibrium
  thermodynamics, as well as providing useful resources for quantum algorithms, where
  sampling from Gibbs states constitutes a key subroutine. We propose a variational
  quantum algorithm (VQA) to prepare Gibbs states of a quantum many-body system. The
  novelty of our VQA consists in implementing a parameterized quantum circuit acting
  on two distinct, yet connected, quantum registers. The VQA evaluates the Helmholtz
  free energy, where the von Neumann entropy is obtained via post-processing of computational
  basis measurements on one register, while the Gibbs state is prepared on the other
  register, via a unitary rotation in the energy basis. Finally, we benchmark our
  VQA by preparing Gibbs states of the transverse field Ising model and achieve remarkably
  high fidelities across a broad range of temperatures in statevector simulations.
  We also assess the performance of the VQA on IBM quantum computers, showcasing its
  feasibility on current NISQ devices.
publication: '*arXiv*'
doi: 10.48550/arXiv.2303.11276
links:
- name: arXiv
  url: https://arxiv.org/abs/arXiv:2303.11276
---
