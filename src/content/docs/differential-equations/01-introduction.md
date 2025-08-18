---
title: Introduction to Differential Equations
sidebar:
  order: 1
  label: Introduction
slug: differential-equations/introduction
prev: false
next: true
---

Different methods of solving differential equations, especially partial differential equations are dicussed here.

## Definitions

### Even function

When a function is symmetric about the y-axis.

```math
\forall x \in \text{Dom}(f)\, f(-x) = f(x)
```

### Odd function

When a function is skew-symmetric about the y-axis.

```math
\forall x \in \text{Dom}(f)\, f(-x) = -f(x)
```

:::note

Some functions are neither even nor odd.

Any real-valued function can be expressed as a sum of even and odd functions.

:::

### Periodic function

$f$ is periodic **iff**:

```math
\exists p \gt 0\, \forall x \in \text{Dom}(f)\, f(x+p) = f(x)
```

The smallest $p$ satisfying the above realtionship is called the period. The function is also called as p-periodic.

### Orthogonal

2 distinct functions, $f$ and $g$, are orthogonal over the interval $[a, b]$ (or $(a,b)$ or $(a,b]$ or $[a,b)$) **iff**:

```math
\int_a^b f(x)g(x)\,\text{d}x = 0
```

A set of functions $f_i$ are orthogonal over the interval $[a, b]$ (or $(a,b)$ or $(a,b]$ or $[a,b)$) **iff**:

```math
\int_a^b f_i(x)f_j(x)\,\text{d}x = 0 \quad \text{for} \quad i \neq j
```
