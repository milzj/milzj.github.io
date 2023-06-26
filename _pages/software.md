---
layout: page
permalink: /software/
title: software
description: 
nav: true
nav_order: 6
---

#### [FW4PDE](https://github.com/milzj/FW4PDE): Frank--Wolfe algorithms for PDE-constrained optimization

The package implements conditional gradient methods for the solution 
of the PDE-constrained optimization problems

$$
	\min_{u \in U_{\text{ad}}}  J(S(u)) + \beta \\|u\\|_{L^1(D)},
$$

where $\beta \geq 0$, $S(u)$ is the solution to a potentially nonlinear PDE, and 
$U_{\text{ad}} = \\{ u \in L^2(D) : a \leq u \leq b \\}$. Here $a$, $b \in L^2(D)$
with $a \leq b$.
