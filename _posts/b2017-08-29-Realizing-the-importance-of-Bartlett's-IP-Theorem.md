---
layout: post
published: true
show-avatar: true
image: "/img/amino-acid.jpeg"
title: Realizing the importance of Bartlett's IP theorem in Density Functional Theory
---
![amino-acid.jpeg]({{site.baseurl}}/img/amino-acid.jpeg)
#### What do we mean by Density Functional Theory (DFT) ?

Density Functional theory (DFT) has emerged as  a workhorse of computational chemistry due its low computational cost and being a good approximation to correlated single particle theory. DFT offers a potential ways to avoid solving Schr$\"{o}$dinger equation and to provide the electronic structure by just knowing the exact density.

$$ 
\begin{align*}
\hat{H} | \Psi (\vec{x}) \rangle = E | \Psi (\vec{x}) \rangle
\end{align*}
$$

DFT is based on the idea that one does not need full information of wavefunction to obtain the expectation value of the Hamiltonian.

$$ 
\begin{align*}
E = \langle \Psi | \hat{H} | \Psi \rangle = \sum_{\mu\nu} h_{\mu\nu}P_{\mu\nu} +  \sum_{\mu\nu\lambda\sigma}  \; \Gamma_{\mu\nu\lambda\sigma}(\mu\nu|\lambda\sigma) 
\end{align*}
$$


```python

```
