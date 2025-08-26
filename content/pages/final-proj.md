---
content_type: page
description: This is the end
draft: false
title: Final proj
uid: 328cc676-2e96-4a68-bf28-9493e1bd3f62
---
- Contagious structures for projections. In class we used Plunnecke inequality and Ruzsa inequality to prove contagious structure for projections of \\(A \\times A \\subset \\mathbb{F}\_p^2\\). Are there similar results for projections of an arbitrary set \\(X \\subset \\mathbb{F}\_q^2\\)? Here is a precise question. Suppose that \\(| \\pi\_t(X) | \\le K |X|^{1/2}\\) for \\(t= 0, \\infty, t\_1\\), and \\(t\_2\\). Does it follow that \\(| \\pi\_{t\_1 + t\_2} (X)| \\le K^C |X|^{1/2}\\) for a universal constant \\(C\\)? (What \\(C\\) can you get?) Similarly for \\(|\\pi\_{t\_1 t\_2}(X)|\\) and \\(| \\pi\_{-t}(X)|\\). See Lecture 11. (Possible reference: Katz-Tao's work on "sums differences")
- Projections in algebraically independent directions. Suppose that \\(D = {0, 1, \\infty, t\_1, …, t\_r} \\subset \\mathbb{R}\\). Let \\(\\pi\_t(x\_1, x\_2) = x\_1 + t x\_2\\). Let \\(X\\) be a finite subset of \\(\\mathbb{R}^2\\). Define

\\[S\_D(N) = \\min\_{|X| = N} \\max\_{t \\in D} | \\pi\_t(X)|.\\]

> If \\(t\_1, …, t\_r\\) are algebraically independent over \\(\\mathbb{Q}\\), what upper and lower bounds can you prove on \\(S\_D(N)\\) (in terms of \\(N\\) and \\(r\\))? Might want to start with \\(r=1\\).

- Optional question from pset 5, related to Bombieri-Vinogradov. In pset 5, using the large sieve, we proved the following estimate. If \\(X \\subset [N]\\), then for \\(90\\%\\) of \\(p \\in P\_{N^{1/2}}\\),

> **Equation 1.** \\(\\Vert (\\pi\_p 1\_X)\_h^{\*2} \\Vert\_{L^\\infty(\\mathbb{Z}\_p)} \\lessapprox |X|.\\)

> This bound is sharp when \\(X\\) is an arithmetic progression of length \\(N^\\alpha\\) with \\(\\alpha < 1/2\\). But in this case, \\(\\Vert 1\_X^{\*2} \\Vert\_{\\ell^\\infty}\\) is itself large. Suppose that \\(X \\subset [N]\\) with \\(|X| \\sim N^{1/2}\\), and suppose that \\(\\Vert1\_X^{\*2} \\Vert\_{L^\\infty} \\lessapprox 1\\). For most \\(p \\in P\_{N^{1/2}}\\), can we prove a bound for \\(\\Vert(\\pi\_p 1\_X)^{\*2}\_h \\Vert\_{L^\\infty(\\mathbb{Z}\_p)}\\) which improves on Equation 1?

- Optional question from pset 4, related to the large sieve. To pursue this direction, it would be helpful to have a little background in restriction theory in Fourier analysis. In class, we used the large sieve to prove the following estimate.

> **Theorem 1.** *If* \\(X \\subset [N]\\) *and* \\(| \\pi\_p(X) | \\le (0.99) p\\) *for every* \\(p \\in P\_{N^{1/2}}\\)*, then* \\(|X| \\lessapprox N^{1/2}\\)

> This theorem is essentially sharp when \\(X\\) is the set of squares. We could explore what happens if we know \\(| \\pi\_p(X) \\le (0.99) p\\) for every \\(p \\in P\_{N^\\alpha}\\) for some other exponent \\(\\alpha\\), such as \\(\\alpha = 1/4\\). Or we could explore what happens if we replace \\(| \\pi\_p(X)| \\le (0.99) p\\) by a stronger bound like \\(|\\pi\_p(X)| \\le N^{1/4}\\) for every \\(p \\in P\_{N^{1/2}}\\).

- Non-commutative projection theory. We have presented projection theory in the context of commutative groups. The setting is that we have a commutative group \\(G\\) and many homomorphisms \\(\\pi\_j: G \\rightarrow H\_j\\). Each homomorphism can be described by its kernel, \\(K\_j\\). So \\(\\pi\_j: G \\rightarrow G / K\_j\\). Now suppose that \\(G\\) is a non-commutative group. Let \\(K\_j\\) be a bunch of subgroups, and consider the maps \\(\\pi\_j G \\rightarrow G / K\_j\\). How much of what we discussed in class can be generalized to this setting? Might help to think in general or might help to pick a simple non-commutative group, such as \\(SL\_2(\\mathbb{F}\_p)\\). Projection theory for general commutative groups \\(G\\) is also a possible project to explore.
- Something else that you think of.