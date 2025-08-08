---
title: Hypergeometric Distribution
sidebar:
  order: 4
slug: applied-statistics/hypergeometric-distribution
prev: true
next: true
---

:::caution

Hypergeometric distribution has no relation to the geometric distribution.

:::

### Hypergeometric Experiment

From a population of size $N$ containing $k$ successes, a sample of size $n$ without replacement. Number of successes in the sample is observed and denoted by $X$.

The hypergeometric distribution describes the probability of obtaining $k$ successes in a hypergeometric experiment. Denoted by $h(x;N,n,k)$.

```math
P(x) = \frac{^kC_x \times\; ^{N-k}C_{n-x}}{^NC_n}
```

## Mean
```math
\mu_x = \frac{nk}{N}
```

## Variance
```math
V_x = \frac{nk(N-k)(N-n)}{N^2 (N - 1)}
```

## Cumulative Hypergeometric Distribution

Refers to the probability that the hypergeometric random variable is greater than a lower limit or lesser than an upper limit.

## Multivariate Hypergeometric Distribution

Suppose a population of size $N$, having $k$ different types of items. Each type has $N_1, N_2, \ldots, N_k$ items.

```math
\sum_{i=1}^{k} N_i = N
```

Multivariate Hypergeometric Distribution describes the probability of obtaining $x_1, x_2, \ldots, x_k$ items from the above population. Denoted by $h(\mathbf{x};N,n,\mathbf{N})$.

```math
P(x_1, x_2, \dots, x_k) = \frac{\binom{N_1}{x_1} \cdot \binom{N_2}{x_2} \cdot \ldots \cdot \binom{N_k}{x_k}}{\binom{N}{n}}
```
