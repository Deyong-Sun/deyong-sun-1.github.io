---
layout: post
title: Continuum Mechanics
categories: [general-note, continuum-mechanics]
comments: true
description: >
  [Picture](https://upload.wikimedia.org/wikipedia/commons/thumb/2/23/Continuum_body.svg/200px-Continuum_body.svg.png)
image: https://upload.wikimedia.org/wikipedia/commons/thumb/2/23/Continuum_body.svg/200px-Continuum_body.svg.png
sitemap: false
---

Some learning material.

## 1. Kinematics
* Deformation gradient

$$ \mathbf{F}(\mathbf{X},t)=\Delta \chi = \frac{\partial}{\partial \mathbf{X}} \chi(\mathbf{X},t)  $$

* Determinant of $\mathnf{F}$
$$ J \equiv det(\frac{\partial \chi}{\partial \mathbf{X}}) =det \mathbf{F}\neq 0 $$

* Polar decomposition theorem

$$ \mathbf{F}=\mathbf{RU}=\mathbf{VR}$$
where F is a symmetric matrix, R is a unitary matrix (rotation/reflection), and U and V (stretch) are the right and left polar
decompositions of F.

* The right and left Cauchy-Green (deformation) tensors C and B are defined by

$$ \mathbf{C=U^2=F^{T}F}$$
$$ \mathbf{B=V^2=FF^{T}}$$
where C and B are symmetric and positive definite.

